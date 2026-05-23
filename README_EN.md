![skill-to-web-prompt](https://socialify.git.ci/Ww-Cooooo/skill-to-web-prompt/image?description=1&font=Inter&forks=1&issues=1&language=1&name=1&owner=1&pattern=Formal+Invitation&pulls=1&stargazers=1&theme=Auto)

<div align="center">

[简体中文](README.md) | English

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Claude%20Code-Skill-6C4DF6?style=flat-square&logo=anthropic" alt="Claude Code Skill">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License">
  <img src="https://img.shields.io/badge/Platform-Web%20AI-blue?style=flat-square" alt="Web AI">
</p>

---

> Got a killer Claude Code skill but can't use it in ChatGPT, DeepSeek, or Doubao? This skill converts it into a self-contained prompt you can copy-paste into any web AI — with an honest analysis of what transfers and what doesn't.

## Quickstart

```bash
npx skills@latest add Ww-Cooooo/skill-to-web-prompt
```

Once installed, just say any of these in Claude Code:

- "Convert humanizer-zh to a web AI prompt for ChatGPT"
- "Can find-skills work in DeepSeek? Turn it into a prompt"
- "Turn skill-creator into a prompt I can use in the browser"
- "Export this skill as a web AI prompt"

## What It Does

Each conversion produces a complete document with three sections:

| Section | Description |
|---------|-------------|
| **Usage Guide** | What you need, typical workflow, caveats |
| **The Prompt** | Self-contained, copy-paste ready — works in any web AI |
| **Analysis Report** | Implementation fidelity, kept vs lost features, manual steps, experience differences |

> [!IMPORTANT]
> The analysis is **honest**. If only 30% transfers, that's what you'll see. No sugarcoating.

## Why This Exists

**The Problem:** Claude Code skills are powerful — de-AI-ifying text, finding skills, code review, and more. But they're locked inside Claude Code. When you switch to a web AI, all that capability is gone. Manually rewriting skill logic into prompts is tedious and error-prone.

**The Solution:** Let Claude Code do the conversion itself. It understands the skill's internals, knows the differences between environments, and can give you an accurate picture of what will and won't work.

## Conversion Fidelity by Skill Type

| Skill Type | Expected Fidelity | Notes |
|------------|-------------------|-------|
| Pure text/code processing | 90%+ | De-AI-ify, translation, code review — nearly lossless |
| File I/O with manual workarounds | 70-89% | Core logic transfers; file ops replaced by copy/paste |
| Bash/search/orchestration heavy | 40-69% | Methodology and framework transfer; execution layer lost |
| Core Agent/sub-agent dependent | < 40% | Sub-agents can't be replicated; only conceptual framework remains |

> [!NOTE]
> Web AIs cannot execute scripts, read/write files, or run shell commands. This physical limitation determines which skills convert well.

## Installation

### npx (Recommended)

```bash
npx skills@latest add Ww-Cooooo/skill-to-web-prompt
```

### Git Clone

```bash
git clone https://github.com/Ww-Cooooo/skill-to-web-prompt.git ~/.agents/skills/skill-to-web-prompt/
```

## License

MIT — use freely, attribution appreciated.

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Ww-Cooooo/skill-to-web-prompt&type=Date)](https://www.star-history.com/#Ww-Cooooo/skill-to-web-prompt&Date)
