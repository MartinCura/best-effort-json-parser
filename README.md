# best-effort-json-parser

Parse incomplete json text in best-effort manner

[![npm Package Version](https://img.shields.io/npm/v/best-effort-json-parser)](https://www.npmjs.com/package/best-effort-json-parser)
[![Minified Package Size](https://img.shields.io/bundlephobia/min/best-effort-json-parser)](https://bundlephobia.com/package/best-effort-json-parser)
[![Minified and Gzipped Package Size](https://img.shields.io/bundlephobia/minzip/best-effort-json-parser)](https://bundlephobia.com/package/best-effort-json-parser)

## Example
```typescript
import { parse } from 'best-effort-json-parser'

let data = parse(`[1, 2, {"a": "apple`)
console.log(data) // [1, 2, { a: 'apple' }]
```

More examples see [parse.spec.ts](./src/parse.spec.ts)

## License
This is free and open-source software (FOSS) with
[BSD-2-Clause License](./LICENSE)
