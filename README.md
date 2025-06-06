# 📋 Taskify
> **"Taskify는 일정 관리와 공유 기능을 제공하는 웹 애플리케이션입니다."**

---

## 🧑‍💻 팀원 소개 & 역할 (Team Members & Roles)

<table>
  <thead>
    <tr>
      <th>이름</th>
      <th>프로필</th>
      <th>담당 주요 기능</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/jihoon135">@곽지훈</a></td>
      <td><img src="https://avatars.githubusercontent.com/u/100752796?v=4" width="100"></td>
      <td>
        • 공통 컴포넌트 (버튼, 페이지네이션)<br/>
        • 나의 대시보드 초기 UI 및 수정 페이지<br/>
        • API 연결, 스켈레톤 UI, 반응형<br/>
        • 대시보드 생성 모달<br/>
        • 무한 스크롤<br/>
        • toast context API 구현
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/ramong26">@김수연</a></td>
      <td><img src="https://avatars.githubusercontent.com/u/192767726?v=4" width="100"></td>
      <td>
        • 로그인/회원가입<br/>
        • 토큰 처리<br/>
        • 초기 레이아웃 UI<br/>
        • 카드 무한 스크롤<br/>
        • 나의 대시보드 API 연동
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/dkozowlk">@김태욱</a></td>
      <td><img src="https://avatars.githubusercontent.com/u/56295839?v=4" width="100"></td>
      <td>
        • 공통 인풋 컴포넌트<br/>
        • 랜딩페이지<br/>
        • 카드 모달 및 스켈레톤 UI<br/>
        • 초대받은 대시보드 UI
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/huiseong29">@김희성</a>👑</td>
      <td><img src="https://avatars.githubusercontent.com/u/175691313?v=4" width="100"></td>
      <td>
        • API 요청 모듈 구성 (fetch + error handling)<br/>
        • Dashboard / Column / Card UI 및 CRUD 연동<br/>
        • 카드 상세 및 생성/수정 모달 UI 및 API 연동<br/>
        • Sidebar API 연동 및 페이지네이션<br/>
        • 드래그 앤 드롭
      </td>
    </tr>
    <tr>
      <td><a href="https://github.com/Parkchanyoung0710">@박찬영</a></td>
      <td><img src="https://avatars.githubusercontent.com/u/120624055?v=4" width="100"></td>
      <td>
        • 마이페이지 (반응형, 스켈레톤 UI)<br/>
        • 사이드바 UI 및 공통 모달/토스트<br/>
        • 드롭다운, 태그, 공통 CSS<br/>
        • 나의 대시보드 반응형
      </td>
    </tr>
  </tbody>
</table>

