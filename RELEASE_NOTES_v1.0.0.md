# Mac Performance Monitor v1.0.0 / 性能检测 v1.0.0

## English

First public DMG release of Mac Performance Monitor, a native macOS menu bar tool for checking and recording device performance.

### Highlights

- Live menu bar monitoring for CPU, memory, disk, network speed, thermal state, battery health, and disk temperature.
- macOS-style glass desktop widget with adjustable size and transparency.
- Separate built-in SSD and external drive capacity/temperature display.
- External APFS shared-container handling with partition count and total usage progress.
- Local performance logs with user-selected metrics.
- Custom refresh interval, process view, history charts, login item support, and multi-language UI.

### Disk Temperature

Disk temperature uses `smartctl` when available. Install smartmontools for best support:

```sh
brew install smartmontools
```

### Install

Download `Mac-Performance-Monitor-v1.0.0.dmg`, open it, and drag `性能检测.app` to Applications. If macOS blocks the first launch because the app is not notarized, right-click the app and choose **Open**.

### SHA-256

`e1c41b961adfcf4db9600b34a8894c423acf06cae29ac2b4a68a1b96eed1fefb`

## 中文

这是 Mac Performance Monitor / 性能检测 的第一个公开 DMG 版本。它是一个原生 macOS 菜单栏工具，用于查看并记录电脑性能数据。

### 重点功能

- 菜单栏实时显示 CPU、内存、硬盘、网速、系统温度状态、电池健康度和硬盘温度。
- macOS 风格玻璃桌面小组件，支持调整尺寸和透明度。
- 本地 SSD 与外接硬盘的容量、温度分开显示。
- 支持外接 APFS 共享容器，显示分区数量和总占用进度。
- 支持按用户选择记录本地性能日志。
- 支持刷新间隔设置、进程监控、历史曲线、开机自启动和多语言界面。

### 硬盘温度

硬盘温度读取依赖可用的 `smartctl`。建议安装 smartmontools 获得更完整的硬盘温度支持：

```sh
brew install smartmontools
```

### 安装

下载 `Mac-Performance-Monitor-v1.0.0.dmg`，打开后将 `性能检测.app` 拖入 Applications。如果首次启动时 macOS 因未公证而阻止打开，请右键应用并选择 **Open / 打开**。

### SHA-256

`e1c41b961adfcf4db9600b34a8894c423acf06cae29ac2b4a68a1b96eed1fefb`
