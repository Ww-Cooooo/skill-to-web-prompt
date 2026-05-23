# Skill to Web Prompt

将 Claude Code 技能（Skill）转化为网页 AI 可用的提示词，让 DeepSeek、豆包、ChatGPT 等网页版 AI 也能用上你的技能。

## 这是什么？

Claude Code 的技能（Skill）可以做很多事——去 AI 味、找技能、代码审查等。但这些技能只能在 Claude Code 里用。这个工具帮你把技能转成网页 AI 能直接使用的提示词，同时给出诚实的转化分析，告诉你能迁移多少、会丢失什么。

## 安装

### 方式一：直接安装（推荐）

将 `.skill` 文件拖入 Claude Code 窗口即可安装。

### 方式二：添加到 skills 目录

```bash
# 将仓库克隆到 Claude Code skills 目录
git clone https://github.com/Ww-Cooooo/skill-to-web-prompt.git ~/.agents/skills/skill-to-web-prompt/
```

## 使用方法

在 Claude Code 中输入类似以下内容即可触发：

- "帮我把 humanizer-zh 转成网页 AI 提示词，我想在豆包上用"
- "skill 转 prompt，humanizer-zh"
- "这个 skill 能在 DeepSeek 网页版上用吗？帮我把 find-skills 转一下"
- "把 skill-creator 转成 ChatGPT 能用的 prompt"

### 输出内容

每次转换会生成：

1. **使用说明** — 你需要准备什么、典型使用流程
2. **完整提示词** — 复制即用，可直接粘贴到豆包/DeepSeek/ChatGPT
3. **转化分析** — 实现度估算、保留和丢失的功能、手动操作清单、体验差异

## 注意事项

- 网页 AI 无法执行脚本、操作文件、运行命令——需要这些能力的技能，实现度会打折扣
- 纯文本/代码处理类技能（如去 AI 味、翻译）转化效果最好
- 转化分析会诚实告知哪些功能无法迁移，不会美化数字

## 许可证

MIT
