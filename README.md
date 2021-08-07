# eslintc

[![CI](https://github.com/GiovanniCardamone/eslint-config/actions/workflows/npm-ci.yml/badge.svg)](https://github.com/GiovanniCardamone/eslint-config/actions/workflows/npm-ci.yml)
[![NPM version](https://img.shields.io/npm/v/@giovannicardamone/eslint-config.svg?style=plastic)](https://www.npmjs.com/package/@giovannicardamone/eslint-config)
[![NPM downloads](https://img.shields.io/npm/dm/@giovannicardamone/eslint-config.svg?style=plastic)](https://www.npmjs.com/package/@giovannicardamone/eslint-config)

My Eslint Configuration

## :information_source: Features

- es2021
- typescript
- node
- browser
- mocha

## :package: Installation

Install package

```bash
  npm i -D @giovannicardamone/eslint-config
```

Install required dev dependencies

```bash
  npm i -D eslint @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

Add eslintrc configuration in your `package.json`

```json
{
  "name": "your-beautiful-package",
  "eslintConfig": {
    "extends": "@giovannicardamone/eslint-config"
  }
}
```
