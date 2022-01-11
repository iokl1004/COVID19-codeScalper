생활코딩 리액트 강좌를 완강하고 뭔가 API도 사용해보고 싶어서 유튜브를 검색해보면서 50분강의에서 리액트를 이용한 코로나 집계사이트를 만드는 강의를 봤다.
현재 코로나 시국이여서 괜찮은 프로젝트인것같기도 하고, 리액트 초보인 나로써는 적합한 프로젝트라 생각이 들어 시도를 하였다.

Edit : VS Code
node js 버전 : 17.3.0
npm 버전 : 8.3.0

nodejs & npm설치
1. 홈페이지 접속 후 파일을 다운로드하고 설치 진행 : nodejs.org/ko/download/
2. cmd창 열어서 node -v 입력 후 Enter 치면 v17.3.0 처럼 나오는지 확인
3. cmd창에서 npm -v 입력 후, Enter치면 8.3.0 처럼 나오는지 확인

npx 설치 ( npx란? 노드 패키지를 설치시켜주는 노드 패키지 )
1. cmd창 열어서 npm install npx -g 입력 후 Enter
2. cmd창에서 npx -v 입력 후, Enter 치면 8.3.0 처럼 나오는지 
------------------------------------------------------------------------------------------------------------------------------------
2022.01.07(금) 시작
https://youtu.be/DtLhiMxgsm0?t=1290

2022.01.11(화) 종료
유튜브에서 하라는대로 똑같이하고, 실행해봤는데도 작동이 안된다... 나랑같이
Uncaught TypeError: Cannot read properties of undefined (reading 'map')

에러가 발생한 사람들도 꽤 있었으며 공통점은 3달이내에 댓글을 달았던 사람들이다.
영상을 계속 정주행을 하고 해봐도 안되었으며, 비록 프로젝트는 성공하지 못하였지만 리액트에 대해 좀더 알게되어 다행이다.
처음으로 postman이라는 API를 테스트하는 플랫폼도 사용해봤는데 신기하였다.

------------------------------------------------------------------------------------------------------------------------------------
에러1.Uncaught TypeError: Cannot read properties of undefined (reading 'map')

에러2. The above error occurred in the <ForwardRef(ChartComponent)> component:

    at ChartComponent (http://localhost:3000/static/js/bundle.js:27356:5)
    at div
    at div
    at section
    at Contents (http://localhost:3000/static/js/bundle.js:172:92)
    at div
    at App

Consider adding an error boundary to your tree to customize error handling behavior.
Visit https://reactjs.org/link/error-boundaries to learn more about error boundaries.

에러3. Warning: Can't perform a React state update on an unmounted component. This is a no-op, but it indicates a memory leak in your application. To fix, cancel all subscriptions and asynchronous tasks in a useEffect cleanup function.
