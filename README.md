<div align="center">

# 프론트엔드 개발자 이서림

**화면의 의도를 코드 구조까지 연결해 설계합니다.**

수정이나 기능 확장에도 흐름이 끊기지 않는 구조를 고민하며,
모든 프로젝트에서 설계부터 구현까지 직접 맡아왔습니다.

<a href="https://velog.io/@leeseoleem1014"><img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/서림-이-84944a355/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:leeseorim0029@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<br/>

## Tech Stack

| 분류 | 기술 |
|---|---|
| **Language** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Frontend** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black) ![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white) |
| **UI** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![NativeWind](https://img.shields.io/badge/NativeWind-38BDF8?style=flat-square&logo=tailwindcss&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) ![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white) |
| **State / Routing** | ![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square&logo=react&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![TanStack Router](https://img.shields.io/badge/TanStack_Router-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white) |
| **Backend / Infra** | ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) |
| **Design / Collab** | ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) |

<br/>

## Featured Projects

### 핏플 (fitpl)

> **키워드 선택만으로 AI가 일정을 자동 구성하는 스마트 일정 플래너 앱**
>
> 팀 프로젝트 · Google Play 출시 · [스토어 바로가기](https://play.google.com/store/apps/details?id=com.bluehp.fitpl)

- 회원가입·일정 생성 페이지 담당. Zustand persist + sessionStorage 조합으로 4단계 일정 생성 플로우 이탈 시에도 작성하던 단계부터 이어가는 보존 범위 설계
- 헤더 타입 5종 discriminated union config 설계로 Layout 컴포넌트에 렌더링 책임 이관. 헤더 누락 0건, config 한 곳 수정으로 전 페이지 동기화
- Keystore 생성부터 Gradle signing config 비밀번호 노출 방지까지 Android Release 빌드 파이프라인 단독 구축

`React` `TypeScript` `Vite` `Tailwind CSS` `Zustand` `TanStack Query` `Storybook`

<br/>

### 가라챠토

> **TJ 노래방 J-POP 차트의 자동 수집 파이프라인부터 AI 해설·YouTube 연동까지 단독 구현한 풀스택 웹 서비스**
>
> 개인 프로젝트 · 배포 운영 중 · 앱인토스(Apps in Toss) 전용 마이그레이션 진행 중

- 공식 API가 없는 TJ 차트의 CSRF 토큰·세션 인증 구조를 역분석해 TOP 100 자동 수집 크롤러 단독 구현
- 3계층 DB 스키마 설계로 곡당 AI 번역 호출을 1회로 제한, YouTube API 쿼터 초과 시 pending 재시도 큐로 처리 누락 0건·API 비용 0원 유지
- AI 챗봇 의도 분류 설계로 고빈도 단순 검색은 LLM 호출 없이 즉시 응답

`Next.js` `TypeScript` `Tailwind CSS` `Supabase` `Gemini API` `Vercel`

<br/>

### 우리두 (Uridoo)

> **"오늘 뭐 할래?"에서 멈추는 대화를 겨냥한, 결정과 기록을 돕는 도구형 모바일 앱**
>
> 2인 팀 프로젝트 · 프론트엔드·UX/UI 전담 · 개발 중

- 챌린지 4종·마스코트 성장·회고 달력으로 이어지는 5탭 IA를 UX 설계부터 프로토타입, 프론트엔드 구현까지 전담
- 디자인 토큰 기반 테마 시스템(포인트 4색 × 3단계, 하드코딩 금지) 설계
- EAS Build 기반 iOS·Android 크로스 플랫폼 빌드 환경 구성

`React Native (Expo)` `TypeScript` `Expo Router` `NativeWind` `Zustand` `moti` `clsx`

<br/>

## More Projects

> **생일 카드 웹 서비스** : 회원가입 없이 초대 링크만으로 수신자 전용 열람을 구현한 인터랙티브 생일 카드 웹 (개인 · 배포 운영 중)
>
> **채식어디** : 원재료명 OCR 판독으로 채식 타입별 섭취 가능 여부를 안내하는 모바일 앱 (4인 팀 · Team Lead)

<br/>

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Leeseoleem&show_icons=true&theme=default&hide_border=true" alt="Seorim's GitHub stats"/>

</div>
