# daspkg package index

Package registry for [daspkg](https://github.com/GaijinEntertainment/daScript), the daslang package manager.

## Module Index

| Module | Package | Install |
|--------|---------|--------|
| `anthropic` | das-claude | `daspkg install github.com/borisbat/dasAnthropic` |
| `telegram` | dasTelegram | `daspkg install github.com/borisbat/dasTelegram` |
| `test_deps` | daspkg-test-deps | `daspkg install github.com/borisbat/daspkg-test-deps` |
| `test_pure` | daspkg-test-pure | `daspkg install github.com/borisbat/daspkg-test-pure` |
| `test_versions` | daspkg-test-versions | `daspkg install github.com/borisbat/daspkg-test-versions` |

## Packages by Tag

**a**: das-claude, dasTelegram

**d**: dasTelegram

**e**: dasTelegram

**g**: das-claude

**l**: das-claude

## Packages

### das-claude

Typed bindings for the Anthropic Claude Messages API

- **Author:** borisbat
- **License:** BSD-3-Clause
- **Modules:** `anthropic`
- **Tags:** l, g, a
- **Min SDK:** 0.4
- **Install:** `daspkg install github.com/borisbat/dasAnthropic`
- **URL:** [github.com/borisbat/dasAnthropic](https://github.com/borisbat/dasAnthropic)

---

### dasTelegram

Telegram Bot API bindings for daslang — zero-DOM JSON via sscan_json/sprint_json

- **Author:** borisbat
- **License:** BSD-3-Clause
- **Modules:** `telegram`
- **Tags:** e, a, d
- **Install:** `daspkg install github.com/borisbat/dasTelegram`
- **URL:** [github.com/borisbat/dasTelegram](https://github.com/borisbat/dasTelegram)

---

### daspkg-test-deps

Test package: module with dependencies

- **Author:** borisbat
- **Modules:** `test_deps`
- **Tags:** 
- **Dependencies:** daspkg-test-pure
- **Install:** `daspkg install github.com/borisbat/daspkg-test-deps`
- **URL:** [github.com/borisbat/daspkg-test-deps](https://github.com/borisbat/daspkg-test-deps)

---

### daspkg-test-pure

Test package: pure daslang module

- **Author:** borisbat
- **Modules:** `test_pure`
- **Tags:** 
- **Install:** `daspkg install github.com/borisbat/daspkg-test-pure`
- **URL:** [github.com/borisbat/daspkg-test-pure](https://github.com/borisbat/daspkg-test-pure)

---

### daspkg-test-versions

Test package: module with version tags

- **Author:** borisbat
- **Modules:** `test_versions`
- **Tags:** 
- **Install:** `daspkg install github.com/borisbat/daspkg-test-versions`
- **URL:** [github.com/borisbat/daspkg-test-versions](https://github.com/borisbat/daspkg-test-versions)

---

_5 package(s) registered._

## Adding a package

```
daspkg introduce github.com/user/repo
```

This validates the package manifest (`.das_package`) and creates a PR.
