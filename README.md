![skill-to-web-prompt](https://socialify.git.ci/Ww-Cooooo/skill-to-web-prompt/image?description=1&font=Inter&forks=1&issues=1&language=1&name=1&owner=1&pattern=Formal+Invitation&pulls=1&stargazers=1&theme=Auto)

<div align="center">

简体中文 | [English](README_EN.md)

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-6C4DF6?style=flat-square&logo=anthropic" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/Platform-Web%20AI-blue?style=flat-square" alt="Web AI">
</p>

---

> 你在 Claude Code 里装了一个超好用的技能，出门到了豆包/DeepSeek/ChatGPT 网页版上就没法用了。这个技能帮你把 Claude Code Skill 转成网页 AI 能直接复制粘贴使用的提示词，并给你一份诚实的转化分析。

## 快速开始

```bash
npx skills@latest add Ww-Cooooo/skill-to-web-prompt
```

安装后在 Claude Code 中说出以下任意一句即可触发：

- "帮我把 humanizer-zh 转成网页 AI 提示词，我想在豆包上用"
- "skill 转 prompt，find-skills"
- "这个 skill 能在 DeepSeek 网页版上用吗？"
- "把 skill-creator 转成 ChatGPT 能用的 prompt"

## 它做了什么？

每次转换生成一份完整文档，包含三个部分：

| 部分 | 说明 |
|------|------|
| **使用说明** | 你需要准备什么、典型使用流程、注意要点 |
| **完整提示词** | 核心产物，复制即用，粘贴到任何网页 AI 就能生效 |
| **转化分析** | 实现度估算、保留/丢失的功能、手动操作清单、体验差异 |

> [!IMPORTANT]
> 分析报告会**如实**告知哪些功能无法迁移，不会为了让你开心而把 30% 的实现度写成 80%。

## 为什么需要它？

**问题：** Claude Code 的技能能做很多事——去 AI 味、找技能、代码审查等等。但一旦离开 Claude Code，到了网页版 AI 上，这些技能就没法用了。每次手动把技能逻辑改写为提示词，费时又容易遗漏。

**解决思路：** 这件事应该让 Claude Code 自己来做。它最了解技能的机制，也知道两个环境的差异，由它来转化并诚实告诉你缺了什么，比你自己揣摩要准确得多。

## 哪些技能转化效果好？

| 技能类型 | 预期实现度 | 说明 |
|----------|-----------|------|
| 纯文本/代码处理 | 90%+ | 去 AI 味、翻译、代码审查等——几乎无损 |
| 有文件读写但可手动替代 | 70-89% | 核心逻辑可迁移，文件操作用"粘贴/复制"代替 |
| 依赖 Bash/搜索/编排 | 40-69% | 方法论和框架可迁移，执行层面丢失较多 |
| 核心依赖 Agent 子代理 | < 40% | 子代理无法替代，仅概念框架可保留 |

> [!NOTE]
> 网页 AI 不能执行脚本、操作文件、运行命令。这个物理限制决定了并非所有技能都适合转化。

## 安装

### npx 安装（推荐）

```bash
npx skills@latest add Ww-Cooooo/skill-to-web-prompt
```

### Git 克隆

```bash
git clone https://github.com/Ww-Cooooo/skill-to-web-prompt.git ~/.agents/skills/skill-to-web-prompt/
```

## 许可证

MIT — 随便用，署名即可。

## ⭐ 星星

[![Star History Chart](https://api.star-history.com/svg?repos=Ww-Cooooo/skill-to-web-prompt&type=Date)](https://www.star-history.com/#Ww-Cooooo/skill-to-web-prompt&Date)
