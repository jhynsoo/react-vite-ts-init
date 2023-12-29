# react-vite-ts-init

## What is this?

A custom script for personal use to set up a React project with Vite and TypeScript.

## Features

* Remove unnecessary boilerplate code and assets (e.g. `index.css`, `logo.svg`, etc.).
* Configure ESLint and Prettier.
* Install dev dependencies.
  * `eslint-config-airbnb`
  * `eslint-config-airbnb-typescript`
  * `eslint-config-prettier`
  * `eslint-plugin-import`
  * `eslint-plugin-jsx-a11y`
  * `eslint-plugin-react`
  * `eslint-import-resolver-typescript`
  * `prettier`
* Configure path alias as `@` for `src` directory.
* Initialize Git repository.
* Install useful libraries.
* Remove default `README.md` template.

## Libraries installed

* `react-router-dom` and `@types/react-router-dom`.
  * Add 'Router.tsx' in `src/`.
  * Make `src/App.tsx` render `Router`.
* `recoil`
  * Add `RecoilRoot` in `src/App.tsx`.
* `axios`
* `react-query`
  * Add `QueryClientProvider` in `src/App.tsx`.
* `@emotion/styled` and `@emotion/react`
  * Configure `src/emotion.d.ts` for TypeScript.
  * Add global styles in `src/styles/global.tsx`.
  * Add `ThemeProvider` and `Global` in `src/App.tsx`.

## How to use?

Run the following command in your terminal.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/jhynsoo/react-vite-ts-init/master/initreact)"
```
