<h1 align="center">@sveltek/tsconfig</h1>

<p align="center">Sveltek's config for TypeScript.</p>

<br>

## Installation

```sh
pnpm add -D @sveltek/tsconfig
```

## Usage

```ts
// tsconfig.json

{
  "extends": "@sveltek/tsconfig"
}
```

## Custom Setup

```ts
// tsconfig.json

{
  "extends": "@sveltek/tsconfig",
  "compilerOptions": {
    "baseUrl": "./",
    "paths": {
      "@": ["./src"],
      "@/*": ["./src/*"]
    }
  }
}
```

## License

Developed in 🇭🇷 Croatia, © Sveltek.

Released under the [MIT](LICENSE.txt) license.
