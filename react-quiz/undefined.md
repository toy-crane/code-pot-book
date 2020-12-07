---
description: with VS-Code
---

# 개발 환경 셋팅하기

## VS Code 설치하기

우리 프로젝트에서는 `VS Code` 를 기본 코드 에디터로 사용할 예정입니다.

[VS Code 공식 홈페이지](https://code.visualstudio.com/)에서 다운로드 받아 설치 해주세요.

## Node.js 설치하기

[Node.js 공식 홈페이지](https://nodejs.org/en/)에서 왼쪽에 있는 Node.js LTS 버전을 설치합니다.

React를 공부하는데 Node.js는 왜 설치해야 하나요? javascript로 작성된 라이브러리를 설치할 때, 사용하는 NPM을 사용하기 위함 입니다. NPM은 Node.js가 설치가 되면 자동으로 설치가 됩니다.

## React 프로젝트 시작하기

터미널을 열고, react 프로젝트를 생성하는 아래의 명령어를 실행합니다. \(혹 터미널이 익숙하지 않다면 맨 아래 터미널 셋팅 방법을 확인해 주세요\)

```jsx
npx create-react-app starter-quiz-app
```

npx는 설치하지 않았는데, 어떤 명령어 인가요? npx는 npm의 확장 버전으로 npm이 하지 못했던 일들을 추가적으로 할 수 있게 도와줍니다. 또한 npx는 npm이 설치되면 자동으로 설치가 됩니다.

create-react-app은 뭐죠? react 어플리케이션을 쉽게 만들어 주는 도구입니다. 예전에는 react를 실행 하려면 여러 라이브러리들을 같이 설치했어야 했는데, 이러한 불편함을 한 방에 해결해주는 고마운 도구에요 🙇‍♂️ 🙇‍♂️

설치가 완료되면 `ls` 명령어를 통해 실행한 경로에 `starter-quiz-app` 이 생긴 것을 확인 하실 수 있습니다.

이제 react 코드를 실행해 보도록 하겠습니다.

`cd` 명령어로 폴더로 이동하고, `npm run` 명령어를 통해 리액트 코드를 실행합니다.

```jsx
cd starter-quiz-app
npm start
```

코드를 실행하면, 아래와 같은 화면이 뜨면서 정상적으로 react 코드가 실행된 것을 볼 수 있습니다.

터미널에 적혀 있는 `http://localhost:3000` 주소로 접속해 보도록 하겠습니다.

이 주소는 앞으로 react 코드가 실행될 때, 확인할 수 있는 주소로 계속해서 사용하게 될 것입니다.

## Something More !!!

반드시 공부해야 하는 건 아니지만, 도움이 될 만한 자료들을 공유하고 있습니다.

* Javascript 패키지 도구로는 yarn과 npm이 있습니다.

  [https://devgunho.tistory.com/entry/Yarn-vs-npm-Package-Manager](https://devgunho.tistory.com/entry/Yarn-vs-npm-Package-Manager)

* VS Code에서 터미널 창 실행하기
  * Mac 사용자
    * `vs-code` 상단 메뉴 View → Terminal을 클릭하면 터미널 창이 열리는 것을 확인 할 수 있습니다.
  * Window 사용자
    * 윈도우는 기본적으로 리눅스 명령어가 작동하지 않습니다. 그래서 우선 `git bash` 설치가 필요합니다.
      * git bash 설치하기 ⇒ [https://tnsgud.tistory.com/648](https://tnsgud.tistory.com/648)
    * `vs-code` 에서 default로 `git bash` 사용하도록 설정하기
      * `Ctrl +` 명령어로 설정으로 들어 갑니다.
      * 검색창에 `terminal.integrated.shell.windows` 를 입력합니다.
      * `“terminal.integrated.shell.windows”: “”` 에 Git Bash가 설치된 경로를 입력합니다.
      * 이제 View → Terminal을 클릭하면 터미널 창이 열리는 것을 확인 할 수 있습니다.
* create-react-app은 유용한 기능들을 많이 가지고 있습니다.

  [https://create-react-app.dev/docs/getting-started](https://create-react-app.dev/docs/getting-started)

