# 🌐 Web Programming

웹 프로그래밍 과목 실습 및 과제 저장소입니다. HTML/CSS로 시작해 JavaScript 기초, DOM 조작, 이벤트 처리까지, 매주 학습한 내용을 `Problem`(기본 문제풀이)과 `OpenChallenge`(자유 과제) 형태로 정리하고 있습니다.

## 🛠️ 기술 스택

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 📂 폴더 구조

```
WebProgramming/
├── 0902 WebProgramming/
│   ├── chap1/          # 기본 태그 실습 (num1~4.html, profile.png)
│   └── report/         # 프로필 페이지 실습
│
├── 0909 WebProgramming/
│   ├── Problem/        # num1~num8: 이미지·오디오·비디오 삽입, 기본 스타일링
│   └── OpenChallenge/  # 아이폰 이미지 비교 페이지
│
├── 0916 WebProgramming/
│   ├── Problem/        # num1~num5: CSS 셀렉터, 테이블 실습
│   ├── OpenChellenge/  # hover 효과, 질의응답 페이지
│   └── index.html
│
├── 0923 WebProgramming/
│   ├── Problem/        # num1~num9: box-shadow, text-shadow 등 심화 스타일링
│   └── OpenChallenge/  # 설문(survey) 폼 페이지
│
├── 0930 WebProgramming/
│   ├── Problem/        # num1~num10: div, position, float, 리스트·메뉴, animation, transition
│   └── OpenChallenge/  # 스마트폰 소개 페이지(5.html), 소프트웨어 기술 선호 설문지(survey5.html)
│
├── 1007 WebProgramming/
│   ├── Problem/        # num1~num8: JavaScript 기초 (코드 위치, document.write, prompt, 함수, eval)
│   └── OpenChallenge/  # 별 문자 출력하기(6.html)
│
├── 1014 WebProgramming/
│   ├── Problem/        # num1~num10: 난수, 배열, Date, 문자열 처리, 객체(book)
│   └── OpenChallenge/  # 배열로 리스트 만들기(1.html)
│
├── 1028 WebProgramming/
│   ├── Problem/        # 01~10: DOM 객체 탐색·스타일 변경, z-index, transform, 요소 동적 생성/삭제
│   └── OpenChallenge/  # 갬블링 게임(8.html)
│
├── 1104 WebProgramming/
│   ├── Problem/        # 1~10: 이벤트 처리 (onblur/onfocus, onkeydown, onmousemove, onwheel, 이벤트 target), 계산기
│   └── OpenChallenge/  # 마우스 클릭으로 이미지 옮기기(9.html)
│
├── 1111 WebProgramming/
│   ├── Problem/        # 01~09: BOM(window.open, navigator, screen), setTimeout/setInterval 타이머, 시계·산수 문제 채점
│   └── OpenChallenge/  # 눈 내리는 마을 애니메이션(10.html)
│
├── IntroducePage/      # 자기소개 페이지 (index.html, css3.css, busan.mp4)
├── Jachimate/          # 기말 프로젝트: 자취생 공동구매·나눔 사이트 (Firebase·카카오맵)
│   └── presentation/   # 발표자료 PDF
├── Portfolio/          # 보안 진로 포트폴리오 사이트 (index.html 한 파일)
└── README.md
```

> 폴더명은 실습을 진행한 날짜(MMDD) 기준으로 되어 있습니다.

## 📅 주차별 실습 내용

