# CodeMux-App

CodeMux 的公开发布仓库。

CodeMux 是一个面向 Codex Desktop 的桌面增强工具，用来把 Codex 连接到本地 CodeMux 服务和你的模型中转能力，让安装、启动、连接、增强、中文界面、插件能力、历史管理、完全授权修复和后续更新都更方便。

## CodeMux 可以做什么

- 为 Codex 引入 Gemini 顾问能力，在不打断主流程的前提下，自动完成任务分流与模型切换，让 UI、样式、设计理解等工作获得更合适的处理体验。
- Gemini Advisor 失败时自动回退，不中断原本使用。
- 支持全自动 / 手动 Gemini 顾问模式，可按日常使用习惯切换。
- 支持测试一段提示词会走普通 GPT 还是 UI Advisor 路由。
- 支持过滤 Codex 内部标题生成、记忆整理、上下文压缩等请求，避免误触发 Gemini 顾问。

## 模型与图片增强

- 提供 `gpt-image-2` 模型入口。
- 自动把图片生成请求改写到 `gpt-image-2`。
- 同步 Codex 本地模型目录，让模型列表可显示 `gpt-image-2`。
- 支持 Codex 审查 / Review 任务模型切换，可按需将审查任务改走 `gpt-5.5`。
- 支持 GPT 主流程与 Gemini 顾问之间的模型映射和分组配置。

## Codex 历史管理

- 支持扫描并调出 Codex 本机历史记录。
- 支持修复换 Key / 换登录方式后历史不显示的问题。
- 支持导出 Codex 历史会话。
- 支持导入 Codex 历史会话。
- 支持删除选中的历史会话。
- 支持重建 Codex 历史索引。

## 插件增强

- 支持保存插件增强。
- 支持插件入口、插件市场源和插件启用项的持久化增强。
- 支持内置 OpenAI curated 插件资源。
- 支持安装 early preload，增强 CodeMux 与 Codex 的集成。
- 安装增强后，可在 Codex 内显示 CodeMux 控制入口与自动 / 手动切换Gemini入口。
- 支持插件登录兼容处理。
- 支持在 Codex 内部显示常用控制入口。

## Codex 维护能力

- 支持开启 Codex `/goal` 目标模式，适合长流程任务、持续推进、分阶段完成，也更适合在模型繁忙或短时波动时继续保持任务执行。
- 支持一键下载安装 Codex 桌面版。
- 支持检测 Codex 安装环境。
- 支持卸载 Codex 桌面版。
- 支持清理 Codex 残留文件。
- 支持恢复 Codex 配置和程序备份。
- 支持 Windows 上修复 Codex “完全授权 / Full access” 不可选的问题。
- 支持安装后启用 Codex 中文界面。
- 中文界面支持官方中文优先，官方未覆盖时可使用补漏翻译。

## 界面与体验

- 支持中文 / English 界面语言切换。
- 支持深色 / 浅色主题。
- 支持任务结束提示音，可调音量、试听、选择内置音效或本地音频文件。
- 支持托盘后台运行。
- 支持 CodeMux 与 Codex 版本信息查看。
- 支持后续版本更新检查。

<img width="1086" height="753" alt="image" src="https://github.com/user-attachments/assets/27de7b14-3084-431b-b910-12d7e287ecdb" />


## 下载

请在本仓库的 Releases 页面下载最新版本。

或请点击这里获取最新版本：

- [最新版发布页](https://github.com/aicorehub1/CodeMux-App/releases/latest)

Windows 当前可下载：

- 安装版
- 便携版

macOS：

- CodeMux 已按 Windows + macOS 双平台方向适配
- macOS 安装包可后续单独补充发布

## 说明

- 这个仓库只用于公开发布安装包和版本说明。
- 当前公开发布内容以 Windows 版本为主。
- Windows 支持安装版和便携版。
- macOS 版本如发布，将以 `.dmg` 安装包形式单独提供。
- Windows 上的“完全授权 / Full access 修复”会触发一次管理员授权，用于完成 Codex sandbox setup。
- macOS 不使用 Windows sandbox setup，相关 Windows 专属修复入口不会在 macOS 中显示。
