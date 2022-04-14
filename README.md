# New-React-Create-Project-
How to create React Project latest Version

## 기존 방법(더 이상 지원 X) 
####  - ..정확히는 지원하지 않는다기 보다는 글로벌로 create-react-app이 install 되어 있는 상태에서 이 방법을 수행하면 경고문이 나타남
> create-react-app 모듈 설치 및 프로젝트 생성, 시작
```bash
npm install -g create-react-app
create-react-app [Project명]
cd [Project명]
npm start
```
## 변경 방법
### 1. Quick Start
```bash
npx create-react-app [Project명]
cd [Project명]
npm start
```

#### 1-1(npm init).
```bash
npm init react-app [Project명]
```

#### 1-2(yarn create).
```bash
yarn create react-app [Project명]
```
### 2. npm uninstall -g create-react-app 후 다시 install -> npm install -g create-react-app
```bash
npm uninstall -g create-react-app

npm install -g create-react-app
```

#### 2-1(create-react-app).
```bash
create-react-app [Project명]
```
