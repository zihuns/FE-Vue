# Vue 3 Movie App

Vue 3를 사용하여 개발 중인 영화 애플리케이션 프로젝트입니다.

![App Screenshot](./src/assets/app.png)

## 프로젝트 소개

이 프로젝트는 Vue 3 프레임워크를 기반으로 하며, OMDb API를 활용하여 영화 검색 및 상세 정보 조회 기능을 제공합니다. 기본적인 레이아웃 구조(Header, Footer)와 라우팅 시스템을 갖추고 있습니다.

## 주요 구조

`App.vue` 파일을 기준으로 애플리케이션은 다음과 같이 구성됩니다:

- **Header**: 상단 네비게이션 영역 (`~/components/Header`)
- **RouterView**: 라우팅된 페이지가 렌더링되는 메인 영역
- **Footer**: 하단 정보 영역 (`~/components/Footer`)

## 기술 스택

- **Core**: Vue.js 3, Vue Router, Vuex
- **HTTP Client**: Axios
- **Styling**: Bootstrap 5, SCSS
- **Utility**: Lodash
- **Tooling**: Vue CLI, Netlify CLI
- **API**: OMDb API

## 설치 및 실행 방법

```bash
# 의존성 패키지 설치
npm install

# 개발 서버 실행 (Netlify Dev)
npm run serve

# 또는 Webpack 개발 서버 실행
npm run serve:webpack

# 프로덕션 빌드
npm run build

# 린트(Lint) 실행
npm run lint
```
