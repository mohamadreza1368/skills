---
name: research
description: Investigate a question against high-trust primary sources and capture
  the findings as a Markdown file in the repo. Use when the user wants a topic researched,
  docs or API facts gathered, or reading legwork delegated to a background agent.
category: engineering
risk: safe
source: community
source_repo: mattpocock/skills
source_type: community
author: Matt Pocock
license: MIT
license_source: https://github.com/mattpocock/skills/blob/main/LICENSE
date_added: '2026-11-10'
---

## When to Use

Use when this workflow matches the user request: Investigate a question against high-trust primary sources and capture the findings as a Markdown file in the repo. Use when the user wants a topic researched, docs or API facts gathered, or reading legwork delegated to a background agent.

Spin up a **background agent** to do the research, so you keep working while it reads. Start it with a fresh context window.

Its job:

1. Investigate the question against **primary sources** (official docs, source code, specs, first-party APIs), not a secondary write-up of them. Follow every claim back to the source that owns it.
2. Write the findings to a single Markdown file, citing each claim's source.
3. Save it where the repo already keeps such notes; match the existing convention, and if there is none, put it somewhere sensible and say where.
