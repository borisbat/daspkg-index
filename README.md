# daspkg package index

Package registry for [daspkg](https://github.com/GaijinEntertainment/daScript), the daslang package manager.

## Package Index

| Package | Description | Install |
|---------|-------------|---------|
| [das-claude](#das-claude) | Typed bindings for the Anthropic Claude Messages API | `daspkg install das-claude` |
| [dasImgui](#dasImgui) | Dear ImGui bindings for daslang | `daspkg install dasImgui` |
| [dasImguiNodeEditor](#dasImguiNodeEditor) | imgui-node-editor bindings for daslang | `daspkg install dasImguiNodeEditor` |
| [dasTelegram](#dasTelegram) | Telegram Bot API bindings for daslang — zero-DOM JSON v... | `daspkg install dasTelegram` |
| [daspkg-test-deps](#daspkg-test-deps) | Test package: module with dependencies | `daspkg install daspkg-test-deps` |
| [daspkg-test-pure](#daspkg-test-pure) | Test package: pure daslang module | `daspkg install daspkg-test-pure` |
| [daspkg-test-versions](#daspkg-test-versions) | Test package: module with version tags | `daspkg install daspkg-test-versions` |

## Packages by Tag

**ai**: das-claude

**api**: das-claude, dasTelegram

**bot**: dasTelegram

**gui**: dasImgui, dasImguiNodeEditor

**http**: das-claude

**imgui**: dasImgui, dasImguiNodeEditor

**telegram**: dasTelegram

**test**: daspkg-test-deps, daspkg-test-pure, daspkg-test-versions

## Packages

### das-claude

Typed bindings for the Anthropic Claude Messages API

- **Author:** borisbat
- **License:** BSD-3-Clause
- **Tags:** ai, api, http
- **Min SDK:** 0.4
- **Install:** `daspkg install das-claude`
- **URL:** [github.com/borisbat/dasAnthropic](https://github.com/borisbat/dasAnthropic)

---

### dasImgui

Dear ImGui bindings for daslang

- **Author:** borisbat
- **License:** MIT
- **Tags:** gui, imgui
- **Native:** yes (requires C/C++ toolchain)
- **Install:** `daspkg install dasImgui`
- **URL:** [github.com/borisbat/dasImgui](https://github.com/borisbat/dasImgui)

---

### dasImguiNodeEditor

imgui-node-editor bindings for daslang

- **Author:** borisbat
- **License:** MIT
- **Tags:** gui, imgui
- **Native:** yes (requires C/C++ toolchain)
- **Dependencies:** dasImgui
- **Install:** `daspkg install dasImguiNodeEditor`
- **URL:** [github.com/borisbat/dasImguiNodeEditor](https://github.com/borisbat/dasImguiNodeEditor)

---

### dasTelegram

Telegram Bot API bindings for daslang — zero-DOM JSON via sscan_json/sprint_json

- **Author:** borisbat
- **License:** BSD-3-Clause
- **Tags:** telegram, bot, api
- **Install:** `daspkg install dasTelegram`
- **URL:** [github.com/borisbat/dasTelegram](https://github.com/borisbat/dasTelegram)

---

### daspkg-test-deps

Test package: module with dependencies

- **Author:** borisbat
- **Tags:** test
- **Dependencies:** daspkg-test-pure
- **Install:** `daspkg install daspkg-test-deps`
- **URL:** [github.com/borisbat/daspkg-test-deps](https://github.com/borisbat/daspkg-test-deps)

---

### daspkg-test-pure

Test package: pure daslang module

- **Author:** borisbat
- **Tags:** test
- **Install:** `daspkg install daspkg-test-pure`
- **URL:** [github.com/borisbat/daspkg-test-pure](https://github.com/borisbat/daspkg-test-pure)

---

### daspkg-test-versions

Test package: module with version tags

- **Author:** borisbat
- **Tags:** test
- **Install:** `daspkg install daspkg-test-versions`
- **URL:** [github.com/borisbat/daspkg-test-versions](https://github.com/borisbat/daspkg-test-versions)

---

_7 package(s) registered._

## Adding a package

```
daspkg introduce github.com/user/repo
```

This validates the package manifest (`.das_package`) and creates a PR.
