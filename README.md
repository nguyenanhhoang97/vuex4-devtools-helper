# vuex4-devtools-helper

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?style=flat-square)](https://github.com/nguyenanhhoang97/vuex4-devtools-helper/blob/main/LICENSE)
![GitHub top language](https://img.shields.io/github/languages/top/nguyenanhhoang97/vuex4-devtools-helper?color=0076C5&style=flat-square)
![GitHub package.json version](https://img.shields.io/github/package-json/v/nguyenanhhoang97/vuex4-devtools-helper?style=flat-square)
![npm](https://img.shields.io/npm/v/vuex4-devtools-helper?color=CD3738&style=flat-square)
[![for-vuejs](https://img.shields.io/badge/Made%20for-VueJS-42B983.svg?style=flat-square)](https://vuejs.org/)
[![for-vuex](https://img.shields.io/badge/Made%20for-Vuex-42B983.svg?style=flat-square)](https://vuex.vuejs.org/)

## **Introduction**

We missed `Vuex Inspector` when we develop an web app with Vue 3 and Vuex 4. So this package can help us to use `Vuex Inspector` of `Vue.js devtools`

## **Installation**

### Yarn

```bash
yarn add -D vuex4-devtools-helper
```

### NPM

```bash
yarn add -D vuex4-devtools-helper
```

## **Usage**

```ts
import { createApp } from 'vue';
import { addDevtools } from 'vuex4-devtools-helper';
import store from <PATH-TO-YOUR-STORE>;

const app = createApp(App);
\\ ... Your implementation
app.use(store);
\\ ... Your implementation
addDevtools(app, store);

```
