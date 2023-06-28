# eslint-config-tcf
더클라우드팩토리의 eslint-config 패키지입니다.
프로젝트마다 반복되는 eslint 설정을 하나의 패키지로 관리합니다. 

## Usage
github 저장소에 있는 패키지를 설치하기 위해서는 .npmrc 파일이 필요합니다.<br>
[working-with-the-npm-registry#installing-a-package](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#installing-a-package)

### Install
```shell
npm install --save-dev @tcfkr/eslint-config-tcf
```

### Code
```js
// .eslintc.js
module.exports = {
  extends: ['@tcfkr/eslint-config-tcf']
}
```

## Build & Deploy
현재 특정한 브런치 전략을 사용하지 않고 main 브런치에 커밋합니다.

### Publish package
```shell
# login git account
npm login --scope=@tcfkr --auth-type=legacy --registry=https://npm.pkg.github.com
# username: {username}
# password: {personal access token}

npm publish
```

## Required
이 프로젝트를 이해하기 위해서는 아래의 글들을 참고하면 좋습니다.
- [eslint](https://eslint.org/docs/latest/use/core-concepts)
- [eslint-config](https://eslint.org/docs/latest/use/configure/)
- [npm-publish](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#publishing-a-package)

