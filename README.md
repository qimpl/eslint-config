# Qimpl Eslint/Prettier config

Qimpl shared eslint configuration

[![NPM](https://img.shields.io/npm/v/@qimpl/eslint-config.svg)](https://www.npmjs.com/package/@qimpl/eslint-config)

## Usage

```
npx install-peerdeps --dev @qimpl/eslint-config
```

### React

There is the `.eslintrc.js` config for React/React Native projects:

```js
module.exports = {
  extends: '@qimpl/eslint-config/react',
};
```

### Svelte

There is the `.eslintrc.js` config for Svelte projects:

```js
module.exports = {
  extends: '@qimpl/eslint-config/svelte',
};
```

## VS Code config

Once you have done. You probably want your editor to lint and fix for you.

1. Install the [ESLint package](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
2. Now we need to setup some VS Code settings via `Code/File` → `Preferences` → `Settings`. Click to the `{}` icon in the top right corner and add this :

```json
{
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  }
}
```
