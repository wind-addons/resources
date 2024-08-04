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

1. Install [wind-addons/flemjoi](https://github.com/wind-addons/flemoji).
2. Run the following command to generate emojis from Fluent UI source:

   ```powershell
   flemoji -W 512 -H 512 --from=source\fluentui-emoji\assets --to=dist\discord-3d-emoji -T png
   ```
