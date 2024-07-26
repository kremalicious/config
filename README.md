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

### Prettier (deprecated, use Biome instead)

```json
// .prettierrc
"@kremalicious/config/prettier"
```

See https://prettier.io/docs/en/configuration#sharing-configurations