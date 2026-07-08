# Applied Energistics 2 Wireless Terminals 汉化资源包

[![Action](../../actions/workflows/release.yml/badge.svg)](../../actions/workflows/release.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)

一个面向 [Applied Energistics 2 Wireless Terminals（AE2WTLib）](https://github.com/Mari023/AE2WirelessTerminalLibrary) 的中文翻译资源包，该资源包属于 HappyMC Ember Project 系列

> 本资源包使用了生成式人工智能技术来协助翻译

## 覆盖范围

> [!IMPORTANT]
> 本资源包**仅覆盖 AE2WTLib 的游戏内指南（AE2WTLib Guide）部分**，也就是游戏中「AE2WTLib 指南书」里的说明文档
>
> 本资源包基于 [AE2WTLib 19.5.0](https://modrinth.com/mod/applied-energistics-2-wireless-terminals/version/19.5.0) 版本进行制作
>
> 本资源包仅兼容 1.21.1 版本

翻译内容对应仓库中 `assets/ae2/ae2guide/` 下的各篇指南文档，包括入门指引、AE2 机制说明、物品 / 方块 / 机器介绍以及示例装置等。

## 如何使用

### 方式一：直接下载（推荐）

前往仓库的 **[Releases](../../releases/latest)** 页面，下载最新版的 `HappyMC_Ember_TranslatePack_AE2WTLib-*.zip`，即可跳过下面的打包步骤，直接进行[安装](#安装)。

> Release 中的 zip 由 GitHub Actions 自动打包，结构已经符合要求，下载后无需解压即可使用。

### 方式二：自行打包

将 `assets` 文件夹连同 `pack.mcmeta`（见下）一起压缩成一个 `.zip` 文件。**注意：压缩包内的第一层必须直接是 `assets/` 和 `pack.mcmeta`，而不是再套一层项目文件夹。**

```
HappyMC_Ember_TranslatePack_AE2WTLib.zip
├── assets/
│   ├── ae2/
│   │   └── ae2guide/
│   │       └── ...（AE2 指南文档）
│   └── ae2wtlib/
│       └── ae2guide/
│           └── ...（AE2WTLib 指南文档）
└── pack.mcmeta
```

打包命令示例：

```bash
# Linux / macOS
zip -r HappyMC_Ember_TranslatePack_AE2WTLib.zip assets pack.mcmeta
```

```powershell
# Windows PowerShell
Compress-Archive -Path assets, pack.mcmeta -DestinationPath HappyMC_Ember_TranslatePack_AE2WTLib.zip
```

### 安装

1. 打开 Minecraft 存放资源包的文件夹：游戏内 **选项 → 资源包 → 打开资源包文件夹**（`.minecraft/resourcepacks/`）。
2. 把打包好的 `.zip` 文件（或直接把整个项目文件夹）放进该目录。
3. 回到游戏 **选项 → 资源包**，将本资源包从「可用」移动到「已选」一侧，点击「完成」。
4. 进入游戏，打开 AE2 指南书即可看到中文内容。

## 遇到问题？

如果你在使用过程中发现翻译错误、排版问题，或者资源包无法正常加载，欢迎到 GitHub 仓库提交 issue：

- 👉 [提交 Issue](../../issues/new/choose)

提交时请尽量按照 issue 模板填写游戏版本、模组版本、问题描述、截图和日志，方便我们更快定位问题。也欢迎直接提交 Pull Request 帮助改进翻译。

## 许可协议

本项目基于 [MIT License](./LICENSE) 开源。你可以自由使用、修改和分发，但请保留原始的版权与许可声明。

> 本资源包为非官方社区汉化，与 Applied Energistics 2 官方团队和 AE2WTLib 开发者无隶属关系。AE2 原始文档及 AE2WTLib 相关内容版权归其各自作者所有。
