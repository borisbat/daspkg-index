# daspkg package index

Package registry for [daspkg](https://github.com/GaijinEntertainment/daScript), the daslang package manager.

## Packages

| Package | Description | URL |
|---------|-------------|-----|
| dasTelegram | Telegram Bot API bindings for daslang — zero-DOM JSON via sscan_json/sprint_json | [github.com/borisbat/dasTelegram](https://github.com/borisbat/dasTelegram) |
| daspkg-test-deps | Test package: module with dependencies | [github.com/borisbat/daspkg-test-deps](https://github.com/borisbat/daspkg-test-deps) |
| daspkg-test-pure | Test package: pure daslang module | [github.com/borisbat/daspkg-test-pure](https://github.com/borisbat/daspkg-test-pure) |
| daspkg-test-versions | Test package: module with version tags | [github.com/borisbat/daspkg-test-versions](https://github.com/borisbat/daspkg-test-versions) |

_4 package(s) registered._

## Adding a package

```
daspkg introduce github.com/user/repo
```

This validates the package manifest (`daspkg.json`) and creates a PR.
