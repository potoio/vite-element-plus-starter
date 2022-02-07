<div align="center">
  <h2>Vite + Element-Plus Template</h2>

  <a href="https://standardjs.com">
    <img 
      src="https://img.shields.io/badge/code_style-standard-brightgreen.svg?style=flat" 
      alt="Code Style"
    >
  </a>

  <a href="http://commitizen.github.io/cz-cli">
    <img 
      src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg?style=flat" 
      alt="Commitizen"
    >
  </a>
</div>
<br />

## Features
- Faster by default: [vite](https://github.com/vitejs/vite), [vue](https://github.com/vuejs/vue-next), [pnpm](https://github.com/pnpm/pnpm), [esbuild](https://github.com/evanw/esbuild)
- Vue 3 ecosystem: [vue](https://github.com/vuejs/vue-next), [vuex](https://next.vuex.vuejs.org), [vue-router](https://github.com/vuejs/vue-router-next)
- Typescript, of course
- Using new `<script setup>` style
- Support legacy browsers: [@vitejs/plugin-legacy](https://github.com/vitejs/vite/tree/main/packages/plugin-legacy)
- Composition utilities: [vueuse](https://github.com/vueuse/vueuse)
- Fonts auto injecting: [vite-plugin-fonts](https://github.com/stafyniaksacha/vite-plugin-fonts)
- Just in time css utilities: [tailwindcss](https://github.com/tailwindlabs/tailwindcss)
- On-demand components auto importing: [iconify](https://github.com/antfu/vite-plugin-icons), [element-plus](https://github.com/element-plus/element-plus)
- Form validation: [vuelidate](https://vuelidate-next.netlify.app)
- Localization: [vue-i18n](https://github.com/intlify/vue-i18n-next), [vite-plugins-i18n](https://github.com/intlify/vite-plugin-vue-i18n)
- UI Documentation: [storybook](https://github.com/storybookjs/storybook) (ON PROGRESS)
- Testing: [jest](https://github.com/facebook/jest), [testing-library](https://testing-library.com/docs/vue-testing-library/intro)
- HTTP request: [axios](https://github.com/axios/axios)
- Git custom hooks: [husky](https://github.com/typicode/husky)
- Commit conventions: [commitizen](https://github.com/commitizen/cz-cli)
- Linters: [commitlint](https://github.com/conventional-changelog/commitlint), [eslint](https://github.com/eslint/eslint), [stylelint](https://github.com/stylelint/stylelint)
- Visualize bundle: [rollup-plugin-visualizer](https://github.com/btd/rollup-plugin-visualizer)
- Optimized nginx config
- Dockerize

## Dev Tools
- [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar): Vue 3 IDE support
- [Iconify IntelliSense](https://marketplace.visualstudio.com/items?itemName=antfu.iconify): Icon inline display and autocomplete
- [i18n Ally](https://marketplace.visualstudio.com/items?itemName=lokalise.i18n-ally): All in one i18n support
- [Tailwind CSS Intellisense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss): IDE support for Tailwind CSS
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

## Requirement
  - [node.js](http://nodejs.org/)
  - [volta](https://docs.volta.sh/guide/getting-started)
  - [pnpm](https://pnpm.js.org/en/installation)

## Getting Started
### GitHub Template

[Create a repo from this template on GitHub](https://github.com/potoio/vite-element-plus-starter/generate).

### Clone to local
If you prefer to do it manually with the cleaner git history

```bash
# clone repository
$ git clone https://github.com/potoio/vite-element-plus-starter.git

# open folder vite-element-plus-starter
$ cd vite-element-plus-starter

# install packages
$ pnpm install

# build and serve with vite dev server
$ pnpm dev
```

### Run with Docker

```bash
# build docker image and tag it with name nginx
$ docker build . -t potoio-nginx

# run docker image nginx with name vite-element-plus-starter in port 9900
$ docker run -it -p 9900:80 --rm --name vite-element-plus-starter potoio-nginx
```

## Checklist
When you use this template, try follow the checklist to update your info properly

- [ ] Change `name, description, repository, bugs` field in `package.json`
- [ ] Change the author name in `LICENSE`
- [ ] Change the title in `commonState.ts`
- [ ] Change the favicon in `public`
- [ ] Remove the `.github` folder which contains the funding info
- [ ] Clean up the README(s) and remove modules

## How to Create Folder
A guide how to create a folder using `create-cli`

### Component
```bash
# create new atom component with name loading
$ node create component atoms loading
```

### Module
```bash
# create new module with name home and with all types
$ node create module home all
```

