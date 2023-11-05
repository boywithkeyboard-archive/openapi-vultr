## vultr.js

> [!NOTE]  
> vultr.js is merely a preconfigured instance of [openapi-fetch](https://github.com/drwpow/openapi-typescript/tree/main/packages/openapi-fetch), based on the official OpenAPI schema by Vultr.

### Setup

#### Deno

```ts
import { Vultr } from 'https://esm.sh/vultr.js'
```

#### Node.js

```bash
npm i vultr.js
```

```ts
import { Vultr } from 'vultr.js'
```

### Usage

```ts
const client = new Vultr({
  token: '...'
})
```
