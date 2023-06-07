# eslint-config-tcf

더클라우드팩토리에서 내부에서 사용하는 ESlint 모듈입니다.

## install
```js
// 프로젝트 루트 디렉터리에 .eslintrc.js
module.exports = {
  extends: "@tcfkr/eslint-config-tcf"
}

```

```shell
npm install eslint-plugin-import eslint-plugin-node
npm link @tcfkr/eslint-config-tcf
```

## run
```shell
npx eslint ./파일
```