## 🔗 배포 주소 (Deployment URL)
- [Taskify 바로가기](https://taskify-git-develop-codeit-part3.vercel.app/)

## 📅 프로젝트 기간 (Project Timeline)
2025년 4월 22일 ~ 2025년 5월 12일

---

## ✨ 코드 컨벤션 (Code Convention)

### 📁 폴더/파일 네이밍 규칙 (Folder & File Naming Convention)

| **대상** | **규칙** | **예시** |
|---|---|---|
| 폴더명 | 케밥케이스 (kebab-case) | `components/`, `user-profile/` |
| 컴포넌트 파일명 | 파스칼케이스 (PascalCase) | `UserProfile.jsx` |
| 스타일 파일명 | 케밥케이스 + `.styles.js` | `user-profile.styles.js` |
| 이미지/아이콘 파일명 | 케밥케이스 | `logo-icon.png`, `profile-default.png` |
| 함수명/변수명 | 카멜케이스 (camelCase) | `fetchUserData`, `userList` |
| 환경변수 | 대문자+스네이크케이스 | `REACT_APP_API_URL` |
| css 파일명 | 카멜케이스 (camelCase) | `dashboardList.module.css` |
---

### 🌿 브랜치 네이밍 컨벤션 (Branch Naming Convention)

| 역할 | 네이밍 | 예시 |
|---|---|---|
| 메인 브랜치(배포용) | `main` | `main/` |
| 개발 통합 브랜치 | `develop` | `develop/` |
| 기능 개발 브랜치 | `feature/기능명` | `feature/dashboard-modal` |
| 긴급 수정 브랜치 | `hotfix/이슈명` | `hotfix/login-error` |
| 릴리즈 준비 브랜치 | `release/버전명` | `release/v1.0.0` |
| 코드 스타일 수정 | `style/해당브랜치` | `style/login` |
| 잡무나 유지보수 | `chore/라이브러리 업데이트` | `chore/update` |  
---

## 🛠️ 사용 기술 스택 (Tech Stack)

| 역할 | 사용 기술 |
|----------|-----------|
| **Language** | ![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) |
| **Framework / UI** | ![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white) |
| **State Management** | ![Zustand](https://img.shields.io/badge/Zustand-000000?style=flat&logo=Zustand&logoColor=white&labelColor=orange) |
| **Styling** | ![CSS Modules](https://img.shields.io/badge/CSS%20Modules-000000?style=flat&logo=css3&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white) |
| **Drag & Drop** | ![DnD](https://img.shields.io/badge/Drag_&_Drop_UI-6E40C9?style=flat&logo=framer&logoColor=white) |
| **Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) |
| **Deployment** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=Vercel&logoColor=white")

## 🧩 사용된 주요 라이브러리 소개

| 라이브러리 | 설명 |
|-----------|------|
| **[clsx](https://www.npmjs.com/package/clsx)** | 조건부로 클래스를 병합할 수 있는 간결하고 빠른 유틸리티 함수 |
| **[date-fns](https://date-fns.org/)** | 날짜 포맷, 덧셈/뺄셈, 비교 등의 기능을 모듈화하여 제공하는 최신 JavaScript 날짜 유틸리티 라이브러리 |
| **[React Date Picker](https://reactdatepicker.com/)** | 직관적이고 커스터마이징이 쉬운 날짜 선택 UI 컴포넌트 |
| **[Framer Motion](https://www.framer.com/motion/)** | 생산성과 퍼포먼스를 모두 잡은 React용 애니메이션 라이브러리 |
| **[Tailwind CSS](https://tailwindcss.com/)** | 유틸리티 클래스 기반으로 빠르게 UI를 구성할 수 있게 도와주는 CSS 프레임워크 |
| **[Zustand](https://github.com/pmndrs/zustand)** | 매우 간단하고 가벼운 상태 관리 라이브러리|

---

## 📂 폴더 구조 (Folder Structure)

```bash
src/
├── api/                              🌐 API 요청 모듈
│
├── components/                       🧩 UI 컴포넌트 모음
│   ├── common/                       🛠️ 공통 재사용 컴포넌트
│   │   ├── animatedmodalcontainer/
│   │   ├── animatedSection/
│   │   ├── badge/
│   │   ├── commonbutton/
│   │   ├── commoninput/
│   │   └── tag/
│   │
│   └── domain/                       📚 도메인 중심 컴포넌트 (비즈니스 로직 포함)
│       ├── colorpin/                🎨 색상 고정 관련 UI
│       ├── dashboard/               📊 대시보드 관련 UI
│       ├── modals/                  💬 모달 컴포넌트들
│       │   ├── basemodal/
│       │   ├── dashboardCreateModal/
│       │   ├── taskcardcreateModal/
│       │   ├── taskcardeditModal/
│       │   └── taskcardmodal/
│       └── mydashboard/             🗂️ 나의 대시보드 관련 기능
│           ├── dashboardinvitedlist/
│           ├── dashboardlist/
│           ├── editmydashboardattribute/
│           ├── editmydashboardinvitelog/
│           └── editmydashboardmember/
│
├── dropdown/                         🔽 공통 드롭다운 컴포넌트
├── featurecard/                      📇 특성 카드 컴포넌트
│
├── layout/                           🧱 레이아웃 구성 요소
│   ├── footerbar/                    📌 푸터 바
│   ├── gnb/                          🧭 글로벌 네비게이션 바
│   ├── sidebar/                      📚 사이드바
│   ├── layout.module.css             🎨 레이아웃 스타일
│   └── layout.tsx                    📐 레이아웃 컴포넌트
│
├── skeleton/                         🦴 스켈레톤 로딩 컴포넌트
├── toast/                            🍞 토스트 알림 컴포넌트
│
├── hooks/                            🪝 커스텀 훅 모음
│   ├── useColorPicker.ts             🎨 색상 선택 훅
│   ├── useFormSignup.ts              🧾 회원가입 폼 훅
│   └── useIsMobile.ts                📱 반응형 대응 훅
│
├── pages/                            📄 라우팅 페이지 (Next.js)
│   ├── dashboard/
│   │   └── [id]/                     🧱 대시보드 상세/수정 페이지
│   │       ├── dashboard.module.css
│   │       ├── index.tsx
│   │       └── edit.tsx
│   │
│   ├── 404.tsx                       🚫 에러 페이지
│   ├── _app.tsx                      🏗️ 전체 앱 초기화
│   ├── _document.tsx                 📃 문서 설정
│   ├── index.module.css              🎨 홈 스타일
│   ├── index.tsx                     🏠 메인 랜딩 페이지
│   ├── login.tsx                     🔐 로그인 페이지
│   ├── signup.tsx                    🧑‍💻 회원가입 페이지
│   ├── mydashboard.tsx              📂 나의 대시보드
│   └── mypage.tsx                    🙋‍♂️ 마이페이지
│
├── stores/                           📦 전역 상태 관리 (Zustand 등)
│   ├── auth.ts                       🔐 인증 관련 상태
│   └── dashboardMembers.ts          👥 대시보드 멤버 관련 상태
│
├── styles/                           🎨 글로벌 스타일 및 리셋
│   ├── globals.css                   🌐 전역 스타일
│   └── reset.css                     🧼 브라우저 리셋
│
├── types/                            📐 타입 정의
│   ├── api/                          📦 API 응답/요청 타입
│   └── common/                       📄 공통 타입
│
└── utils/                            🧠 유틸리티 함수 모음
    ├── fetch.ts                      🌍 fetch API 래퍼
    └── handleError.ts                ❗ 에러 핸들링 유틸
```

