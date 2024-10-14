# Semantle Ko 자동 매크로 사용법

Semantle Ko 사이트의 단어 맞추기 게임을 자동으로 풀기 위한 브루트포스 매크로입니다. 사용법은 아래 단계를 따르세요.

## 사용법

1. [Semantle Ko](https://semantle-ko.newsjel.ly/) 웹사이트에 접속합니다.
2. 브라우저에서 **개발자 도구**를 엽니다. (Chrome 기준 `F12` 또는 `Ctrl+Shift+I`로 개발자 도구를 열 수 있습니다.)
3. **Console** 탭으로 이동한 후, [`macro.js`](./macro.js) 파일의 코드를 복사하여 붙여넣고 실행합니다.

### 매크로 중지 방법

매크로 실행을 중지하고 싶을 경우, 개발자 도구의 **Console** 창에 아래 코드를 입력합니다:
```javascript
clearInterval(key);
```

이 코드를 입력하면 매크로가 중지되며, 게임을 수동으로 계속 풀 수 있습니다.

## 붙여넣기 오류(경고) 해결 방법

간혹 `Ctrl+V`로 붙여넣기 할 때 경고(warning) 메시지가 뜨면서 제대로 복사/붙여넣기가 되지 않는 경우가 있습니다. 이 문제는 개발자 도구의 **Console** 창에 아래 코드를 입력하여 해결할 수 있습니다:

```javascript
allow pasting
```

이 명령어를 입력하면 붙여넣기가 허용되며, 이후 `Ctrl+V`로 매크로 코드를 정상적으로 붙여넣을 수 있습니다.

### 경고 메시지 예시

경고 메시지 예시는 다음과 같습니다:

```
Warning: Don’t paste code into the DevTools Console that you don’t understand or haven’t reviewed yourself. This could allow attackers to steal your identity or take control of your computer. Please type ‘allow pasting’ below and hit Enter to allow pasting.
```
