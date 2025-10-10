# 🏪 T1Shop Develop

> **T1Shop 디벨롭**은 기존의 T1Shop 웹사이트를 참고하여  
> **프론트엔드와 백엔드 전반을 학습하기 위해 제작한 개인 포트폴리오 프로젝트**입니다.

---

## 🧩 개발 목표
> 실제 쇼핑몰의 구조를 분석하며 프론트엔드와 백엔드의 연동 과정을 학습
> 기초적인 전자상거래 웹사이트의 동작 이해
> 웹사이트 클론 코딩을 통한 디자인 및 코드 설계 능력 향상

---

## 📚 프로젝트 개요

이 프로젝트는 실제 상용 쇼핑몰 사이트인 **T1Shop**의 구조와 디자인을 참고하여  
HTML, CSS, JavaScript를 활용해 **사이트 전반의 동작 원리**를 학습하고  
향후 백엔드 및 데이터베이스(DBSQL)를 연동하여 기능을 확장하기 위한 목적으로 진행되었습니다.

---

## 🛠️ 기술 스택

| 구분 | 사용 기술 |
|------|------------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | (예정) Node.js 또는 Express.js |
| Database | (예정) DBSQL |
| Version Control | Git, GitHub |

---

## ✨ 주요 기능

- 기존 **T1Shop 웹사이트 레이아웃 및 디자인 재현**  
- HTML, CSS, JavaScript를 활용한 기본 UI/UX 구현  
- 반응형 디자인 일부 적용  
- 현재는 **프론트엔드 중심 구조**, 향후 백엔드 연동 예정  

---

## 🔮 추후 추가 예정 기능

- 🧾 **카카오 결제 API 연동**  
- 🗄️ DBSQL 기반 상품 / 사용자 데이터 관리 기능 추가  
- 🧑‍💼 관리자 페이지 기능 개발  
- 📱 완전한 반응형 디자인 개선  

---

## 📁 프로젝트 구조

```text
T1Shop/
├─ public/                     # 배포 정적 리소스(파비콘, 공개 이미지 등)
│  ├─ favicon.ico
│  └─ robots.txt
├─ src/                        # 실제 소스
│  ├─ index.html               # 진입 HTML
│  ├─ assets/                  # 개발용 정적 리소스
│  │  ├─ images/
│  │  ├─ fonts/
│  │  └─ icons/
│  ├─ styles/                  # 스타일
│  │  ├─ base/                 # reset, 변수, 공통 유틸
│  │  │  ├─ _reset.css
│  │  │  └─ _variables.css
│  │  ├─ components/           # 컴포넌트별 스타일
│  │  │  └─ product-card.css
│  │  ├─ pages/                # 페이지별 스타일
│  │  │  ├─ home.css
│  │  │  └─ product.css
│  │  └─ main.css              # 엔트리(@import 모음)
│  ├─ scripts/
│  │  ├─ core/                 # 공용 모듈(라우팅/HTTP/스토리지)
│  │  │  ├─ router.js
│  │  │  ├─ http.js
│  │  │  └─ storage.js
│  │  ├─ components/           # UI 컴포넌트
│  │  │  └─ ProductCard.js
│  │  ├─ pages/                # 페이지 스크립트
│  │  │  ├─ HomePage.js
│  │  │  └─ ProductPage.js
│  │  └─ main.js               # 진입 스크립트(이벤트 바인딩)
│  ├─ templates/               # (선택) 헤더/푸터 HTML 조각
│  │  ├─ header.html
│  │  └─ footer.html
│  └─ data/                    # (임시) 목업 JSON, 추후 API 대체
│     └─ products.json
├─ server/                     # (추가 예정) 백엔드(Express)
│  ├─ app.js                   # 서버 진입점
│  ├─ routes/
│  │  └─ products.route.js
│  ├─ controllers/
│  │  └─ products.controller.js
│  ├─ models/                  # DB 모델(SQL/DAO)
│  │  └─ products.model.js
│  ├─ services/
│  │  └─ payment.service.js    # (추후) 카카오 결제 연동
│  ├─ middlewares/             # 에러핸들링/인증 등
│  └─ config/
│     ├─ db.js                 # DB 연결
│     └─ env.js                # 환경변수 로딩
├─ .env.example                # 환경변수 샘플(노출 X)
├─ package.json
├─ README.md
└─ vite.config.js              # (선택) Vite 사용 시
```
## 📦 설치 및 실행 방법

```bash
# 1. 리포지토리 클론
git clone https://github.com/yujin156/Portfoilo_T1Shop.git

# 2. 프로젝트 폴더로 이동
cd Portfoilo_T1Shop

# 3. 브라우저로 index.html 실행
# (또는 간단한 로컬 서버 실행)
npx serve
```
## ⚖️ 라이선스
이 프로젝트는 학습 및 포트폴리오 목적의 개인 프로젝트입니다.
상업적 사용을 금합니다.
