# Awesome Jest [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> An awesome list of [Jest](https://facebook.github.io/jest/) packages and resources


## Contents

- [Packages](#packages)
  * [Matchers](#matchers)
  * [IDE](#ide)
  * [Linting](#linting)
  * [Runners](#runners)
  * [Environments](#environments)
  * [Snapshot](#snapshot)
  * [Migration](#migration)
  * [Library extensions](#library-extensions)
- [Resources](#resources)


## Packages

### Matchers

- [jest-extended](https://www.github.com/jest-community/jest-extended) Adds additional matchers to core API making it easy to test everything.
- [expect-more](https://github.com/JamieMason/expect-more/tree/master/packages/expect-more-jest) A huge library of test matchers for a range of common use-cases.
- [jest-axe](https://github.com/nickcolley/jest-axe) Custom Jest matcher for [aXe](https://axe-core.org/) for testing accessibility.

### IDE

- [vscode-jest](https://www.github.com/jest-community/vscode-jest) The optimal flow for Jest based testing in VS Code.

### Linting

- [eslint-plugin-jest](https://www.github.com/jest-community/eslint-plugin-jest) ESLint plugin for Jest.

### Runners

- [jest-runner-eslint](https://www.github.com/jest-community/jest-runner-eslint) ESLint runner for Jest.
- [jest-runner-mocha](https://github.com/rogeliog/jest-runner-mocha) Mocha runner for Jest.
- [jest-runner-prettier](https://github.com/keplersj/jest-runner-prettier) Prettier runner for Jest.

### Environments

- [jest-environment-webdriver](https://github.com/alexeyraspopov/jest-webdriver) custom environment for WebDriver integration.

### Snapshot

- [snapshot-diff](https://www.github.com/jest-community/snapshot-diff) Takes two values, and return their difference as a string, ready to be snapshotted with toMatchSnapshot(). Especially helpful when testing the difference between different React component states.
- [jest-snapshots-svg](https://www.github.com/jest-community/jest-snapshots-svg) Take a React component tree, and render it into an SVG.
- [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot) Take a snapshot test of an image buffer, and catch when the image changes over a threshold. Commonly used for visual regression testing.

### Migration

- [jest-codemods](https://github.com/skovhus/jest-codemods) Makes it easy to migrate from other test runner and frameworks to Jest.

### Library extensions

- [testdouble-jest](https://github.com/testdouble/testdouble-jest) Support for [testdouble.js](https://github.com/testdouble/testdouble.js) for users of Jest.
- [jest-puppe-shots](https://github.com/macku/jest-puppe-shots) A Jest plugin for creating screenshots of [React](https://reactjs.org/) components with a little help of [Puppeteer](https://github.com/GoogleChrome/puppeteer)


## Resources

- [Jest cheat sheet](https://github.com/sapegin/jest-cheat-sheet).


## Contribute

Contributions welcome! Read the [contribution guidelines](/CONTRIBUTING.md).


## License

[MIT](/LICENSE)
