<p align="center">
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-6C4DF6?style=flat-square&logo=anthropic" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/license-MIT-green?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/platform-Web%20AI-blue?style=flat-square" alt="Web AI">
</p>

<h1 align="center">Skill to Web Prompt</h1>
<p align="center"><em>将 Claude Code 技能转化为网页 AI 可直接使用的提示词</em></p>
<p align="center"><em>Convert Claude Code Skills into prompts for web-based AI tools</em></p>

---

## 快速开始 / Quickstart

### 方式一：npx 安装（推荐 / Recommended）

```bash
npx skills@latest add Ww-Cooooo/skill-to-web-prompt
```

### 方式二：Git 克隆

```bash
git clone https://github.com/Ww-Cooooo/skill-to-web-prompt.git ~/.agents/skills/skill-to-web-prompt/
```

---

## 这是什么？ / What Is This?

Claude Code 的技能可以做很多事——去 AI 味、找技能、代码审查等等。但这些技能只能在 Claude Code 里用。

这个技能帮助你把 Claude Code Skill 转换为网页 AI 可以**直接复制粘贴使用**的提示词。同时给出诚实的转化分析报告：能迁移多少、会丢失什么、需要手动做什么。

> Claude Code skills are powerful, but locked inside the terminal. This skill converts them into self-contained prompts that work in DeepSeek, Doubao (豆包), ChatGPT, and any other web-based AI — along with an honest analysis of what transfers and what doesn't.

---

## 使用方法 / Usage

在 Claude Code 中输入以下任意一句即可触发：

> Just say any of these in Claude Code:

| 中文 | English |
|------|---------|
| 帮我把 humanizer-zh 转成网页 AI 提示词 | Convert humanizer-zh to a web AI prompt |
| 这个 skill 能在 DeepSeek 上用吗？ | Can this skill work in ChatGPT web? |
| skill 转 prompt，find-skills | Turn skill-creator into a prompt |

### 输出内容 / What You Get

每次转换生成一份完整文档，包含三个部分：

| 部分 | 说明 |
|------|------|
| **使用说明** Usage Guide | 你需要准备什么、典型使用流程、注意事项 |
| **完整提示词** The Prompt | 核心产物，复制即用，可直接粘贴到任何网页 AI |
| **转化分析** Analysis Report | 实现度估算、保留/丢失的功能、手动操作清单、体验差异 |

---

## 为什么需要这个？ / Why This Exists

**问题：** 你在 Claude Code 里装了一个超好用的技能，但到了网页版 AI（豆包、DeepSeek、ChatGPT）上就没法用了。你不想每次都手动把技能的逻辑转写成提示词。

**解决：** 这个技能自动完成转化，并且诚实告诉你哪些能力无法迁移。不会为了让你开心而把 30% 的实现度写成 80%。

> **The Problem:** You've got a great skill working in Claude Code, but web AI tools can't use it. Manually rewriting skills into prompts every time is tedious and error-prone.
>
> **The Solution:** Automate the conversion, with honest analysis. Pure text-processing skills usually get 90%+ fidelity. Tool-heavy skills get an honest rating — no sugarcoating.

---

## 注意事项 / Notes

- 网页 AI **不能**执行脚本、操作文件、运行命令——依赖这些的技能，实现度会打折扣
- 纯文本/代码处理类技能（去 AI 味、翻译、代码审查）转化效果最好，通常 90%+
- 重度依赖 Bash/Glob/Grep/Agent 的技能，只能迁移方法论和框架部分
- 分析报告会如实告知限制，不会美化数字

> - Web AI tools **cannot** run scripts, read/write files, or execute shell commands
> - Text/code processing skills (de-AI-ify, translation, code review) convert best — usually 90%+ fidelity
> - Skills heavily dependent on Bash, file search, or sub-agents will lose significant functionality
> - The analysis report tells you honestly what's lost and why

---

## 许可证 / License

MIT
