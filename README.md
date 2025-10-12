# Config

> Shared configuration files

## Usage

```bash
npm i -D @kremalicious/config
```

### Biome

```json
// biome.json
{
  "extends": ["@kremalicious/config/biome"]
}
```

See https://biomejs.dev/guides/configure-biome/#share-a-configuration-file

### Prettier

```mjs
// .prettierrc.mjs
import sharedConfig from "@kremalicious/config/prettier"

/** @type {import("prettier").Config} */
export default {
  ...sharedConfig
}
```

See https://prettier.io/docs/en/configuration#sharing-configurations