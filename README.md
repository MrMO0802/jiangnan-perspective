# jiangnan-perspective

A Codex skill that distills the public creative thinking patterns of Chinese fantasy writer Jiang Nan (Yang Zhi) into a practical writing, revision, and story-design assistant.

This skill is designed for high-level creative analysis, chapter-level revision, character-voice diagnosis, and original writing guidance. It does not contain Jiang Nan's books, does not reproduce protected text, and should not be used to generate close imitations of *Dragon Raja* or any other copyrighted work.

## What It Does

Use this skill when you want help with:

- modern fantasy or campus fantasy story design
- long-form worldbuilding
- youth/coming-of-age character arcs
- secret-school or hidden-world entry scenes
- dialogue that advances both information and relationships
- chapter revision that starts from structure instead of surface polish
- *Dragon Raja* character-voice diagnosis at a high-level craft level
- original fiction advice without copying *Dragon Raja* character voices
- IP adaptation risk analysis
- author rights, publishing, and creative-control reasoning
- reviewing a draft for "too much exposition" or weak emotional stakes

Typical trigger phrases:

- `用江南的视角`
- `江南会怎么看`
- `龙族作者视角`
- `少年感创作`
- `长篇幻想怎么写`
- `IP改编怎么判断`
- `江南 perspective`

## Core Modules

The skill includes seven story-craft modules:

1. **Low-status protagonist enters a huge world**
2. **Daily speech grounds mythic weight**
3. **Strong characters are mirrors, not just goals**
4. **Dialogue is status combat and emotional camouflage**
5. **Emotional debt comes before sacrifice**
6. **Worldbuilding pulls with mystery and pays off with emotion**
7. **Youthfulness is the powerless person's wish to be summoned**

It also includes two revision-focused systems:

- **Chapter revision protocol**: identify the chapter's job, emotional anchor, pressure ladder, character roles, and dialogue constraints before rewriting sentences.
- ***Dragon Raja* character-voice matrix**: high-level voice and behavior constraints for major characters such as Lu Mingfei, Chu Zihang, Nono, Lu Mingze, Caesar, Fingel, Erii, Anjou, Su Enxi, and Zero.

These modules are intended as reusable craft mechanisms, not as sentence-level style imitation.

## Installation

Copy this directory into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R jiangnan-perspective ~/.codex/skills/jiangnan-perspective
```

Then restart Codex so the new skill is loaded.

## Example Prompts

```text
我想写一个现代校园奇幻长篇，主角是很普通的县城高中生。请用江南式创作机制帮我设计第一卷大纲，但不要仿写原文。
```

```text
我写了一场秘密学院面试戏，但现在很像说明书。请用江南式小说创作引擎帮我改成更有日常质感和人物关系推进的设计。
```

```text
用江南视角帮我判断：这个幻想 IP 适不适合先做电影，而不是动画或剧集？
```

```text
我给你一幕《龙族》同人章节，感觉只是表皮润色。请先重构章节重点，再诊断人物声音，不要直接仿写原文。
```

```text
我想写一个原创现代奇幻，不是龙族同人。请用江南视角帮我判断这个故事的核心意义和第一卷结构。
```

## Repository Contents

```text
jiangnan-perspective/
├── SKILL.md
├── README.md
├── test-prompts.json
└── references/
    ├── extraction-framework.md
    ├── skill-template.md
    └── research/
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        ├── 06-timeline.md
        ├── 07-fiction-technique-from-local.md
        ├── 08-darwin-dry-run.md
        ├── 09-character-voice-from-local.md
        └── 10-darwin-character-voice-upgrade.md
```

## Sources and Method

The skill is based on:

- public interviews and media reports about Jiang Nan's writing, publishing, and IP views
- public reporting on recent publishing and copyright disputes
- private local-corpus structural analysis summarized only at a high level
- a derived character-voice matrix and revision workflow based on statistics, abstractions, and craft-level observations only

The repository does **not** include source ebooks, full text, chapter dumps, dialogue datasets, or long excerpts from copyrighted works.

## Safety and Copyright Boundary

This skill should:

- provide high-level analysis, outlines, craft advice, and original alternatives
- avoid close imitation of Jiang Nan's prose
- avoid reproducing long passages from copyrighted books
- refuse requests like "write a paragraph exactly like *Dragon Raja*"
- redirect imitation requests into craft-level guidance or clearly original writing

## Attribution

Generated with [女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill), then refined with Darwin-style dry-run reviews, including the character-voice and chapter-revision upgrade.

This repository is an independent skill package and is not affiliated with Jiang Nan, his publishers, or rights holders.
