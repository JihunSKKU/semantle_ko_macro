## Semantle Ko 자동 매크로 사용법

Semantle Ko 사이트의 단어 맞추기 게임을 자동으로 풀기 위한 브루트포스 매크로입니다. 사용법은 다음과 같습니다:

1. 웹사이트 [꼬맨틀](https://semantle-ko.newsjel.ly/)에 접속합니다.
2. 개발자 도구를 열고 Console 탭으로 이동합니다.
3. [`macro.js`](./macro.js) 파일의 코드를 Console 창에 붙여넣고 실행합니다.

만약 매크로를 중지하고 싶다면, Console 창에 아래 코드를 입력하세요:
```javascript
clearInterval(key);
```

이 코드는 매크로 실행을 중지하고, 게임을 수동으로 계속 풀 수 있게 해 줍니다.