# ToastBlocker

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![LSPosed](https://img.shields.io/badge/LSPosed-Module-green.svg)](https://github.com/LSPosed/LSPosed)

一款基于 LSPosed 框架的 Xposed 模块，用于拦截指定应用的系统 Toast 弹窗。

## 源码仓库

[👉 查看 GitHub 源码](https://github.com/h465855hgg/toastblocker)

## 功能特性

- 选择性拦截特定应用的 Toast 通知
- 轻量级，无额外资源占用

## 环境要求

- Android 7.0+ (API 24)
- [LSPosed 框架](https://github.com/LSPosed/LSPosed)

## 快速开始

1. **安装模块**  
   下载并安装 APK

2. **激活模块**  
   打开 LSPosed 管理器，确认模块已启用

3. **配置作用域**  
   进入模块设置，选择需要拦截 Toast 的目标应用

4. **重启生效**  
   强制停止目标应用后重新打开，验证 Toast 是否被拦截

## 注意事项

- 仅拦截系统 Toast，不影响应用内自定义弹窗
- 部分应用可能使用非标准 Toast 实现，拦截可能失效

## 许可证

[MIT License](LICENSE)
