<h1 align="center">안녕하세요! 디자인과 사용자 경험을 함께 고민하는 프론트엔드 개발자 이서림입니다 👋</h1>

<p>
안녕하세요! 디자인과 사용자 경험을 함께 고민하는 프론트엔드 개발자입니다.
React 기반의 UI 구현에 강점을 가지고 있으며, 디자인부터 개발까지 혼자서 전체 흐름을 설계하고 구현하는 작업을 좋아합니다.

현재는 주로 React, Expo, Next.js, TypeScript, Tailwind를 활용해
사용자 친화적인 인터페이스와 매끄러운 사용자 여정을 만드는 데 집중하고 있어요.
스토리북을 활용한 컴포넌트 문서화와 디자인 시스템 구축에도 큰 관심을 갖고 꾸준히 공부하고 있습니다.

UI/UX의 일관성과 세밀한 설계가 좋은 제품을 만든다고 믿기 때문에,
프로젝트마다 Figma로 먼저 구조를 정리한 뒤 개발을 진행합니다.
또한 협업 과정에서 혼선을 줄이기 위해 명확한 문서화와 소통 중심의 협업 방식을 지향하고 있습니다.

현재는 개인 프로젝트와 Team Bluepot 활동을 통해 다양한 서비스를 직접 기획하고 개발하며 경험을 넓혀가고 있습니다.
</p>

---

### 🛠 Tech Stack  

| Category | Tech |
| --- | --- |
| 🧩 Frameworks | <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/> <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white"/> |
| 🧰 Tools & Libraries | <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black"/> <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white"/> <img src="https://img.shields.io/badge/Zustand-000000?style=flat-square"/> <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white"/> <img src="https://img.shields.io/badge/Moti-000000?style=flat-square"/> |
| 💻 Languages | <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> |
| 🎨 Design & UI | <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/> |

---

# 🙋‍♂️ Personal Projects

## 🎂 <a href="https://github.com/Leeseoleem/my-little-birthday-party" target="_blank">나의 작은 생일 파티</a>

> **인터랙티브 생일 메시지 웹 서비스** – React + Supabase  
> 메시지를 보내는 대신, 하나의 경험을 선물하는 생일 카드 플랫폼

**🔧 Tech Stack**  
React 18 · TypeScript · Vite · TanStack Router · Tailwind CSS v4 · Framer Motion · Supabase (Postgres + RLS + Anonymous Auth) · Vercel · Storybook · Vitest · Playwright

<details>
  <summary><b>자세히 보기</b></summary>

**🧩 My Role**
- 기획 → UX 설계 → UI 디자인 → 프론트엔드 개발 전체 단독 진행
- Supabase DB 스키마 설계 및 RLS 정책 구성
- PIN 기반 1회성 이벤트 로직 설계 (`isOpened` 상태 제어)
- 제작자 / 수신자 분리된 라우팅 구조 설계
- 케이크 인터랙션, 초 끄기 이벤트, 파티 연출 애니메이션 구현
- RPC 기반 PIN 검증 및 보안 접근 흐름 설계
- Storybook 기반 컴포넌트 단위 개발 및 문서화

**✨ Key Features**
- 단계별 제작 플로우 (이름·생일 입력 → 케이크 제작 → 캐릭터 선택 → 편지 작성 → 링크 생성)
- PIN(MMDD) 기반 접근 제어 및 1회성 이벤트 설계
- 초 끄기 인터랙션 (마우스 기반 / 마이크 확장 설계)
- 케이크·캐릭터·편지 클릭 상호작용 구조
- 재접속 시 파티 페이지 직행 로직 (`isOpened` 서버 제어)
- Supabase Anonymous Auth + RLS 기반 최소 권한 데이터 접근

