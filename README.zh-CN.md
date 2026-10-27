# Lobster · Prism

**一抹珊瑚暖色，点亮静谧的蓝色夜晚。**

[![发行附件下载量](https://img.shields.io/github/downloads/EllisMorrow/tine-theme-lobster-prism/total?label=release%20downloads)](https://github.com/EllisMorrow/tine-theme-lobster-prism/releases)

[English](README.md) · [下载 theme.json](https://github.com/EllisMorrow/tine-theme-lobster-prism/releases/latest/download/theme.json)

Lobster · Prism 以 Lobster 预设为视觉参考，配对浅色与深色阅读色板，并独立适配 Tine 的背景、链接和高亮。

### 深色模式

![Lobster · Prism 深色模式实拍](docs/lobster-dark.png)

### 浅色模式

![Lobster · Prism 浅色模式实拍](docs/lobster-light.png)

*用户测试后提供的 Windows 实机截图，两套配色均实际包含在同一个主题包中。*

## 安装

1. 下载 [theme.json](https://github.com/EllisMorrow/tine-theme-lobster-prism/releases/latest/download/theme.json)。
2. 在 Tine 打开 **设置 → 外观 → 主题包 → 选择 theme.json**，选择下载的文件。
3. 点击 **使用颜色**，选择 **浅色、深色或跟随系统**。

需要主题 API **0.2** 支持。原有 `logseq/custom.css` 和设备强调色可能影响效果；主题只负责 API 支持的颜色，不包含额外字体、布局或任务标记样式。

## 配色

| 角色 | 浅色 | 深色 |
| --- | --- | --- |
| 主背景 | `#eff1f5` | `#111827` |
| 侧栏 | `#e3e6ed` | `#111827` |
| 正文 | `#35353b` | `#e4e4e7` |
| 标题 | `#35353b` | `#e4e4e7` |
| 强调色 | `#ff5c5c` | `#ff5c5c` |
| 链接 | `#ac3f3f` | `#ff5c5c` |
| 标签 | `#ac3f3f` | `#ff5c5c` |
| 高亮底色 | `#f1dfe3` | `#2e202d` |

## 验证情况

通过官方主题格式检查；浏览器样例检查了两套完整变量、模式切换及指定颜色组合。用户提供了上方 Windows 明暗实机截图，展示公开欢迎页面上的标题、正文、层级、链接、标签、行内代码和引用区域。高亮、选中操作、设置状态和其它平台未由这些截图覆盖，不据此宣称全部路径均已验证。

## 来源与边界

视觉参考：[Codex Lobster appearance preset](https://learn.chatgpt.com/docs/reference/settings#appearance)，`installed version 26.1021.3705`。本独立编写的适配采用 MIT 许可；详见 [许可说明](LICENSE)。从本机 Codex 预设定义中读取部分颜色数值，并独立映射到 Tine；不分发 Codex 源代码或资源。原参考只有单模式时，另一模式为独立生成的配色，用户已提供两种模式的截图；原始上游来源和署名仍需核对。

独立社区适配由 EllisMorrow 完成，使用 AI 辅助开发。不分发 Codex 程序代码、标志或附带资源，不代表相关项目或 OpenAI 的官方产品，也不承诺与 Codex 像素级一致。具体映射和验证边界见 [适配说明](docs/adaptation.md)。

顶部徽标统计 GitHub Release 附件累计下载量，不代表安装人数。可在本仓库反馈问题，附版本、系统、模式及不包含私人内容的截图。
