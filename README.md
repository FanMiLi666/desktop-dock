# Desktop Dock

一个轻量的 macOS 桌面 Dock 工具，用来辅助个人桌面工作流。

[下载最新版](https://github.com/FanMiLi666/desktop-dock/releases/latest)

## 功能

- 菜单栏常驻运行，用来快速显示桌面或恢复窗口。
- 支持隐藏当前可见窗口，让桌面内容快速露出。
- 支持恢复之前隐藏的窗口，方便在桌面和工作窗口之间切换。
- 注册全局快捷键 `Control + Option + Command + D`，不用点菜单栏也能触发。
- 点击菜单栏图标可打开操作菜单，包含显示桌面、恢复窗口等常用动作。
- 会尝试跳过 Finder、Dock、系统弹窗、浮动窗口等不适合隐藏的系统窗口。

## 适用场景

- 桌面上放了常用文件或临时素材，需要频繁快速查看。
- 多窗口工作时，想一键清空视野，再一键恢复原来的窗口状态。
- 不想依赖 macOS 默认热角或复杂手势，希望用一个固定快捷键控制桌面。
- 做演示或录屏前，需要快速整理屏幕显示内容。

## 应用信息

- 名称：Desktop Dock
- 版本：0.1.0
- 系统要求：macOS 13.0+
- 架构：Apple Silicon arm64

## 使用方式

1. 从 [Releases](https://github.com/FanMiLi666/desktop-dock/releases/latest) 下载 zip。
2. 将 `Desktop Dock.app` 拖到 `Applications` 文件夹。
3. 双击打开应用。

## 说明

当前仓库保存的是已打包的 `.app` 应用包，不包含完整源码工程。由于需要控制其他应用窗口，首次使用可能需要在 macOS“系统设置 -> 隐私与安全性 -> 辅助功能”中授予权限。
