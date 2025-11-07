# 이길어때 (HowAboutThisWay) - 교통약자 전용 네비게이션 프론트엔드

## 프로젝트 개요

"이길어때"는 교통약자를 위한 전용 네비게이션 서비스의 프론트엔드 애플리케이션입니다. React와 Vite를 기반으로 구축되어 빠른 개발 환경과 최적화된 빌드를 제공합니다.

## 기술 스택

### 핵심 기술

- **React 19.1.0** - 사용자 인터페이스 구축
- **Vite 6.3.5** - 빠른 개발 서버 및 빌드 도구
- **React Router DOM 7.6.2** - 클라이언트 사이드 라우팅

### 개발 도구

- **ESLint** - 코드 품질 관리
- **TypeScript 타입 정의** - 타입 안정성 지원

## 프로젝트 구조

```
HATW/
├── public/              # 정적 파일
│   └── vite.svg
├── src/
│   ├── api/             # API 통신 모듈
│   │   └── map.js       # 지도 관련 API
│   ├── assets/          # 이미지 및 리소스
│   │   └── react.svg
│   ├── pages/           # 페이지 컴포넌트
│   │   ├── Map.jsx      # 지도 페이지 컴포넌트
│   │   └── Map.css      # 지도 페이지 스타일
│   ├── App.jsx          # 메인 앱 컴포넌트
│   ├── App.css          # 앱 스타일
│   ├── main.jsx         # 애플리케이션 진입점
│   └── index.css        # 전역 스타일
├── index.html           # HTML 템플릿
├── vite.config.js       # Vite 설정
├── eslint.config.js     # ESLint 설정
└── package.json         # 프로젝트 의존성 및 스크립트
```

## 주요 기능 (예정)

### 지도 기능

- 교통약자를 위한 최적 경로 탐색
- 접근성 정보 제공
- 장애물 및 편의시설 표시

### 라우팅

- React Router를 통한 페이지 네비게이션
- 지도 페이지 및 기타 기능 페이지 구성

## 설치 및 실행

### 사전 요구사항

- Node.js (권장: 18.x 이상)
- npm 또는 yarn

### 설치

```bash
npm install
```

### 개발 서버 실행

```bash
npm run dev
```

개발 서버는 기본적으로 `http://localhost:5173`에서 실행됩니다.

### 프로덕션 빌드

```bash
npm run build
```

빌드된 파일은 `dist/` 폴더에 생성됩니다.

### 빌드 미리보기

```bash
npm run preview
```

### 코드 린팅

```bash
npm run lint
```

## 개발 환경 설정

### Vite 설정

현재 기본 React 플러그인만 활성화되어 있습니다. 필요에 따라 추가 플러그인을 설정할 수 있습니다.

### ESLint 설정

React Hooks 및 React Refresh 플러그인이 설정되어 있어 React 개발 모범 사례를 준수합니다.

## 현재 개발 상태

- ✅ 프로젝트 기본 구조 설정 완료
- ✅ React Router DOM 설정 완료
- ✅ 지도 페이지 및 API 구조 준비
- 🔄 지도 기능 구현 중
- 🔄 API 연동 구현 중

## 향후 개발 계획

1. 지도 라이브러리 통합 (예: Kakao Map, Naver Map 등)
2. 교통약자 경로 탐색 알고리즘 구현
3. 접근성 정보 표시 기능
4. 사용자 인터페이스 개선
5. 반응형 디자인 적용

## 라이선스

이 프로젝트는 비공개(private) 프로젝트입니다.

## 기여

현재 이 프로젝트는 개발 중입니다. 기여 및 문의사항은 프로젝트 관리자에게 연락해주세요.
