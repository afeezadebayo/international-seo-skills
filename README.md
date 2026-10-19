# International SEO — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **international SEO** skills for **Claude, Claude Code, OpenAI Codex** and any agent that reads the
[Agent Skills](https://agentskills.io/specification) format. Serve the right country and language version to every
market: structure, hreflang, localisation, multilingual keywords, local search engines and market-by-market reporting.
Each skill is a single `SKILL.md`: a senior practitioner's workflow — when to use it, the inputs to ask for, a numbered
process, decision rules, an output template and sources — loaded only when a task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/international-seo/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/international-seo-skills.git
cp -r international-seo-skills/hreflang-implementation ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r international-seo-skills/hreflang-implementation ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/international-seo/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`international-seo-audit`](international-seo-audit/SKILL.md) | Audit how a site serves each country and language, scored per market with a prioritised plan. The entry point. |
| [`international-market-selection`](international-market-selection/SKILL.md) | Choose and prioritise countries and languages with a phased roadmap, success metrics and exit criteria. |
| [`international-site-structure`](international-site-structure/SKILL.md) | Choose ccTLDs vs subfolders vs subdomains and design the URL patterns for language and country. |
| [`hreflang-implementation`](hreflang-implementation/SKILL.md) | Implement and debug hreflang via HTML, headers or sitemaps, with canonical alignment and validation. |
| [`geo-language-targeting`](geo-language-targeting/SKILL.md) | Align the signals Google and Bing use to show the right country and language version. |
| [`international-technical-seo`](international-technical-seo/SKILL.md) | Fix crawler access per locale, forced redirects, CDN caching, language selectors and performance by country. |
| [`multilingual-keyword-research`](multilingual-keyword-research/SKILL.md) | Research keywords natively per market instead of translating English lists. |
| [`international-content-strategy`](international-content-strategy/SKILL.md) | Plan content per market — translate, adapt, create or skip — instead of translating everything. |
| [`localisation-translation`](localisation-translation/SKILL.md) | Design localisation workflows: content tiers, glossaries, AI translation with native review, quality checks. |
| [`international-link-building`](international-link-building/SKILL.md) | Build local authority per market with native outreach, local assets, partners and directories. |
| [`local-search-engines`](local-search-engines/SKILL.md) | Plan SEO for Baidu, Yandex, Naver and Seznam where Google isn't dominant. |
| [`international-expansion-migration`](international-expansion-migration/SKILL.md) | Plan market launches and international migrations with benchmarks, redirect/hreflang maps and rollback triggers. |
| [`international-seo-reporting`](international-seo-reporting/SKILL.md) | Report international SEO per market: segmentation, ranking-URL match, conversions and investment reviews. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: international SEO skills, multilingual SEO, SKILL.md, Agent Skills, Claude skills, Claude Code skills,
Codex skills, AI agent skills, hreflang, ccTLD, subfolder, geo-targeting, localisation, translation, multilingual
keyword research, Baidu, Yandex, Naver, Seznam, international site migration, international SEO reporting.</sub>
