# 자취메이트 설정 가이드

같은 학교 자취생끼리 공동구매·나눔을 연결하는 웹사이트예요.

| 파일 | 설명 |
|---|---|
| `index.html` | 사이트 전체 (HTML·CSS·JavaScript) |
| `firestore.rules` | Firebase 데이터베이스 보안 규칙 |
| `README.md` | 이 설명서 |
| `presentation/jachimate_presentation.pdf` | 발표자료 (13장) |

## 동작 방식

`index.html` 맨 아래 `CONFIG`에 키를 넣었는지에 따라 자동으로 바뀝니다.

| | 키를 안 넣으면 (데모 모드) | 키를 넣으면 |
|---|---|---|
| 로그인 | 학교 도메인만 확인 | **Firebase Authentication**: 학교 메일로 실제 인증 메일 발송 |
| 글 저장 | 내 브라우저에만 저장 | **Cloud Firestore**: 모든 사용자가 실시간으로 같은 글을 봄 |
| 지도 | 직접 그린 기본 지도 | **카카오맵 API** |

Firebase와 카카오맵은 따로 켤 수 있어요. 하나만 넣어도 됩니다.

---

## 1. Firebase 연결 (로그인 + 데이터베이스)

1. https://console.firebase.google.com 에서 **프로젝트 만들기**를 해요. Google 애널리틱스는 꺼도 돼요.
2. 프로젝트 홈에서 **웹 앱 추가(</> 아이콘)**를 누르고 앱 이름을 정하세요. 호스팅 체크는 하지 않아도 돼요.
3. 화면에 나오는 `firebaseConfig = { apiKey: ..., ... }` 값을 복사해서 `index.html`의 `CONFIG.FIREBASE`에 붙여넣어요.
4. 왼쪽 메뉴 **빌드 > Authentication > 시작하기 > 이메일/비밀번호**를 **사용 설정**해요.
5. **빌드 > Firestore Database > 데이터베이스 만들기**를 해요. 위치는 `asia-northeast3 (서울)`로 정하세요.
6. Firestore의 **규칙** 탭에 `firestore.rules` 내용을 그대로 붙여넣고 **게시**해요.
   - 학교를 제한하려면 규칙의 `ac[.]kr`과 `index.html`의 `SCHOOL_DOMAIN`을 둘 다 같은 학교 도메인으로 바꾸세요.
7. **Authentication > 설정 > 승인된 도메인**에 배포한 사이트 주소(예: `jachimate.netlify.app`)를 추가해요.

> `apiKey`는 웹사이트에 공개돼도 괜찮은 값이에요. 데이터는 6번의 보안 규칙이 지켜 줘요. 인증 메일을 확인한 학교 메일 사용자만 읽고 쓸 수 있어요.

## 2. 카카오맵 연결 (지도)

1. https://developers.kakao.com 에 로그인하고 **내 애플리케이션 > 애플리케이션 추가하기**를 눌러요.
2. 앱의 **제품 설정 > 카카오맵 > 사용 설정**을 **ON**으로 바꿔요. 이걸 안 하면 지도가 안 떠요.
3. **앱 > 플랫폼 키 > JavaScript 키**를 복사해서 `CONFIG.KAKAO_JS_KEY`에 붙여넣어요.
4. 같은 JavaScript 키의 **JavaScript SDK 도메인**에 사이트 주소를 등록해요.
   - 배포 주소: `https://jachimate.netlify.app` (본인 주소)
   - 내 컴퓨터 테스트용: `http://localhost:8000`
5. 나눔 지도는 **브라우저의 현재 위치**를 기준으로 반경 안의 나눔만 보여줘요.
   - 기본 반경은 1km예요. 화면에서 500m, 1km, 2km, 전체 중에 고를 수 있어요. 기본값은 `CONFIG.RADIUS`에서 바꿔요.
   - 위치 권한을 거절하면 학교 주소(`CONFIG.SCHOOL_ADDRESS`)를 기준으로 보여줘요.
   - 현재 위치로 글을 올리면 집이 드러나지 않게 `CONFIG.PRIVACY_JITTER`(40m) 안쪽에서 살짝 옮겨 저장해요.
   - 위치 기능은 `https://` 주소나 `localhost`에서만 동작해요.

## 3. 내 컴퓨터에서 테스트

`index.html`을 더블클릭해서 열면 카카오맵과 Firebase가 동작하지 않을 수 있어요. 폴더에서 아래 명령으로 간단한 서버를 켜세요.

```
python -m http.server 8000
```

그다음 브라우저에서 http://localhost:8000 에 들어가면 돼요.

## 4. 배포 (Netlify)

1. https://app.netlify.com/drop 에 들어가요.
2. 이 폴더를 통째로 끌어다 놓으면 바로 주소가 생겨요.
3. 생긴 주소를 Firebase **승인된 도메인**(1-7)과 카카오 **JavaScript SDK 도메인**(2-4)에 등록하세요.

## 5. 발표 전 체크리스트

- [ ] 학교 메일 계정 **2개**로 가입·인증해 두기 (한 명은 글쓰기, 한 명은 참여하기 시연)
- [ ] 공동구매 3~4개, 나눔 3~4개 미리 올려 두기 (Firebase 모드는 처음에 비어 있어요)
- [ ] 발표 컴퓨터에서 지도와 로그인이 되는지 미리 확인
- [ ] 인터넷이 안 될 때를 대비해 시연 화면 녹화해 두기