| 날짜 | 폴더 | 주요 학습 내용 |
| --- | --- | --- |
| 09/02 | `0902 WebProgramming` | HTML 기본 태그, 프로필 페이지 만들기 |
| 09/09 | `0909 WebProgramming` | 이미지·오디오(`<audio>`)·비디오(`<video>`) 삽입, 페이지 레이아웃 |
| 09/16 | `0916 WebProgramming` | CSS 셀렉터(클래스/아이디), 테이블(`table-layout`), `:hover` 가상 클래스 |
| 09/23 | `0923 WebProgramming` | `text-shadow` / `box-shadow`, 설문 폼(`<form>`) 제작 |
| 09/30 | `0930 WebProgramming` | `<div>` 박스 구성, `position: fixed`, `float` 배치, 리스트(`ul`/`ol`)와 수직 메뉴, `@keyframes` 애니메이션, `transition`, 목차(앵커) 링크, 라디오·체크박스 설문 |
| 10/07 | `1007 WebProgramming` | JavaScript 코드 작성 위치(인라인·`<script>`·외부 `.js`), `document.write()`, `prompt()`, 함수, `eval()` |
| 10/14 | `1014 WebProgramming` | `Math.random()`, 배열 다루기(`sort`, `split`), `Date` 객체, 객체 생성(생성자 함수), 조건에 따른 배경색 변경 |
| 10/28 | `1028 WebProgramming` | `getElementById` / `getElementsByTagName`으로 DOM 객체 선택, `style` 속성 변경, `visibility`·`z-index`·`transform`(`rotate`, `scale`), `innerHTML`, `createElement` / `appendChild` / `removeChild`, `addEventListener` |
| 11/04 | `1104 WebProgramming` | `window.onblur` / `onfocus`, `onchange`(라디오 버튼), `onkeydown`(Enter 키), `onmousemove`(이미지 커서), `ondblclick`, `onwheel`, `onmouseover` / `onmouseout`, 이벤트 객체의 `target`, `onload` |
| 11/11 | `1111 WebProgramming` | `window.open()`으로 새 창 제어(크기·위치·창 공유), `navigator.userAgent`로 브라우저 판별, `screen` 객체로 해상도 확인, `setTimeout()` / `setInterval()` / `clearInterval()`로 시계 만들기, 타이머를 이용한 자동 채점 산수 퀴즈, 눈 내리는 애니메이션 |
| - | `IntroducePage` | 지금까지 배운 HTML/CSS를 종합한 자기소개 페이지 |
| - | `Portfolio` | HTML/CSS/JavaScript를 종합한 인터랙티브 포트폴리오 사이트 |
| - | `Jachimate` | 기말 프로젝트: 같은 학교 자취생끼리 공동구매·나눔을 연결하는 웹사이트 |

## ✨ 핵심 학습 요약

### HTML / CSS

- **미디어 삽입**: `<img>`, `<audio controls>`, `<video>` 태그로 이미지·소리·영상을 페이지에 삽입하는 방법을 익힘.
- **CSS 셀렉터 우선순위**: 태그 → 클래스(`.`) → 아이디(`#`) 순으로 우선순위가 높아지는 것을 실습을 통해 확인.
- **Shadow 계열 속성**: `text-shadow`는 `x y blur color` 3개 값 + 색상, `box-shadow`는 여기에 `spread` 값이 추가로 허용된다는 차이를 학습.
- **가상 클래스**: `:hover`를 이용해 마우스 오버 시 그림자·이미지 등이 동적으로 바뀌는 UI 구현.
- **폼(Form) 요소**: 설문 페이지를 만들며 `<input>`(`radio`, `checkbox`, `button`), `<label>` 등 사용자 입력 요소 학습.
- **레이아웃과 배치**: `position: fixed`로 화면 하단에 고정, `float`로 header / nav / section / footer 구조를 나란히 배치.
- **리스트와 메뉴**: `list-style-type: none`, `display: inline-block` 등으로 리스트를 가공해 순서 안내문과 수직 메뉴(`nav`) 제작.
- **애니메이션**: `@keyframes` + `animation` + `transform`으로 움직이는 효과를, `transition`으로 hover 시 부드러운 변화를 구현.

### JavaScript

- **코드 위치**: 이벤트 속성에 직접 작성, `<script>` 태그 내부, 외부 `.js` 파일로 분리하는 세 가지 방식을 비교.
- **입출력**: `prompt()`로 값을 입력받고 `document.write()`로 결과(별 모양, 표, 요일 등)를 출력.
- **함수와 연산**: 함수 정의·호출, `Math.floor()`로 자릿수 비교, `eval()`로 문자열 수식 계산.
- **난수**: `Math.random()` 과 `Math.floor()`를 조합해 난수 10개, 랜덤 색 16개 생성.
- **배열과 문자열**: 배열 순회·역순 출력, 가장 긴 이름 찾기, `sort()` 정렬, 문자열 분할.
- **Date 객체**: 방문 시각(오전/오후), 요일에 따라 `style.backgroundColor` 를 바꾸는 페이지 제작.
- **객체**: `book` 객체를 만들어 보며 생성자 함수(`function Book()` + `new`)로 객체를 생성하는 방법 학습.

### DOM 조작 (10/28)

