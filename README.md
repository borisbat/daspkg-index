# daspkg package index

Package registry for [daspkg](https://github.com/GaijinEntertainment/daScript), the daslang package manager.

## Adding a package

1. Fork this repo
2. Add your package to `packages.json`
3. Open a PR

## Format

```json
{
  "package-name": {
    "url": "github.com/owner/repo",
    "description": "Short description"
  }
}
```

The `url` is without `https://` prefix. daspkg prepends it automatically.
