# warning: 
Copied from `only-allow` package, it only used in study
---

# enn-only-allow

> Force a specific package manager to be used on a project

## Usage

Add a `preinstall` script to your project's `package.json`.

If you want to force [npm](https://docs.npmjs.com/cli/npm), add:

```json
{
  "scripts": {
    "preinstall": "npx only-allow npm"
  }
}
```

If you want to force [cnpm](https://npmmirror.com/), add:

```json
{
  "scripts": {
    "preinstall": "npx only-allow cnpm"
  }
}
```

If you want to force [pnpm](https://pnpm.js.org/), add:

```json
{
  "scripts": {
    "preinstall": "npx only-allow pnpm"
  }
}
```

If you want to force [yarn](https://yarnpkg.com/), add:

```json
{
  "scripts": {
    "preinstall": "npx only-allow yarn"
  }
}
```

## License

[MIT](LICENSE)
