## createElement

React.createElement(Component, props, ...children) => ReactElement


## use Babel
## Advantage of using Babel 
1. convert
2. delete commnet
3. 코드 압축

### How to Install Babel
npx babel --watch src --out-dir . --presets@babel/preset-react //deprecated
`npm install --save-dev babel-cli`

## What is Webpack
- js로 만든 프로그램을 배포하기 좋은 형태로 묶어주는 도구(배포하기 좋은 형태란, 웹팩을 사용하지 않고 배포하면 어떤 어려움이 있는지)

웹펙은 ESM(ES6의 모듈 시스템),commonJS 모두 지원 
=> 코드 작성후 웹팩 실행 시 예전 버전의 브라우저에서도 동작하는 자바스크립트 코드를 짤 수 있다.
웹팩 실행 시 하나의 자바스크립트 파일 생성 => 원한다면 multiple 가능

### Install Webpack
npm install webpack webpack-cli react react-dom