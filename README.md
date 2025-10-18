<h1 align="center">🏪 T1Shop 디벨롭 (T1Shop Develop)</h1>

<p align="center">
  <b>기존 <a href="https://shop.t1.gg" target="_blank">T1Shop</a> 사이트를 참고하여, 
  프론트엔드와 백엔드 전반을 학습하기 위해 제작한 포트폴리오 프로젝트입니다.</b><br><br>
  <img src="./img/banner_img/top_banner_pc.jpg" width="600" alt="T1Shop Banner"/>
</p>

---

## 📚 프로젝트 개요

이 프로젝트는 실제 T1 공식몰의 구조와 디자인을 분석하여  
HTML, CSS, JavaScript 중심으로 **웹사이트 프론트엔드 구현**을 연습하고,  
추후 **DB 연동 및 카카오 결제 기능**을 추가하기 위한 학습형 클론 프로젝트입니다.

---

## 🛠️ 기술 스택

| 구분 | 사용 기술 |
|------|------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Backend (예정)** | Node.js, Express |
| **Database (예정)** | DBSQL |
| **Version Control** | Git, GitHub |
| **Deployment** | GitHub Pages |
| **Design** | 직접 구조 설계 및 CSS 커스터마이징 |

---

## ✨ 주요 기능

- 🖼️ **메인 페이지**
  - 비디오 배너 + 섹션별 레이아웃 (COLLECTION / UNIFORM / COMMUNITY / REVIEW)
- 🛍️ **SHOP 페이지**
  - 상단 배너 + 카테고리 메뉴 구현  
  - 상품 리스트 동적 생성 예정
- 🧩 **공통 Header / Footer**
  - 별도 HTML 파일로 구성  
  - JS `fetch()`로 include 방식 전환 예정
- ⚙️ **스타일 시스템**
  - `basic.css` 기반 reset + 공통 규칙  
  - hover 애니메이션과 transition 효과 포함

---

## 🔮 추후 개발 예정

- 💳 카카오페이 결제 API 연동  
- 🗄️ DBSQL 기반 상품/회원 관리  
- 🧑‍💼 관리자 페이지 추가  
- 📱 반응형 UI/UX 개선  
- 🌐 Node.js 백엔드 서버 구축  

---

## 📁 프로젝트 구조

<details>
<summary>📂 펼쳐보기</summary>

  ```text
T1Shop/
├── html/
│   ├── main.html                # 메인 페이지
│   ├── shop.html                # 쇼핑 페이지
│   ├── header.html              # 공통 헤더
│   └── footer.html              # 공통 푸터
├── css/
│   ├── basic.css                # 공통 스타일 / reset
│   ├── header.css               # 일반 헤더
│   ├── mainHeader.css           # 메인 전용 투명 헤더
│   ├── main.css                 # 메인 페이지 섹션 레이아웃
│   ├── collection.css           # COLLECTION 섹션
│   ├── uniform.css              # UNIFORM 섹션 (기존 unlform.css)
│   ├── community.css            # COMMUNITY 섹션 (기존 commuity.css)
│   ├── footer.css               # 푸터
│   └── shop.css                 # SHOP 전용 스타일
├── img/
│   ├── banner_img/              # 배너 이미지
│   ├── products/                # 상품 이미지
│   ├── logo/                    # 로고 파일
│   └── icon/                    # 아이콘 이미지
├── mp4/
│   └── new-pc-video.mp4         # 메인 비디오 배너
└── README.md                    # 프로젝트 문서

```
</details>
---
## 📦 실행 방법
# 1️⃣ 리포지토리 클론
git clone https://github.com/yujin156/Portfoilo_T1Shop.git

# 2️⃣ 프로젝트 폴더로 이동
cd Portfoilo_T1Shop

# 3️⃣ 로컬에서 실행 (VSCode Live Server 또는 serve 사용)
npx serve

브라우저에서 👉 http://localhost:3000
 으로 접속하세요.
---

##🎨 디자인 컨셉
항목	내용
🎨 Color Theme	#ff0000 (T1 레드), #0b0b0b, #181818
🔠 Font	Bold한 Sans-serif 계열
📐 Layout	Flexbox 중심, 반응형 확장 용이
✨ Style Point	hover 트랜지션 / 레이어드 타이틀 디자인
🧩 주요 섹션 스크린샷 (예시 자리)
Collection	Uniform	Community

---
	
👩‍💻 개발자 정보
항목	내용
이름	유진 (Yujin)
GitHub	@yujin156

이메일 / 포트폴리오	(추가 예정)
⚖️ 라이선스

이 프로젝트는 학습 및 포트폴리오 목적의 개인 프로젝트입니다.
상업적 사용을 금합니다.