- **DOM 객체 선택**: `getElementById()`, `getElementsByTagName()`으로 요소를 찾아 반복문으로 `style.color` 등을 일괄 변경.
- **계산된 스타일**: `window.getComputedStyle()`로 현재 `visibility` 값을 읽어 show/hide 토글 구현.
- **스타일 동적 변경**: `z-index`로 카드 겹침 순서 바꾸기, `transform: rotate()` / `scale()`로 클릭 시 이미지 회전·확대.
- **내용 변경**: `innerHTML`과 `prompt()`를 조합해 텍스트·HTML을 즉석에서 교체, `eval()`로 클릭하면 계산 결과 표시.
- **요소 동적 생성/삭제**: `createElement()` → `appendChild()`로 항목 추가, `removeChild()`로 삭제. 이벤트 리스너는 `onclick` 속성 방식과 `addEventListener()` 방식을 비교.
- **OpenChallenge**: `Math.random()`으로 세 칸의 숫자를 뽑아 모두 같으면 성공하는 갬블링 게임 제작.

### 이벤트 처리 (11/04)

- **포커스 이벤트**: 브라우저 창이 포커스를 잃거나(`onblur`) 얻을 때(`onfocus`) 배경색 변경.
- **폼 이벤트**: 라디오 버튼 `onchange`로 선택한 과일 이미지 출력, 텍스트 입력창에서 `onkeydown`의 `e.key == "Enter"`로 수식 계산.
- **마우스 이벤트**: `onmousemove`로 이미지가 마우스를 따라다니는 커서, `ondblclick`으로 랜덤 배경색, `onwheel`로 이미지 확대/축소.
- **이벤트 객체의 `target`**: `onmouseover` / `onmouseout`에서 `e.target.tagName`으로 `<span>`에만 밑줄 적용, 클릭한 `<li>`만 글자 크게 만들기, 항목 위에 마우스를 올리면 설명 표시.
- **페이지 로드**: `<body onload="init()">`로 문서가 로드된 뒤 이벤트 리스너 등록.
- **종합 실습**: 버튼 이벤트를 연결한 계산기(Back / CE / C / `=`)와, 10×10 표에서 클릭한 칸으로 이미지가 이동하는 OpenChallenge 제작.

### BOM과 타이머 (11/11)

- **window 객체**: `window.open(url, 이름, 옵션)`으로 `width` / `height` / `left` / `top`을 지정해 새 창을 열고, 새 창의 `document.write()`·`document.title`·`style.backgroundColor`를 제어. 창 이름을 같게 주면 하나의 창을 공유(`select`의 `onchange`로 사이트 접속).
- **navigator 객체**: `navigator.userAgent`를 소문자로 바꾼 뒤 `indexOf("chrome")`으로 Chrome 브라우저 여부를 감별.
- **screen 객체**: `screen.width` / `screen.height`가 1280×1024보다 작으면 `alert()`으로 해상도 경고 출력.
- **타이머**: `setTimeout()`을 재귀 호출해 1초마다 갱신되는 시계를, `setInterval()` / `clearInterval()`로 클릭하면 멈췄다 다시 가는 시계를 구현.
- **산수 퀴즈**: `Math.random()`과 `switch`로 사칙연산 문제를 자동 출제하고, `eval()`과 `Math.floor()`로 채점(오답은 `line-through`). 10초 뒤 자동 채점되는 타이머 버전(`08.html`)도 제작.
- **OpenChallenge**: 30개의 `*` 눈송이를 `Math.random()` 속도와 `Math.cos()` 흔들림으로 떨어뜨리는 눈 내리는 애니메이션 제작.

## 🙋 자기소개 페이지 (IntroducePage)

HTML/CSS 실습 내용을 활용해 만든 자기소개 페이지입니다.

- `<table>`로 기본 정보 구성, `<section>` 단위로 About / Contact / Skills / Projects 영역 분리
- 외부 CSS(`css3.css`)와 Pretendard 웹폰트 적용, 카드형 섹션 디자인
- `mailto:` / `tel:` 링크, `<iframe>`으로 유튜브 영상 삽입, `<video>`로 부산 영상(`busan.mp4`) 삽입

## 🛡️ 포트폴리오 사이트 (Portfolio)

정보보안 진로(최종 목표: KISA)를 주제로 만든 한 페이지짜리 포트폴리오 사이트입니다. 외부 파일 없이 `index.html` 하나에 HTML/CSS/JS가 모두 들어 있습니다.

