# ts-project-base

## Quick Start

```sh
# https://github.com/Rich-Harris/degit
degit lanlyhs/ts-project-base
```

## init

```sh
# https://docs.npmjs.com/cli/v8/commands/npm-init
npm init -y
# https://github.com/tj/git-extras/blob/master/Commands.md#git-ignore-io
git-ignore-io macos,node > .gitignore
```

## build

```sh
npm install -D typescript
# https://www.typescriptlang.org/docs/handbook/compiler-options.html
npx tsc --init
```

## test

```sh
# https://kulshekhar.github.io/ts-jest/docs/getting-started/installation
npm install -D jest ts-jest @types/jest
npx ts-jest config:init
```

## linter

```sh
# https://typescript-eslint.io/docs/linting/
npm install -D eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin
```

## formatter

```sh
# https://prettier.io/docs/en/install.html
npm install -D prettier eslint-config-prettier
```

## git hooks

```sh
# https://github.com/okonet/lint-staged
# https://github.com/typicode/husky
npx mrm@2 lint-staged
```
