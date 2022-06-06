# @deniszola/package

This is a simple npm package that demonstrates the [GitHub Package Registry](https://github.com/features/package-registry).

## Installation

Before installing, make sure to authenticate with GitHub Package Registry or to use a `.npmrc` file. See "[Configuring npm for use with GitHub Package Registry](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-npm-registry#authenticating-to-github-packages)."

`$ npm install @deniszola/package`

Or add this package to your `package.json` file:

```json
"dependencies": {
  "@deniszola/package": "2.0.0"
}
```

## Usage

```javascript
const helloWorld = require("@deniszola/package");

helloWorld(); // Hello World from @deniszola/package!
```
