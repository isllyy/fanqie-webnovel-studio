# Fanqie Webnovel Studio

Codex skill for Chinese web-novel work on Fanqie/Tomato Novel, especially female-oriented long-form projects.

It combines:

- market scan and topic selection
- project setup and story bible creation
- total outline, volume outline, and chapter outline
- chapter drafting workflow
- self-review and AI-flavor reduction
- continuity tracking
- title, intro, tag, and publishing optimization

## Install

Use Codex skill installer with this GitHub path:

```bash
python3 ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo isllyy/fanqie-webnovel-studio \
  --path fanqie-webnovel-studio
```

Or explicitly reference the skill in Codex:

```text
Use $fanqie-webnovel-studio to plan a Fanqie female-fiction project.
```

## Skill Location

The actual skill lives in:

```text
fanqie-webnovel-studio/
├── SKILL.md
├── agents/openai.yaml
└── references/
```

## Typical Requests

- 帮我在番茄开一本女频新书
- 看看什么题材适合写
- 出总纲、卷纲和前 25 章章纲
- 继续写第 3 章，写完自动审稿
- 审一下这一章，减少 AI 味
- 给这本书做书名、简介、标签和发布建议