🔗 [GitHub Repo](https://github.com/Leeseoleem/my-little-birthday-party) | [Design Document](...) | [Live Demo](https://my-little-birthday-party.vercel.app/)

</details>

---

## 📊 <a href="..." target="_blank">QuizLab</a>  *(Paused / Archived)*

> **학습 퀴즈 앱** – Expo + Firebase  
> 문제 제작 · 풀이 · 통계까지 가능한 학습용 앱

**🔧 Tech Stack**  
Expo · TypeScript · Nativewind(Tailwind) · Firebase · (검색/통계 관련 로직 설계)

<details>
  <summary><b>자세히 보기</b></summary>

**📌 Status: 중단(보류)**
- **중단 사유:** Expo SDK/버전 업데이트 과정에서 **의존성 충돌 및 Firebase 연동 오류**가 반복적으로 발생하여, 안정적인 개발 환경을 재정비하기 위해 보류했습니다.
- **추후 계획:** 기능 방향을 확장하여 **웹(React 또는 Next.js)** 기반으로 재구성할 가능성이 있습니다. 특히 **AI가 문제를 생성/추천**하는 기능을 중심으로 재설계를 고려 중입니다.

**🧩 My Role**
- 디자인 → 개발 전체 단일 개발
- Firestore 스키마 설계
- 문제 풀이 로직, 타이머 모드, 통계 기능 직접 설계
- Meilisearch 기반 검색 기능 구축
- Lottie 기반 인터랙션 UI 개발

**✨ Key Features**
- 커스텀 문제집 생성
- 시간 제한 모드 / 자유 모드
- 문제 통계 및 오답 노트
- 폴더 공유 기능 준비 중

🔗 [GitHub Repo](...) | [Figma Design](...)

</details>

---

## 🧑‍💻 <a href="https://github.com/Leeseoleem/leeseoleem-portfolio" target="_blank">Personal Portfolio</a>

> **개인 포트폴리오 웹 사이트** – React + TypeScript + Tailwind 기반  
> 실제 배포 완료(Resume/Projects/Contact 정리)

**🔧 Tech Stack**  
React · TypeScript · Tailwind CSS · GitHub Pages

<details>
  <summary><b>자세히 보기</b></summary>

**🧩 My Role**
- 전체 정보 구조(About · Projects · Skills · Contact) 설계
- 반응형 레이아웃 및 컴포넌트 기반 UI 구현
- 색상·타이포·여백을 통합한 개인용 디자인 시스템 정리
- GitHub Pages를 활용한 CI/CD 및 배포

🔗 [GitHub Repo](https://github.com/Leeseoleem/leeseoleem-portfolio) · 🌐 [Live Site](https://leeseoleem.github.io/leeseoleem-portfolio/)

</details>

---

# 👥 Team Projects

## 🩵 BluePot

### 🧭 <a href="https://github.com/T-BluePot/barogagi-front" target="_blank">바로가기 | Barogagi</a>

> **AI 기반 여행 일정 추천 웹 앱** – React 기반  
> Team Bluepot 프로젝트

**🔧 Tech Stack (Front-end 담당 영역)**  
React · TypeScript · Tailwind · Vite · Storybook · TanStack Query

<details>
  <summary><b>자세히 보기</b></summary>

**✨ Key Features**
- 사용자의 여행 스타일(테마·지역·분위기)을 기반으로 AI 일정 추천
- 일정 생성 후 일자별 구성 Drag & Drop 편집 UI
- 태그 기반 필터링 및 장소 검색 기능
- 서버 연동 기반 데이터 관리 구조 설계

**🧩 My Role**
- 전체 UI/UX 플로우 및 화면 구조 설계
- 메인 페이지 및 **일정 생성 핵심 기능 구현**
- 전화번호 기반 일반 회원가입 로직 구현 (OAuth와 별도 구조)
- 회원가입/인증 흐름에 따른 상태 설계 및 서버 API 연동
- TanStack Query를 활용한 서버 상태 관리 및 비동기 데이터 처리 구조 설계
- 일정 생성/수정 관련 API 연동 및 데이터 흐름 설계
- 컴포넌트 단위 설계 및 재사용 가능한 레이아웃 구성

🔗 [GitHub Repo](https://github.com/T-BluePot/barogagi-front) · 🚀 Coming Soon(배포 예정)

</details>

---

### 🧩 <a href="https://github.com/T-BluePot/portfolio" target="_blank">Team Bluepot Portfolio</a>

> **Team Bluepot 소개 및 프로젝트 모음 페이지** – 웹 포트폴리오 사이트  
> 팀 프로젝트 | 팀 전용 포트폴리오 제작

**🔧 Tech Stack**  
React · TypeScript · Tailwind CSS

<details>
  <summary><b>자세히 보기</b></summary>

**🧩 My Role**
- 팀 아이덴티티를 반영한 레이아웃 및 UI 설계
- 프로젝트 카드·타임라인 등 소개 컴포넌트 구현
- 팀 프로젝트 구조와 역할을 정리한 콘텐츠 구성

🔗 [GitHub Repo](https://github.com/T-BluePot/portfolio)

</details>

---

### 💬 <a href="https://github.com/T-BluePot/GlassBottle" target="_blank">Glassbottle</a>

> **익명 소통 기반 커뮤니케이션 앱** – React Native  
> Team Bluepot 프로젝트

**🔧 Tech Stack**  
React Native · Firebase

<details>
  <summary><b>자세히 보기</b></summary>

**✨ Key Features**
- 이름 없이 자유롭게 소통할 수 있는 **익명 기반 메시지 시스템**
- 사용자 간 부드러운 흐름을 위한 **모달·전환 애니메이션 중심 UI**

**🧩 My Role**
- UI/UX 컴포넌트 구현
- 모달/상호작용 UI 개발
- Firebase 인증 및 데이터 연동

🔗 [GitHub Repo](https://github.com/T-BluePot/GlassBottle)

</details>

---

## 🎓 Graduation Project

### 🌱 <a href="https://github.com/VRRS-Project-Team-GitPage" target="_blank">채식 어디</a>

> **채식 음식 추천 앱** – Expo 기반  
> 팀 프로젝트 | 팀장 및 프론트엔드 개발

**🔧 Tech Stack**  
front | Expo · JavaScript · StyleSheet · Figma  
back | Spring Boot · Clover OCR

<details>
  <summary><b>자세히 보기</b></summary>

**✨ Key Features**
- 채식 유형(락토, 오보, 비건 등) 기준 필터 기능
- 원재료명 사진 분석을 통한 섭취 가능 여부 판별
- 랜덤 음식 추천 기능

**🧩 My Role**
- UI/UX 전반 설계 및 전체 화면 구현
- Firebase 연동 및 데이터 구조 설계
- 팀 일정·작업 분배 총괄 (팀장 역할)
- 공통 컴포넌트 구조 설계

🔗 [GitHub Repo](https://github.com/VRRS-Project-Team-GitPage) · [Figma Design](https://www.figma.com/proto/Iw4NxpHMFiyFo3bWT6CF3W/%EC%BA%A1%EC%8A%A4%ED%86%A4-%EB%94%94%EC%9E%90%EC%9D%B8-UI-%EC%B5%9C%EC%A2%85?page-id=2%3A647&node-id=2-1016&viewport=-1006%2C617%2C0.56&t=QrVBhkHL52KxprZd-1&scaling=contain&content-scaling=fixed) · [Youtube](https://youtu.be/PUEc9VYo3kM?si=KGFWudiny2r6Xl3i)

</details>

---

### 📊 GitHub Stats  

[![Seorim's GitHub stats](https://github-readme-stats.vercel.app/api?username=leeseoleem&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)

---

### 📬 Contact  

📧 Email: leeseorim0029@email.com  
📝 Blog: [Velog](https://velog.io/@leeseoleem1014)  
