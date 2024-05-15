# prettier-config
pudon's prettier config

## Install

```sh
npm i -D @pudon/prettier-config
```

## Usage

In `package.json`:

```json
{
  "prettier": "@pudon/prettier-config"
}
```

In `prettier.config.js`:

```js
import config from '@pudon/prettier-config';

export default {
  ...config,
  semi: false,
};