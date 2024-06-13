# khulnasoft-json-schema

JSON schema of khulnasoft.yml files

[![npm version](https://img.shields.io/badge/khulnasoft-json-schema.svg)](https://img.shields.io/badge/js/khulnasoft-json-schema)

## Usage

### JSON Schema

#### As hosted URL

You can use the following URL for the current JSON schema file:

```
https://raw.githubusercontent.com/khulnasoft/khulnasoft-json-schema/master/src/schema.json
```

#### Import as file in Node

```js
const schema = require('khulnasoft-json-schema/dist/schema.json')
```

#### Usage with VSCode

Add the following to your settings:

```json
{
  "yaml.schemas": {
    "https://raw.githubusercontent.com/khulnasoft/khulnasoft-json-schema/master/src/schema.json":
      "khulnasoft.yml"
  }
}
```

### Typescript Definitions

```sh
yarn add khulnasoft-json-schema
```

```ts
import { KhulnasoftDefinition } from 'khulnasoft-json-schema'
```
