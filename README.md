<div align="center">
  <img src="https://ciro.club/statics/images/icons/1671040126_sJJ__CzS1xMlbFRzvtJnz.svg" style="width: 320px" alt="logo" />
  <h1>tiny-lorem</h1>
</div>

> A modern JavaScript tool library for generating simulation data. Has perfect type hinting. Can be used in **browser** and **node**.

[English](README.md) | [简体中文](README-ZH.md)

[![codecov](https://codecov.io/gh/cirolee/tiny-lorem/branch/main/graph/badge.svg)](https://codecov.io/gh/cirolee/tiny-lorem/branch/main) ![npm bundle size](https://img.shields.io/bundlephobia/min/tiny-lorem) ![GitHub release (release name instead of tag name)](https://img.shields.io/github/v/release/cirolee/tiny-lorem) ![GitHub](https://img.shields.io/github/license/cirolee/tiny-lorem)

## view the demo

[![](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/edit/vitejs-vite-84xphd?file=index.html)

## Installation

pnpm

```shell
pnpm install tiny-lorem
```

yarn

```shell
yarn install tiny-lorem
```

npm

```shell
npm install tiny-lorem
```

## Usage

ESM(ESModule)

```ts
import TinyLorem from 'tiny-lorem';
const lorem = new TinyLorem();

lorem.texts.word(); // 汉
lorem.number.int(); // 123
```

CJS(CommonJs)

```ts
const TinyLorem = require('tiny-lorem').default;
const lorem = new TinyLorem();

lorem.texts.word(); // 汉
lorem.number.int(); // 123
```

## API Documents

[Documents](https://ciro.club/tiny-lorem)

## Inspired by

[Mockjs](https://github.com/nuysoft/Mock)  
[faker-js](https://github.com/faker-js/faker)

## LICENSE

[MIT](LICENSE)
