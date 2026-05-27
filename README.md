# Mac Performance Monitor / 性能检测

**A native macOS menu bar performance monitor with a glass desktop widget, local logs, and disk temperature tracking.**

**原生 macOS 菜单栏性能监控工具，支持玻璃桌面小组件、本地日志和硬盘温度检测。**

## Download / 下载

Download the latest DMG from [GitHub Releases](https://github.com/dt12e0/mac-performance-monitor/releases/latest).

请前往 [GitHub Releases](https://github.com/dt12e0/mac-performance-monitor/releases/latest) 下载最新版 DMG。

## Key Features / 主要功能

- **Menu bar live monitor**: CPU, memory, disk, network speed, thermal state, battery health, and disk temperature.
- **Desktop glass widget**: Adjustable desktop widget with macOS-style translucent glass UI.
- **External drive support**: Monitor external SSD/HDD capacity and temperature separately from the built-in SSD.
- **Multi-disk display**: Detect multiple disks and APFS shared containers, with partition count and usage progress.
- **Local logging**: Record selected performance metrics to local text, CSV, or JSONL logs.
- **Custom refresh interval**: Choose how often the app updates device performance data.
- **Process and history views**: Optional process monitoring and performance history charts.
- **Multi-language UI**: Chinese, Japanese, English, and Korean, with automatic system-language detection.
- **Login item support**: Optional launch at startup.
- **Lightweight native app**: Built with SwiftUI for macOS.

## 中文功能介绍

- **菜单栏实时监控**：CPU、内存、硬盘、网速、系统温度状态、电池健康度、硬盘温度。
- **桌面玻璃小组件**：支持调整尺寸和透明度，贴近 macOS 玻璃材质风格。
- **外接硬盘支持**：本地 SSD 和外接 SSD/HDD 的容量、温度分开显示。
- **多硬盘兼容**：支持多个硬盘、APFS 共享容器、分区数量和占用进度显示。
- **本地日志记录**：可按用户选择记录相关性能数据到本地日志文件。
- **刷新频率设置**：用户可以自定义设备数据刷新间隔。
- **进程与历史记录**：可选开启进程监控和性能历史曲线。
- **四国语言界面**：中文、日语、英语、韩语，默认自动跟随系统语言。
- **开机自启动**：支持设置为登录后自动启动。
- **原生轻量应用**：SwiftUI 构建，适合长期挂在菜单栏使用。

## Disk Temperature Notes / 硬盘温度说明

Disk temperature reading uses `smartctl` when available. For best temperature support, install smartmontools:

硬盘温度读取会优先使用 `smartctl`。如需更完整的硬盘温度支持，建议安装 smartmontools：

```sh
brew install smartmontools
```

Some internal Apple SSDs or external drives may not expose temperature data through SMART. In that case, the app will show that the temperature is unavailable.

部分 Apple 内置 SSD 或外接硬盘可能不会通过 SMART 暴露温度数据，此时软件会显示未检测到温度。

## Installation / 安装方式

1. Download `性能检测.dmg` from the latest release.
2. Open the DMG and drag `性能检测.app` into Applications.
3. Launch the app from Applications.
4. If macOS blocks the first launch because the app is not notarized, right-click the app and choose **Open**.

## Tags / 标签

`macOS`, `menu bar app`, `performance monitor`, `CPU monitor`, `memory monitor`, `disk monitor`, `network speed`, `disk temperature`, `external SSD`, `SMART`, `smartctl`, `SwiftUI`, `desktop widget`, `battery health`, `system monitor`
