# 構築導入

当プロジェクトの初期構築を記録する為にこのファイルは、作成されています.

## ライブラリ導入

### 依存関係

`npm i react react-dom`

### 開発用の依存関係

`npm i -D dotenv lint-staged simple-git-hooks eslint prettier typescript ts-node webpack webpack-cli electron electron-reload`

## 設定ファイルの作成

`npx tsc --init`
`npx eslint --init`
`touch .gitignore .npmignore .editorconfig .eslintignore .prettierignore LICENSE README.md webpack.config.ts tsconfig.main.json`
`echo {}> .prettierrc.json`

## 型定義のライブラリを導入

`npm i -D @types/node @types/react @types/react-dom @types/webpack-dev-server`

## eslint のルールライブラリを導入

`npm i -D eslint-config-airbnb eslint-plugin-import eslint-plugin-jsx-a11y eslint-plugin-react eslint-plugin-react-hooks @typescript-eslint/eslint-plugin @typescript-eslint/parser`

## bundle のためのローダーとプラグインを導入

`npm i -D ts-loader css-loader`
`npm i -D mini-css-extract-plugin @types/mini-css-extract-plugin html-webpack-plugin`
