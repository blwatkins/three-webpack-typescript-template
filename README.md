# Three.js TypeScript Template

A template project for using [Three.js](https://threejs.org/) with [TypeScript](https://www.typescriptlang.org/) and [webpack](https://webpack.js.org/).

## Getting Started

Create a new project from this template using the green "Use this template" button above.

Write the project's source code in the `src/` directory.
The `src/main.ts` file provided contains a simple Three.js program with a rotating green cube.
This file will be used as the entry point for webpack.

## Installation

```shell
npm install
```

`npm install` will install all the dependencies required to run this project.

## Linting

### Linting TypeScript

```shell
npm run lint:ts
```

`npm run lint:ts` will lint the TypeScript source code using ESLint, identifying syntactic and stylistic errors based on a configured set of rules.
TypeScript linting configurations and rules can be found, edited, and updated in `eslint.config.ts.mjs`.

### Linting JavaScript

```shell
npm run lint:js
```

`npm run lint:js` will lint the JavaScript configuration files using ESLint, identifying syntactic and stylistic errors based on a configured set of rules.
JavaScript linting configurations and rules can be found, edited, and updated in `eslint.config.js.mjs`.

## Building the Bundle

### Building the Bundle in Development Mode

```shell
npm run build:dev
```

`npm run build:dev` will bundle your sketch in development mode using webpack.
This should identify any compiler errors present in your source code.
The webpack build configuration can be found in `webpack.config.mjs`.

### Building the Bundle in Production Mode

```shell
npm run build
```

`npm run build` will bundle your sketch in production mode using webpack.
The webpack build configuration can be found in `webpack.config.mjs`.

## Serving the Bundle

### Serving the Development Bundle

```shell
npm run serve:dev
```

`npm run serve:dev` will bundle the scene in development mode, start a localhost development server (`127.0.0.1:8080`), and open a new browser window for the `index.html` file bundled with the compiled scene.

### Serving the Production Bundle

```shell
npm run serve
```

`npm run serve` will bundle the scene in production mode, start a localhost development server (`127.0.0.1:8080`), and open a new browser window for the `index.html` file bundled with the compiled scene.

## GitHub Workflows

This template contains GitHub workflows designed to update project dependencies and scan the code for security vulnerabilities every month.

To learn more about Dependabot configurations, visit the [GitHub Dependabot documentation](https://docs.github.com/en/code-security/dependabot).

To learn more about CodeQL configurations, visit the [GitHub CodeQL documentation](https://codeql.github.com/docs/).

[![CodeQL](https://github.com/blwatkins/three-webpack-typescript-template/actions/workflows/codeql.yml/badge.svg)](https://github.com/blwatkins/three-webpack-typescript-template/actions/workflows/codeql.yml)
[![npm Build](https://github.com/blwatkins/three-webpack-typescript-template/actions/workflows/npm-build.yml/badge.svg)](https://github.com/blwatkins/three-webpack-typescript-template/actions/workflows/npm-build.yml)

## Attributions

The favicon.ico of this template was designed by [Freepik from Flaticon](https://www.flaticon.com/free-icons/art).
You can find the original icon on [flaticon.com](https://www.flaticon.com/free-icon/art_1756752?term=art&page=1&position=38&origin=search&related_id=1756752).

## License

The source code of this project is licensed under the [MIT License](https://opensource.org/license/mit).
The full text of the license is included with the package source code.

----

Copyright &copy; 2024-2026 Brittni Watkins.
