# vue2-editor

HTML editor using Vue.js 2.0 and Quill.js, an open source editor&#34;

## Install

```bash
yarn add vue2-editor
```

## Usage

```js
import Vue2Editor from 'vue2-editor'

//... your code
```

## Folder structure

- `src/`: Source files for this component
  - `Vue2Editor.vue` The component itself
- `example/`: Example for demonstrating this component
  - `index.js`: Entry for the example
  - `App.vue`: The root component which we use to load this component
- `vbuild.example.js`: Config file for your example
- `vbuild.component.js`: Config file for your component
- `package.json`: App manifest
- `.editorconfig`: Ensure consistent editor behaivor
- `.gitignore`: Ignore files we don't need to push

## Development

- `yarn example`: Run example in development mode
- `yarn deploy`: Deploy example to gh-pages
- `yarn build:cjs`: Build component in commonjs format
- `yarn build:umd`: Build component in umd format
- `yarn build`: Build component in both format
- `yarn lint`: Run eslint

Check out your npm scripts, it's using [vbuild](https://github.com/egoist/vbuild) under the hood.

---

Generated by [create-vue-app](https://github.com/egoist/create-vue-app)