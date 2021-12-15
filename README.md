# vite-vue-prettier

This is a highly opinionated starter template to use with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Included

- Vue 3, `<script setup>` SFCs
- Vite
- Prettier
- eslint
- stylelint
- autoprefixer
- vite-plugin-legacy
- vite-svg-loader
- husky + lint-staged

## Not included

This template doesn't include either vue-router, vuex or pinia. These modules are widely used in Vue ecosystem, but they are not necessary in every single project and the way of adding and using them is very well documented and pretty straightforward. On the other hand, getting both eslint and stylelint to play well with Vue SFCs and Prettier may be tricky.

## Prerequisites

- node 12+
- yarn 1

## Install

You can use a tool like [degit](https://github.com/Rich-Harris/degit) to scaffold your project with one of the templates.

```sh
npx degit cyberbobs/vite-vue-prettier my-project
cd my-project

yarn
yarn dev
```

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)
