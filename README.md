# eslint-config-tcf

-----
더클라우드팩토리에서 내부에서 사용하는 ESlint config 모듈입니다.

## Usage

-----
`.eslintrc.js` extends에 `@tcfkr/eslint-config-tcf` 를 입력해서 사용할 수 있습니다. ESLint configuration은 [여기](https://eslint.org/docs/latest/use/configure/)를 참조하세요.

```js
module.exports = {
  extends: "@tcfkr/eslint-config-tcf"
}

```

### How to test

```shell
npm link @tcfkr/eslint-config-tcf
```

```shell
npx eslint ./src
```