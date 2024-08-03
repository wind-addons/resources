# 💎 Resources

Resource files used in Wind Addons development.

<details>
<summary>📖 Table of Contents</summary>

- [🛠️ Project Setup](#️-project-setup)
  - [Requirements](#requirements)
  - [Project Initialization](#project-initialization)
- [🔄 Updating Fluent UI Emojis](#-updating-fluent-ui-emojis)

</details>

## 🛠️ Project Setup

### Requirements

- Rust 1.80.0 or later

### Project Initialization

```powershell
git clone https://github.com/wind-addons/resources.git
git submodule update --init --recursive
```

## 🔄 Updating Fluent UI Emojis

Updating emoji PNG files with the latest fluentui-emojis
To update the emoji files, follow these steps:

```powershell
cd source/emoji/updater
.\update.bat
```
