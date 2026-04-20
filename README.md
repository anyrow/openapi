# Anyrow OpenAPI Spec

[![OpenAPI 3.1](https://img.shields.io/badge/OpenAPI-3.1-green)](https://spec.openapis.org/oas/v3.1.0)
[![MIT License](https://img.shields.io/badge/license-MIT-blue)](./LICENSE)

The public OpenAPI 3.1 specification for the [Anyrow](https://anyrow.ai) API.

## Hosted spec

The spec is always available at:

```
https://anyrow.ai/openapi.json
```

## Using this spec

### Postman / Insomnia

Import directly from the hosted URL: `https://anyrow.ai/openapi.json`

### Scalar / Swagger UI

```html
<script
  id="api-reference"
  data-url="https://anyrow.ai/openapi.json"
  src="https://cdn.jsdelivr.net/npm/@scalar/api-reference"></script>
```

### Code generation

```bash
npx @openapitools/openapi-generator-cli generate \
  -i https://anyrow.ai/openapi.json \
  -g typescript-fetch \
  -o ./anyrow-client

npx openapi-typescript https://anyrow.ai/openapi.json -o ./anyrow.d.ts
```

## Official SDKs

- [TypeScript/JavaScript](https://github.com/anyrow/sdk-typescript)
- [Go](https://github.com/anyrow/sdk-go)
- [Python](https://github.com/anyrow/sdk-python)
- [Rust](https://github.com/anyrow/sdk-rust)
- [CLI](https://github.com/anyrow/cli)

## License

MIT — see [LICENSE](./LICENSE).
