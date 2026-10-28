# 🌐 Web Programming

웹 프로그래밍 과목 실습 및 과제 저장소입니다. HTML/CSS로 시작해 JavaScript까지, 매주 학습한 내용을 `Problem`(기본 문제풀이)과 `OpenChallenge`(자유 과제) 형태로 정리하고 있습니다.

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
├── IntroducePage/      # 자기소개 페이지 (index.html, css3.css, busan.mp4)
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
| - | `IntroducePage` | 지금까지 배운 HTML/CSS를 종합한 자기소개 페이지 |

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

## 🙋 자기소개 페이지 (IntroducePage)

HTML/CSS 실습 내용을 활용해 만든 자기소개 페이지입니다.

- `<table>`로 기본 정보 구성, `<section>` 단위로 About / Contact / Skills / Projects 영역 분리
- 외부 CSS(`css3.css`)와 Pretendard 웹폰트 적용, 카드형 섹션 디자인
- `mailto:` / `tel:` 링크, `<iframe>`으로 유튜브 영상 삽입, `<video>`로 부산 영상(`busan.mp4`) 삽입

## ▶️ 실행 방법

각 폴더 안의 `.html` 파일을 다운로드한 뒤, 웹 브라우저(Chrome, Edge 등)로 드래그하거나 더블클릭하여 열면 결과물을 확인할 수 있습니다.

```bash
git clone https://github.com/KimKyul0904/WebProgramming.git
cd WebProgramming
```

> `IntroducePage`는 `index.html`을 열면 되고, `css3.css`와 같은 폴더에 있어야 스타일이 적용됩니다.

---

📌 매주 실습이 끝날 때마다 폴더와 이 README가 업데이트됩니다.
