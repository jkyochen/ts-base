# ts-base

## Quick Start

```sh
npx degit lanlyhs/ts-base
```

[degit](https://github.com/Rich-Harris/degit)

## init

```sh
npm init -y
git-ignore-io macos,node > .gitignore
```

[npm-init](https://docs.npmjs.com/cli/v8/commands/npm-init)

[git-ignore-io](https://github.com/tj/git-extras/blob/master/Commands.md#git-ignore-io)

## build

```sh
npm install -D typescript
npx tsc --init
```

[tsc](https://www.typescriptlang.org/docs/handbook/compiler-options.html)

## test

```sh
npm install -D jest ts-jest @types/jest
npx ts-jest config:init
```

[ts-jest](https://kulshekhar.github.io/ts-jest/docs/getting-started/installation)

[jest](https://jestjs.io/)

## linter

```sh
npm install -D eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin
```

[typescript-eslint](https://typescript-eslint.io/docs/linting/)

[eslint](https://eslint.org/)

## formatter

```sh
# https://prettier.io/docs/en/install.html
npm install -D prettier eslint-config-prettier
```

[prettier](https://prettier.io/)

## git hooks

```sh
npx mrm@2 lint-staged
```

[lint-staged](https://github.com/okonet/lint-staged)

[husky](https://github.com/typicode/husky)