- **구성**: About(학력 포함) · Why Security(국내 주요 보안 사고) · Award(2025 K-HiTech 장려상, AZAS) · Projects · Skills · Journey · Contact
- **CSS**: CSS 변수, `grid` 레이아웃, `@keyframes` 애니메이션(오로라 배경, 흐르는 기술 띠, 그라디언트 텍스트), `@media` 반응형, `prefers-reduced-motion` 대응
- **JavaScript**: `IntersectionObserver`로 스크롤 등장 효과와 숫자 카운트업, 스크롤 위치에 따라 단어가 밝아지는 문장과 차오르는 타임라인, 현재 섹션을 따라가는 내비게이션 하이라이트, 터미널 타이핑 효과, `navigator.clipboard`로 이메일 복사

## 🏠 기말 프로젝트: 자취메이트 (Jachimate)

같은 학교 자취생끼리 생필품을 함께 사고, 남는 물건을 근처 학생에게 나눔할 수 있게 연결하는 웹사이트입니다. Claude(AI)와 함께 기획부터 배포까지 진행했습니다.

- **배포 주소**: https://jachimate.netlify.app
- **발표자료**: [`Jachimate/presentation/jachimate_presentation.pdf`](Jachimate/presentation/jachimate_presentation.pdf)
- **핵심 기능**
  - **학교 메일 인증**: Firebase Authentication으로 대학 메일(`ac.kr`)에 인증 메일을 보내고, 인증을 마친 학생만 참여
  - **공동구매 모집**: 품목·인원·마감일 입력 시 1인당 금액 자동 계산, 자주 사는 품목 템플릿, 참여 현황 실시간 반영(Cloud Firestore)
  - **내 주변 나눔 지도**: 브라우저 Geolocation으로 현재 위치를 받아 반경 1km(500m·2km·전체 선택) 안의 나눔을 카카오맵에 표시, 지도를 눌러 바로 나눔 등록
  - **개인정보 보호**: 현재 위치로 올린 나눔은 집이 드러나지 않게 40m 안쪽에서 위치를 살짝 옮겨 저장
- **보안**: Firestore 보안 규칙(`firestore.rules`)으로 메일 인증을 마친 학교 계정만 읽기·쓰기, 본인 글만 삭제, 모집 인원 초과 참여 차단
- **마케팅 전략**: SWOT 분석 후 SO·WO·ST 전략(학교 메일 인증, 품목 템플릿, 위치 흩뜨리기)을 실제 기능으로 구현
- **기술 스택**: HTML/CSS/JavaScript, Firebase(Authentication·Cloud Firestore), 카카오맵 JavaScript API, Netlify

> 설정 방법(Firebase·카카오 키 발급, 보안 규칙, 배포)은 `Jachimate/README.md`에 정리되어 있습니다.

## ▶️ 실행 방법

각 폴더 안의 `.html` 파일을 다운로드한 뒤, 웹 브라우저(Chrome, Edge 등)로 드래그하거나 더블클릭하여 열면 결과물을 확인할 수 있습니다.

```bash
git clone https://github.com/KimKyul0904/WebProgramming.git
cd WebProgramming
```

> `Portfolio`는 `Portfolio/index.html`을 바로 열면 됩니다.
>
> `Jachimate`는 로그인·지도·위치 기능 때문에 파일을 더블클릭하면 동작하지 않습니다. 배포 주소(https://jachimate.netlify.app)로 접속하거나, 폴더에서 `python3 -m http.server 8000`을 실행한 뒤 `http://localhost:8000`으로 열어 주세요.
>
> `IntroducePage`는 `index.html`을 열면 되고, `css3.css`와 같은 폴더에 있어야 스타일이 적용됩니다.
>
> `1111 WebProgramming`의 `window.open()` 실습(01~03번)은 브라우저의 팝업 차단 설정에 따라 새 창이 열리지 않을 수 있으니, 이 경우 팝업을 허용해 주세요.
>
> 일부 실습 파일(`1028 WebProgramming`, `1104 WebProgramming`, `1111 WebProgramming` 등)은 `../../media/` 경로의 이미지를 참조하지만 해당 폴더는 저장소에 포함되어 있지 않아, 이미지가 보이지 않을 수 있습니다.

---

📌 매주 실습이 끝날 때마다 폴더와 이 README가 업데이트됩니다.
