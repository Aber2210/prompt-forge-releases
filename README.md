# PromptForge Releases

[PromptForge](https://github.com/Aber2210/prompt-forge) 的发布产物与更新源。

PromptForge 是一款现代化的开源提示词（Prompt）管理器：本地优先、零后端，支持多类型提示词、云端链接导入、树形分组、中文全文检索、版本控制、WebDAV 多设备同步，并可打包为免安装桌面应用。

## 下载

本仓库的 [Releases](../../releases) 提供**免安装绿色版**（Windows exe，单文件）。

## 更新方式

手动下载最新 Release 的 `prompt-forge.exe`，替换旧文件即可。

- 数据跟随 exe 同级的 `data/` 目录，**覆盖 exe 不影响已有数据**。
- 应用内自动更新（`tauri-plugin-updater`）尚未接入，当前为手动更新。

## 说明

- **源码**：托管在私有仓库 [Aber2210/prompt-forge](https://github.com/Aber2210/prompt-forge)（需访问权限）。
- **代码签名**：当前 exe 未做代码签名，Windows SmartScreen 可能提示「未知发布者」，属已知项。
- **License**：[MIT](./LICENSE) © 2026 PromptForge Contributors
