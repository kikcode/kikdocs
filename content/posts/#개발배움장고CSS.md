# 개발/배움/장고/CSS

[Django #5 CSS](https://wonwooddo.tistory.com/78)
[CSS 프레임워크 비교 (Bootstrap, Material UI, Antd, Semantic UI , Tailwind)](https://mingeesuh.tistory.com/6)

#### [Introduction - Semantic UI React](https://react.semantic-ui.com/)

- 정말 간단하고 직관적이기 때문에 큰 러닝 커브 없이 빠르게 소규모 프로젝트에 적용 가능

#### [Tailwind CSS - Rapidly build modern websites without ever leaving your HTML.](https://tailwindcss.com/)

#### [MUI: The React component library you always wanted](https://mui.com/) Material-UI

- 컴포넌트 단위 개발할 때 많이 유용. React-Bootstrap보다 완성도가 높은만큼 커스텀 스타일링 적용은 조금 더 어렵다는 느낌을 받았다 (상대적으로). ✨이걸로 결정

#### [DRF를 이용한 Django-React 프로젝트 3. django-react 개발 환경 구축](https://intrepidgeeks.com/tutorial/django-react-program-using-drf-3-constructing-django-react-development-environment)

#### [Material-UI에 대해서 알아보고 실제로 컴포넌트를 이용하기 | 프리즈의 귀차니즘](https://freez2385.github.io/posts/React-Material-UI/)

### Material-UI 설치하기

[3. Material UI 적용하기 - Ryu](https://haleyryu.gitbook.io/engineer/frontend/react-x-redux/3.-material-ui)
[Material-UI에 대해서 알아보고 실제로 컴포넌트를 이용하기 | フリーズのレイジネス](https://freez2385.github.io/j/posts/React-Material-UI/)

```
npm install @material-ui/core
```

### Rest-api 작성시 설치 모듈(2022.5.2)

```
Package             Version
------------------- -------
asgiref             3.5.1
Django              3.2.12
django-cors-headers 3.11.0
djangorestframework 3.13.1
djongo              1.3.6
pip                 22.0.4
pymongo             3.12.3
pytz                2022.1
setuptools          60.6.0
sqlparse            0.2.4
typing_extensions   4.2.0
wheel               0.37.1
```

### Passionate coding 초기 설정

[DRF를 이용한 Django-React 프로젝트 3. django-react 개발 환경 구축](https://velog.io/@in_g_ing__/django-react-%EA%B0%9C%EB%B0%9C%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%B6%95)  
[django-webpack-loader 설치 - coder-question-ko.com](https://coder-question-ko.com/cq-ko-blog/156976) .
[Django と webpack を連携して､ モダンなフロントエンド環境を構築する](https://zenn.dev/kimuson/articles/b2a96d7c8729659379d3)⭐️  
[DJANGO & REACT 장고와 리액트 연동하기 (1) - 설치편](https://ssilook.tistory.com/entry/%EC%9E%A5%EA%B3%A0%EC%99%80-%EB%A6%AC%EC%95%A1%ED%8A%B8Django-React%EC%97%B0%EB%8F%99%ED%95%98%EA%B8%B0-1-%EC%84%A4%EC%B9%98%ED%8E%B8?category=876974)⭐️  
[DJANGO & REACT 장고와 리액트 연동하기 (4) - 템플릿 변경하기](https://ssilook.tistory.com/entry/%EC%9E%A5%EA%B3%A0%EC%99%80-%EB%A6%AC%EC%95%A1%ED%8A%B8Django-React%EC%97%B0%EB%8F%99%ED%95%98%EA%B8%B0-3-%ED%85%9C%ED%94%8C%EB%A6%BF-%EB%B3%80%EA%B2%BD%ED%95%98%EA%B8%B0?category=876974)⭐️
[Django 및 React Tutorial # 3-Webpack 및 Babel을 사용한 React 통합](https://www.youtube.com/watch?v=6c2NqDyxppU)⭐️  
[꾸생의 DevLog - React 리액트 webpack & babel 설정하기](https://juni-official.tistory.com/158)  
[こんにちは MUI！ 新しくなった Material UI v5](https://zenn.dev/h_yoshikawa0724/articles/2021-09-26-material-ui-v5)  
[함수형 컴포넌트 클래스형 컴포넌트](https://devilfront.tistory.com/87?category=828452)  
[React 初心者が Material-UI で今どきの Web フォームを作ってみた（Stepper 編） | DevelopersIO](https://dev.classmethod.jp/articles/react-beginners-tried-to-create-a-modern-web-form-with-material-ui-stepper/)

```
mkdir backend
python -m venv venv
pip3 install django
pip install djangorestframework
django-admin startproject config .

//nodejs
sudo apt update
sudo apt install nodejs
sudo apt install npm
node -v

// nodejs 업데이트
nodejs -v // 버전이 너무 낮으면 업그레이드할 것
sudo npm cache clean -f // npm 캐시 제거
sudo npm install -g n
sudo n lts

// npm 업데이트
sudo npm i -g npm
npm -v

//기존 nodejs삭제
sudo apt-get --purge remove nodejs

//
npx create-react-app frontend

//Django webpack-loader 설치
npm install --save-dev webpack webpack-cli webpack-bundle-tracker
npm list
//yarn buildはnpm run buildと同じ
//webpack-stats.json 파일은 build하면 출력됨 (webpack.config.js를 빌드해 dist에 결과가 나온다)
	1	Entry : 대상파일
	2	Output : 결과물
	3	Loaders : 다른 Type의 파일 변환
	4	Plugins
	5	Mode
- module.exports = {} : 선언된 객체를 모듈로 출력
- entry : 사용될 js (배열을 이용한 복수설정)
- output :  합쳐질 결과물에 대한 설정
- module : 모듈 설정
- plugins : 플러그인 활용

// 리액트 모듈을 빌드
npm run-script build
npm run dev or npm run build //frontend 디렉토리에서 실행
npm run start

git push -u origin develop
git checkout -b develop

// 리액트 템플릿
python manage.py runserver react

// Material-UI
npm install @mui/material @emotion/react @emotion/styled
npm install @mui/icons-material
// 프로젝트에서 styled-components를 사용해서 스타일링 하기로 했다면 styled-components as a styling engine으로 설치한다.
npm install @mui/styled-engine-sc styled-components
//정규식
react hook form



// 수정할 때 마다 새로고침 없이 수정된 내용만 변경된다.
// 리액트 핫 로더
npm install --save-dev react-hot-loader // 근데 리액트 버전이 높아서 못깔았다
npm ERR! Could not resolve dependency:
npm ERR! peer react@"^15.0.0 || ^16.0.0 || ^17.0.0 " from react-hot-loader@4.13.0

npm update -g npm
npm update -g // 모든 글로벌 패키지 업데이트

자세히 보니 react 버전이 너무 높아서 hot-loader가 안깔린다

sudo npm install -g n //n은 node의 버전을 관리해주는 플러그인
n rm 0.9.4 v0.10.0 //특정 버전 삭제
n latest
npm install npm-check
npm uninstall react@17.0.2 react-dom@17.0.2

npm install --save react@^17.0.0 react-dom@^17.0.0
npm install react@17.0.0 react-dom@17.0.0

```

[Configuration | webpack](https://webpack.js.org/configuration/)⭐️  
`webpack5 module not found` 에러 대응 : import한 모듈명이 맞는지 확인할 것

### Bable

[Babel 이해하기. react로 개발을 하고 있다면 거의 대부분 babel도 함께 사용하고… | by landvibe | Medium](https://ljs0705.medium.com/babel-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-a1d0e6bd021a)  
[꾸생의 DevLog - React 리액트 webpack & babel 설정하기](https://juni-official.tistory.com/158)

```
npm i react react-dom
npm i -D @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
npm install @babel/plugin-proposal-class-properties
npm install react-router-dom

babel.config.json
```

npm을 사용해 webpack, webpack-cli를 개발에서만 사용할 수 있도록 dev(-D) 명령어를 넣어주고 이를 package.json 파일에 남겨놓기 위해 —save 명령어를 추가해 설치해준다.

- babel/core : 기본적인 바벨로 최신 문법으로 변환해주는 역할을 한다.
- babel/preset-env : 여러 환경에 맞게 JavaScript를 동작하게 해 준다.
- babel/preset-react : 리액트를 위한 플러그인 모음
- babel-loader : 바벨(babel)과 웹팩(webpack)을 연결해준다.

### **style-loader, css-loader 설치**

```
npm i -D style-loader css-loader
```

### template

[Django と webpack を連携して､ モダンなフロントエンド環境を構築する](https://zenn.dev/kimuson/articles/b2a96d7c8729659379d3)⭐️  
[9+ Free React Templates - Material UI](https://mui.com/material-ui/getting-started/templates/)  
[React with TypeScript プロジェクトに Material-UI を導入してみる - Multi Vitamin & Mineral](https://multimineral-tech.com/entry/2021/01/15/200454)  
[最新版 TypeScript+webpack 5 の環境構築まとめ(React, Vue.js, Three.js のサンプル付き) - ICS MEDIA](https://ics.media/entry/16329/)⭐  
[Theming - Material UI](https://mui.com/material-ui/customization/theming/)  
[Minimal Free – Client & Admin Dashboard | MUI Store](https://mui.com/store/previews/minimal-dashboard-free/)  
[React MUI Templates - Open-Source and FREE](https://www.admin-dashboards.com/react-mui-template-open-source/)  
[YouTube](https://www.youtube.com/playlist?list=PLDxCaNaYIuUlG5ZqoQzFE27CUOoQvOqnQ)  
[Berry Free - React Material Admin Dashboard | MUI Store](https://mui.com/store/previews/berry-react-material-admin-free/)[Documentation - Berry Material-UI React](https://codedthemes.gitbook.io/berry/)

```
npm install --save-dev @types/react-router-dom
npm i -D typescript ts-loader
npm i -S @types/react @types/react-dom


npm i @tabler/icons --legacy-peer-deps
npm install react-perfect-scrollbar --legacy-peer-deps
npm install framer-motion --legacy-peer-deps
npm install react-redux --legacy-peer-deps
npm i react-device-detect --legacy-peer-deps
npm i material-ui-popup-state --legacy-peer-deps
npm install svg-inline-loader --legacy-peer-deps
npm i redux --legacy-peer-deps
npm install sass-loader sass webpack --legacy-peer-deps
npm i webpack-loader html-loader --legacy-peer-deps
```

**tsconfig.json**

#개발/배움/npm

```
npm uninstall webpack-loader html-loader --legacy-peer-deps
npm uninstall sass-loader sass webpack --legacy-peer-deps
npm uninstall redux --legacy-peer-deps
npm uninstall svg-inline-loader --legacy-peer-deps
npm uninstall material-ui-popup-state --legacy-peer-deps
npm uninstall react-device-detect --legacy-peer-deps
npm uninstall react-redux --legacy-peer-deps
npm uninstall framer-motion --legacy-peer-deps
npm uninstall react-perfect-scrollbar --legacy-peer-deps
npm uninstall @tabler/icons --legacy-peer-deps
```

[어도비 xd에서 ui 키트를 사용하는 방법 2022](https://ko.joecomp.com/how-use-ui-kits-adobe-xd)
[Material Symbols and Icons - Google Fonts](https://fonts.google.com/icons?selected=Material+Icons)

[MUI の Dashboard Template を React アプリに導入してみた | DevelopersIO](https://dev.classmethod.jp/articles/using-the-management-screen-template-of-mui/)

[React Fast Refresh](https://dev-momo.tistory.com/entry/React-Fast-Refresh)

```
npm install -D @pmmmwh/react-refresh-webpack-plugin react-refresh
npm install -D type-fest
```

[React Fast Refresh 적용하기. 최근 react-hot-loader를 적용한 리액트 환경에서… | by Jusung Hwang | Medium](https://nabigraphics.medium.com/react-fast-refresh-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0-d68dab89da57)
[웹팩 플러그인 사용법 및 주요 플러그인 | cckn’s Devlog](https://www.cckn.dev/webpack/%EC%9B%B9%ED%8C%A9-%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8-%EC%82%AC%EC%9A%A9%EB%B2%95-%EB%B0%8F-%EC%A3%BC%EC%9A%94-%ED%94%8C%EB%9F%AC%EA%B7%B8%EC%9D%B8/)

[GitHub - pmmmwh/react-refresh-webpack-plugin: A Webpack plugin to enable “Fast Refresh” (also previously known as Hot Reloading) for React components.](https://github.com/pmmmwh/react-refresh-webpack-plugin)

WebSocket connection to failed
WebSocket connection to 'wss://unfamiliarcode-fjnsx.run.goorm.io/\_next/webpack-hmr' failed:
ERR_UNKNOWN_URL_SCHEME

# Path parameter

- 원하는 조건의 데이터들### 혹은

하나의 데이터### 에 대한 정보를 받아올 때 적절

### (따로 정제되지 않은 데이터 가져올 때..!)

# Query string

- filtering### ,

sorting### ,
searching### 에 적절

![](%23%E1%84%80%E1%85%A2%E1%84%87%E1%85%A1%E1%86%AF%E1%84%87%E1%85%A2%E1%84%8B%E1%85%AE%E1%86%B7%E1%84%8C%E1%85%A1%E1%86%BC%E1%84%80%E1%85%A9CSS/image.png)
