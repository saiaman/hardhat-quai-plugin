# hardhat-quai-plugin

A hardhat plugin to handle solidityX compiler ( for beginning )

[Hardhat](https://hardhat.org) plugin example.

## Installation

<_A step-by-step guide on how to install the plugin_>

```bash
npm install hardhat-quai-plugin
```

Import the plugin in your `hardhat.config.js`:

```js
require("hardhat-quai-plugin");
```

Or if you are using TypeScript, in your `hardhat.config.ts`:

```ts
import "hardhat-quai-plugin";
```

## Configuration

This plugin extends the `HardhatUserConfig`'s `ProjectPathsUserConfig` object with an optional
`solidityx` field.

This is an example of how to set it:

```js
module.exports = {
  solidityx: {
    compiler_path: "PATH_TO_SOLC_COMPILER",
  },
};
```
