# qqhkx2027

## 秋秋工具箱

围绕「秋秋很开心」内容创作流程整理的一组可复用工具与 Skills。

> A small open-source toolkit for writing, formatting, visual production, knowledge capture, and personal workbench building.

## 创作闭环

```text
写文章 → 公众号排版 → 生成封面 → 制作信息图
   ↓                         ↓
知识沉淀 ←────────────── 日常工作台
```

## 项目导航

| 项目 | 用途 | 类型 | 在线 / 仓库 |
| --- | --- | --- | --- |
| [qiuqiu-wechat-editor](https://github.com/qqhkx2027/qiuqiu-wechat-editor) | Markdown 转公众号排版，支持主题、预览与复制 | Web 应用 | [GitHub](https://github.com/qqhkx2027/qiuqiu-wechat-editor) |
| [qiuqiu-cover-prompt](https://github.com/qqhkx2027/qiuqiu-cover-prompt) | 按平台和构图模式生成封面提示词 | Skill | [GitHub](https://github.com/qqhkx2027/qiuqiu-cover-prompt) |
| [qiuqiu-infographic-maker](https://github.com/qqhkx2027/qiuqiu-infographic-maker) | 将文章整理成康奈尔或咨询风信息图方案 | Skill | [GitHub](https://github.com/qqhkx2027/qiuqiu-infographic-maker) |
| [qiuqiu-obsidian-notes](https://github.com/qqhkx2027/qiuqiu-obsidian-notes) | 将内容沉淀为结构化、可复用的 Obsidian 笔记 | Skill | [GitHub](https://github.com/qqhkx2027/qiuqiu-obsidian-notes) |
| [qiuqiu-workbench-builder](https://github.com/qqhkx2027/qiuqiu-workbench-builder) | 从需求生成可离线、可备份、可分享的个人工作台 | Skill / HTML | [GitHub](https://github.com/qqhkx2027/qiuqiu-workbench-builder) |
| [qiuqiu-document-workshop](https://github.com/qqhkx2027/qiuqiu-document-workshop) | 身份证等证件裁剪、校正并合并为 PDF | Web / Python | [GitHub](https://github.com/qqhkx2027/qiuqiu-document-workshop) |

## 推荐使用顺序

1. 用 `qiuqiu-wechat-editor` 整理 Markdown 与公众号排版。
2. 用 `qiuqiu-cover-prompt` 为不同平台生成封面提示词。
3. 用 `qiuqiu-infographic-maker` 把复杂内容转成信息图。
4. 用 `qiuqiu-obsidian-notes` 将方法和结论沉淀到知识库。
5. 用 `qiuqiu-workbench-builder` 管理长期项目、习惯与内容生产。
6. 用 `qiuqiu-document-workshop` 处理证件和 PDF 等实用文件。

## 设计原则

- 先确认目标和输出格式，再执行生成或转换。
- 重要内容可检查、可恢复，不静默覆盖用户文件。
- 技能目录保持自包含，校验脚本不依赖某个用户的本机路径。
- Web 项目优先提供在线预览；本地工具提供清晰的启动方式。

## 本地目录

在本地 Obsidian 工作区中，项目对应于 [`05-Agents/`](../) 下的同名目录。

## 许可

各项目分别使用 MIT License；具体以对应仓库根目录的 `LICENSE` 为准。
