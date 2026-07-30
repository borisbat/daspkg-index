# daspkg package index

Package registry for [daspkg](https://github.com/GaijinEntertainment/daScript), the daslang package manager.

## Package Index

| Package | Description | Install |
|---------|-------------|---------|
| [das-cards](#das-cards) | Vector playing card rendering — SVG-based triangle mesh... | `daspkg install das-cards` |
| [das-claude](#das-claude) | Typed bindings for the Anthropic Claude Messages API | `daspkg install das-claude` |
| [dasDuckDB](#dasDuckDB) | DuckDB bindings and SQL LINQ provider for daslang | `daspkg install dasDuckDB` |
| [dasImguiImplot](#dasImguiImplot) | ImPlot bindings for daslang | `daspkg install dasImguiImplot` |
| [dasImguiNodeEditor](#dasImguiNodeEditor) | imgui-node-editor bindings for daslang | `daspkg install dasImguiNodeEditor` |
| [dasPostgreSQL](#dasPostgreSQL) | PostgreSQL (libpq) bindings and SQL LINQ provider for das... | `daspkg install dasPostgreSQL` |
| [dasTelegram](#dasTelegram) | Telegram Bot API bindings for daslang — zero-DOM JSON v... | `daspkg install dasTelegram` |
| [dasVideo](#dasVideo) | Video playback for daslang (pl_mpeg / dav1d, royalty-free) | `daspkg install dasVideo` |
| [dasVulkan](#dasVulkan) | Vulkan bindings for daslang, generated from vk.xml | `daspkg install dasVulkan` |
| [daspkg-test-deps](#daspkg-test-deps) | Test package: module with dependencies | `daspkg install daspkg-test-deps` |
| [daspkg-test-pure](#daspkg-test-pure) | Test package: pure daslang module | `daspkg install daspkg-test-pure` |
| [daspkg-test-versions](#daspkg-test-versions) | Test package: module with version tags | `daspkg install daspkg-test-versions` |
| [minmaxheap](#minmaxheap) | Minmax heap implementation, see github for details on usage | `daspkg install minmaxheap` |

## Packages by Tag

**ai**: das-claude

**api**: das-claude, dasTelegram

**bot**: dasTelegram

**cards**: das-cards

**database**: dasDuckDB, dasPostgreSQL

**decode**: dasVideo

**duckdb**: dasDuckDB

**games**: das-cards

**gpu**: dasVulkan

**graphics**: das-cards, dasVulkan

**gui**: dasImguiImplot, dasImguiNodeEditor

**http**: das-claude

**imgui**: dasImguiImplot, dasImguiNodeEditor

**media**: dasVideo

**plot**: dasImguiImplot

**postgresql**: dasPostgreSQL

**sql**: dasDuckDB, dasPostgreSQL

**telegram**: dasTelegram

**test**: daspkg-test-deps, daspkg-test-pure, daspkg-test-versions

**video**: dasVideo

**vulkan**: dasVulkan

## Packages

### das-cards

Vector playing card rendering — SVG-based triangle mesh cards for OpenGL

- **Author:** borisbat
- **License:** LGPL-2.1
- **Tags:** graphics, games, cards
- **Updated:** 2026-06-11
- **Install:** `daspkg install das-cards`
- **URL:** [github.com/borisbat/dasCards](https://github.com/borisbat/dasCards)

---

### das-claude

Typed bindings for the Anthropic Claude Messages API

- **Author:** borisbat
- **License:** BSD-3-Clause
- **Tags:** ai, api, http
- **Min SDK:** 0.4
- **Updated:** 2026-04-20
- **Install:** `daspkg install das-claude`
- **URL:** [github.com/borisbat/dasAnthropic](https://github.com/borisbat/dasAnthropic)

---

### dasDuckDB

DuckDB bindings and SQL LINQ provider for daslang

- **Author:** borisbat
- **License:** MIT
- **Tags:** sql, database, duckdb
- **Updated:** 2026-07-04
- **Native:** yes (requires C/C++ toolchain)
- **Install:** `daspkg install dasDuckDB`
- **URL:** [github.com/borisbat/dasDuckDB](https://github.com/borisbat/dasDuckDB)

---

### dasImguiImplot

ImPlot bindings for daslang

- **Author:** borisbat
- **License:** MIT
- **Tags:** gui, imgui, plot
- **Updated:** 2026-07-02
- **Native:** yes (requires C/C++ toolchain)
- **Dependencies:** dasImgui
- **Install:** `daspkg install dasImguiImplot`
- **URL:** [github.com/borisbat/dasImguiImplot](https://github.com/borisbat/dasImguiImplot)

---

### dasImguiNodeEditor

imgui-node-editor bindings for daslang

- **Author:** borisbat
- **License:** MIT
- **Tags:** gui, imgui
- **Updated:** 2026-07-02
- **Native:** yes (requires C/C++ toolchain)
- **Dependencies:** dasImgui
- **Install:** `daspkg install dasImguiNodeEditor`
- **URL:** [github.com/borisbat/dasImguiNodeEditor](https://github.com/borisbat/dasImguiNodeEditor)

---

### dasPostgreSQL

PostgreSQL (libpq) bindings and SQL LINQ provider for daslang

- **Author:** borisbat
- **License:** MIT
- **Tags:** sql, database, postgresql
- **Updated:** 2026-07-05
- **Native:** yes (requires C/C++ toolchain)
- **Install:** `daspkg install dasPostgreSQL`
- **URL:** [github.com/borisbat/dasPostgreSQL](https://github.com/borisbat/dasPostgreSQL)

---

### dasTelegram

Telegram Bot API bindings for daslang — zero-DOM JSON via sscan_json/sprint_json

- **Author:** borisbat
- **License:** BSD-3-Clause
- **Tags:** telegram, bot, api
- **Updated:** 2026-04-20
- **Install:** `daspkg install dasTelegram`
- **URL:** [github.com/borisbat/dasTelegram](https://github.com/borisbat/dasTelegram)

---

### dasVideo

Video playback for daslang (pl_mpeg / dav1d, royalty-free)

- **Author:** borisbat
- **License:** MIT
- **Tags:** video, media, decode
- **Updated:** 2026-06-21
- **Native:** yes (requires C/C++ toolchain)
- **Install:** `daspkg install dasVideo`
- **URL:** [github.com/borisbat/dasVideo](https://github.com/borisbat/dasVideo)

---

### dasVulkan

Vulkan bindings for daslang, generated from vk.xml

- **Author:** borisbat
- **License:** MIT
- **Tags:** graphics, vulkan, gpu
- **Updated:** 2026-07-02
- **Native:** yes (requires C/C++ toolchain)
- **Install:** `daspkg install dasVulkan`
- **URL:** [github.com/borisbat/dasVulkan](https://github.com/borisbat/dasVulkan)

---

### daspkg-test-deps

Test package: module with dependencies

- **Author:** borisbat
- **Tags:** test
- **Updated:** 2026-06-11
- **Dependencies:** daspkg-test-pure
- **Install:** `daspkg install daspkg-test-deps`
- **URL:** [github.com/borisbat/daspkg-test-deps](https://github.com/borisbat/daspkg-test-deps)

---

### daspkg-test-pure

Test package: pure daslang module

- **Author:** borisbat
- **Tags:** test
- **Updated:** 2026-06-11
- **Install:** `daspkg install daspkg-test-pure`
- **URL:** [github.com/borisbat/daspkg-test-pure](https://github.com/borisbat/daspkg-test-pure)

---

### daspkg-test-versions

Test package: module with version tags

- **Author:** borisbat
- **Tags:** test
- **Updated:** 2026-06-11
- **Install:** `daspkg install daspkg-test-versions`
- **URL:** [github.com/borisbat/daspkg-test-versions](https://github.com/borisbat/daspkg-test-versions)

---

### minmaxheap

Minmax heap implementation, see github for details on usage

- **Author:** vi
- **Updated:** 2026-07-05
- **Install:** `daspkg install minmaxheap`
- **URL:** [github.com/JohnathanKG/minmaxheap](https://github.com/JohnathanKG/minmaxheap)

---

_13 package(s) registered._

## Adding a package

```
daspkg introduce github.com/user/repo
```

This validates the package manifest (`.das_package`) and creates a PR.
