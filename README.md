# 🌐 Web Programming

웹 프로그래밍 과목 실습 및 과제 저장소입니다. HTML/CSS를 중심으로 매주 학습한 내용을 `Problem`(기본 문제풀이)과 `OpenChallenge`(자유 과제) 형태로 정리하고 있습니다.

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
└── 0923 WebProgramming/
    ├── Problem/        # num1~num9: box-shadow, text-shadow 등 심화 스타일링
    └── OpenChallenge/  # 설문(survey) 폼 페이지
```

> 폴더명은 실습을 진행한 날짜(MMDD) 기준으로 되어 있습니다.

## 📅 주차별 실습 내용

| 날짜 | 폴더 | 주요 학습 내용 |
| --- | --- | --- |
| 09/02 | `0902 WebProgramming` | HTML 기본 태그, 프로필 페이지 만들기 |
| 09/09 | `0909 WebProgramming` | 이미지·오디오(`<audio>`)·비디오(`<video>`) 삽입, 페이지 레이아웃 |
| 09/16 | `0916 WebProgramming` | CSS 셀렉터(클래스/아이디), 테이블(`table-layout`), `:hover` 가상 클래스 |
| 09/23 | `0923 WebProgramming` | `text-shadow` / `box-shadow`, 설문 폼(`<form>`) 제작 |

## ✨ 핵심 학습 요약

- **미디어 삽입**: `<img>`, `<audio controls>`, `<video>` 태그로 이미지·소리·영상을 페이지에 삽입하는 방법을 익힘.
- **CSS 셀렉터 우선순위**: 태그 → 클래스(`.`) → 아이디(`#`) 순으로 우선순위가 높아지는 것을 실습을 통해 확인.
- **Shadow 계열 속성**: `text-shadow`는 `x y blur color` 3개 값 + 색상, `box-shadow`는 여기에 `spread` 값이 추가로 허용된다는 차이를 학습.
- **가상 클래스**: `:hover`를 이용해 마우스 오버 시 그림자·이미지 등이 동적으로 바뀌는 UI 구현.
- **폼(Form) 요소**: 설문 페이지를 만들며 `<input>`, `<label>` 등 사용자 입력 요소 학습.

## ▶️ 실행 방법

각 폴더 안의 `.html` 파일을 다운로드한 뒤, 웹 브라우저(Chrome, Edge 등)로 드래그하거나 더블클릭하여 열면 결과물을 확인할 수 있습니다.

```bash
git clone https://github.com/KimKyul0904/WebProgramming.git
cd WebProgramming
```

---

📌 매주 실습이 끝날 때마다 폴더와 이 README가 업데이트됩니다.
