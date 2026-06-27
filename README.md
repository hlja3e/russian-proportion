# Russian Proportion 🇷🇺

[![Forge](https://img.shields.io/badge/Forge-1.20.1-orange)](https://files.minecraftforge.net/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![Client Side](https://img.shields.io/badge/Side-Client%20Only-blue)](#)

**Force custom aspect ratio screen stretching — Russian style!**

Inspired by the Russian gaming tradition of 4:3 aspect ratio, this mod lets you lock Minecraft's rendering to any aspect ratio of your choice, regardless of window size.

## ✨ Features

- **Configurable aspect ratio** — default 4:3, set any ratio (16:9, 16:10, 21:9, 1:1...)
- **Toggle on/off** — enable/disable in-game via config file
- **Client-side only** — works in singleplayer and multiplayer, no server install needed
- **Zero dependencies** — just Forge 1.20.1

## 📦 Installation

1. Install [Minecraft Forge 1.20.1](https://files.minecraftforge.net/)
2. Download `russianproportion-x.x.x.jar` from [Releases](https://github.com/mirage/russian-proportion/releases)
3. Place the JAR in your `mods` folder
4. Launch Minecraft!

## ⚙️ Configuration

Config file: `config/russianproportion/russianproportion-common.toml`

```toml
[general]
    # Enable custom aspect ratio stretching
    enable = true
    # Target aspect ratio (width:height)
    # Examples: "4:3", "16:9", "16:10", "21:9"
    targetRatio = "4:3"
```

Changes take effect immediately — no restart needed.

## 🛠️ Building from Source

```bash
./gradlew clean build
```

Output JAR will be in `build/libs/`.

## 📄 License

MIT © Mirage

---

# 俄式比例 🇷🇺

**强制自定义宽高比画面拉伸 — 俄式风格！**

受俄式 4:3 比例游戏传统启发，本模组允许你将 Minecraft 渲染锁定为任意宽高比。

## ✨ 特性

- **可配置宽高比** — 默认 4:3，可设任意比例
- **开关控制** — 通过配置文件随时启用/禁用
- **纯客户端** — 单人/多人均有效，无需服务端安装
- **零依赖** — 仅需 Forge 1.20.1

## ⚙️ 配置

配置文件：`config/russianproportion/russianproportion-common.toml`

```toml
[general]
    enable = true        # 是否启用
    targetRatio = "4:3"  # 目标宽高比
```

修改后立即生效，无需重启。
