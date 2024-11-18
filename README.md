# eslint-config-airbnb-ts-prettier

![License][license]

A modern, updated fork of [`eslint-config-airbnb-typescript-prettier`](https://github.com/toshi-toma/eslint-config-airbnb-typescript-prettier), combining Airbnb's ESLint rules with TypeScript and Prettier support.

This fork incorporates newer dependencies, and ensures compatibility with modern TypeScript and ESLint versions.

---

## Why this Fork?

The original repository appears unmaintained, with outdated dependencies and compatibility issues. This fork:
- Updates all dependencies to their latest versions.
- Ensures compatibility with modern versions of ESLint, TypeScript, and Prettier.


# How to use
Install `typescript`, `eslint` and `prettier`, `eslint-config-airbnb-ts-prettier` and put it into your `.eslintrc.js`.

```bash
$ npm install typescript eslint prettier eslint-config-airbnb-ts-prettier --save-dev
```

`.eslintrc.js`

```js
module.exports = {
  extends: "airbnb-ts-prettier"
};
```

## Features

- **Airbnb rules:** Industry-standard ESLint configuration for JavaScript, providing robust linting rules for clean and consistent code.
- **TypeScript support:** Fully compatible with TypeScript projects, ensuring type-safe linting.
- **Prettier integration:** Seamlessly integrates with Prettier for automated code formatting without conflicts.
- **Updated dependencies:** All dependencies are kept up to date, ensuring compatibility with the latest versions of ESLint, TypeScript, and Prettier.
- **React support:** Includes rules tailored for React and React Hooks.

## License

Open source [licensed as MIT](https://github.com/toshi-toma/eslint-config-airbnb-typescript-prettier/blob/master/LICENSE).

[npm-image]: https://img.shields.io/npm/v/eslint-config-airbnb-typescript-prettier.svg
[npm-url]: https://npmjs.org/package/eslint-config-airbnb-typescript-prettier
[license]: https://img.shields.io/npm/l/eslint-config-airbnb-typescript-prettier.svg
