<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/light.svg">
  <img src="assets/light.svg" alt="Zz-0005" width="100%">
</picture>

</div>

<br>

## 关于这里

2026 年 10 月建号。这里只放做完的东西和写下来的判断,不堆形容词。

## 项目

### 2048 · v2.0.0

打开即玩的 2048：响应式、键盘 + 触摸、零依赖零构建，另有一个单文件版本可以存进手机离线玩。规格来自下面的 [PRD-2048 v2.0](#需求文档)。

| | |
|:--|:--|
| **在线试玩** | [zz-0005.github.io/2048](https://zz-0005.github.io/2048/) |
| **源码** | [Zz-0005/2048](https://github.com/Zz-0005/2048) |
| **离线单文件** | [2048-standalone.html](https://github.com/Zz-0005/2048/blob/main/2048-standalone.html)（存进手机即可离线玩） |
| **发布说明** | [release-v2.0.0.md](https://github.com/Zz-0005/2048/blob/main/docs/release-v2.0.0.md) |
| **代码审阅记录** | [code-review-2026-10-20.md](https://github.com/Zz-0005/2048/blob/main/docs/code-review-2026-10-20.md) |

需求按 PRD 的验收条目逐条实现，证据留在仓库里：112 项自动化测试（规则引擎、状态机、存储、浏览器 E2E）、axe 可访问性审计 0 条 serious/critical、截图像素校验 66/66、每步耗时 p75 约 2–3ms。发布说明里写了刻意不做的部分（排行榜、账号、云存档）和三条没能验证的事（NVDA/VoiceOver 人工走查、Firefox/Safari、真机触摸惯性）。

## 需求文档

### PRD-2048 v2.0（批准稿）

| 字段 | 内容 |
|:--|:--|
| 文档 ID | PRD-2048 |
| 版本 | v2.0 · 已批准（Approved），可进入开发 |
| 范围 | 响应式 Web；桌面键盘 + 移动端触摸；无账号、无服务端排行榜 |
| 默认语言 | zh-CN |
| 参考实现 | [gabrielecirulli/2048](https://github.com/gabrielecirulli/2048)（MIT） |
| 当前进度 | AT-001～AT-018、NFR-001～NFR-006 逐条对照；其中 AT-013（当前局恢复）按 PRD `D-003` 默认项未交付，逐项明细见发布说明 |

原件与可读版本（同一份文档，三种打开方式）：

| 形式 | 打开 |
|:--|:--|
| 网页版（推荐，浏览器里直接读） | **https://zz-0005.github.io/2048/docs/prd.html** |
| Markdown（GitHub 内渲染） | [docs/PRD-2048-v2.0.md](https://github.com/Zz-0005/2048/blob/main/docs/PRD-2048-v2.0.md) |
| 原件下载（.docx, 55 KB） | [**下载 PRD-2048-v2.0.docx**](https://github.com/Zz-0005/2048/raw/main/docs/PRD-2048-v2.0.docx) |

## 这里以后会有什么

| | |
|:--|:--|
| **项目** | 做完的东西,不论大小 |
| **笔记** | 踩过的坑,和想明白的事 |
| **工具** | 自己用得上、别人也可能用得上的脚本 |

## 现在

第一个项目上线了,就是上面那个 2048。它从 PRD 到实现到验证的记录都在仓库里，没有留在本地。

<br>

<div align="center">
<sub>© 2026 Zz-0005</sub>
</div>
