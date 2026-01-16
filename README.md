# Vue 3 Test Project

이 프로젝트는 Webpack을 사용하여 수동으로 구성된 Vue 3 애플리케이션입니다. Vue 3의 기본적인 컴포넌트 시스템, 반응형 데이터, 그리고 Webpack 설정 방법을 확인하기 위한 예제 프로젝트입니다.

![App Screenshot](src/assets/app.png)

## 🛠 기술 스택 (Tech Stack)

- **Framework**: Vue 3
- **Bundler**: Webpack 5
- **Styling**: SCSS (Sass)
- **Transpiler**: Babel

## 📂 프로젝트 구조 (Project Structure)

- **`src/App.vue`**: 메인 애플리케이션 컴포넌트입니다. 카운터 로직과 과일 목록 렌더링을 포함하고 있습니다.
- **`src/components/Fruit.vue`**: 개별 과일 항목을 표시하는 자식 컴포넌트입니다. `props`를 통해 데이터를 전달받습니다.
- **`webpack.config.js`**: Vue 로더, SCSS 처리, Babel 변환, 개발 서버 설정 등 프로젝트 번들링을 위한 설정 파일입니다.

## ✨ 주요 기능 (Features)

1. **카운터 (Counter)**

   - 숫자를 클릭하면 카운트가 1씩 증가합니다.
   - 카운트가 4보다 커지면 "4보다 큽니다!"라는 메시지가 조건부 렌더링(`v-if`)으로 표시됩니다.

2. **목록 렌더링 (List Rendering)**
   - `App.vue`의 데이터(`Apple`, `Banana`, `Cherry`)를 기반으로 `Fruit` 컴포넌트를 반복 렌더링합니다.
   - 부모 컴포넌트에서 자식 컴포넌트로 데이터를 전달하는 `props` 활용 예시가 포함되어 있습니다.

## 🚀 실행 방법 (Getting Started)

### 의존성 설치

```bash
npm install
```

### 개발 서버 실행

Webpack Dev Server를 통해 로컬 환경(`localhost:8080`)에서 프로젝트를 실행합니다.

```bash
npm run dev
```

### 프로덕션 빌드

```bash
npm run build
```
