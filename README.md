# Typescript Practice

## Create Typescript
```
 yarn create react-app my-app --template typescript
```

## Install eslint

```
 yarn add -D typescript @typescript-eslint/parser
 yarn add -D typescript-eslint/eslint-plugin
 yarn create @eslint/config //eslintrc.js 파일 생성하기
 
 참고: https://eslint.org/docs/user-guide/getting-started
```

## Prettier 연결하기
```
yarn add eslint-config-prettier
```

root에 .prettierrc 파일 생성 후
```
{
  "singleQuote": false,
  "semi": true,
  "useTabs": false,
  "tabWidth": 2,
  "trailingComma": "all",
  "printWidth": 120,
  "arrowParens": "always"
} 
```
추가하기

그 외 eslintrc.js에 추가할 내용 구글링 ㄲ
