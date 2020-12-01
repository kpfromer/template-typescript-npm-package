# template-typescript-npm-package

## Description

A barebones file structure for creating a npm package in TypeScript.

## Includes

- [eslint](https://github.com/eslint/eslint)
- [jest](https://github.com/facebook/jest) for testing
- A GitHub workflow file for continuous testing and npm publishing
- [semantic-release](https://github.com/semantic-release/semantic-release) for a fully automated
  release (using semantic versioning)
- [prettier](https://github.com/prettier/prettier), [husky](https://github.com/typicode/husky),
  [lint-staged](https://github.com/okonet/lint-staged) for automatic formatting and linting

# Scripts

- `start` for starting `src/index.ts` (might want to remove this and `ts-node` depending on package)
- `test` for jest testing
- `test:watch` for watching files using jest
- `build` for building TypeScripts to `lib` folder
- `lint` runs `eslint`
- `format` runs `prettier`

# License

This project is licensed with the MIT license
