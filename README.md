# rules-horror — 规则怪谈生成器

Claude Code skill for generating authentic Chinese rules horror (规则怪谈) stories.

## Installation

### Method 1: Git Clone

```bash
git clone https://github.com/yizhang-dream/claude-skills-rules-horror.git ~/.claude/skills/rules-horror
```

Restart Claude Code. The skill will be auto-discovered.

### Method 2: ZIP Download

1. Download `rules-horror.zip` from the [latest release](https://github.com/yizhang-dream/claude-skills-rules-horror/releases)
2. Extract to `~/.claude/skills/rules-horror/`
3. Restart Claude Code

After installation, verify: type `/规则怪谈` in Claude Code. It should trigger the skill.

### Method 3: Manual Copy

Copy this entire directory into `~/.claude/skills/rules-horror/`. The key file is `SKILL.md` — Claude Code discovers skills by scanning subdirectories of `~/.claude/skills/` for `SKILL.md` files with valid YAML frontmatter.

## Usage

In Claude Code:

```
/规则怪谈                    # Random setting
/规则怪谈 场景：老旧居民楼    # Specified setting
生成一篇医院主题的规则怪谈     # Natural language trigger
```

## Skill Structure

```
rules-horror/
  SKILL.md                       # 6-step generation workflow
  references/
    genre-guide.md               # Symbol theory, logical techniques
    anti-patterns.md             # 18 common mistakes + quality checklist
    classic-examples.md          # Analyzed extracts from classic works
```

## What Makes Rules Horror Work

Rules horror generates fear through:
- **Contradiction**: Different documents give incompatible instructions
- **Implication**: Horror is never stated directly — the reader assembles it
- **Everyday corruption**: Familiar places become uncanny
- **Cognitive contamination**: Understanding the rules makes you more vulnerable

## Design Principles

- **Physical concept nodes** — all core symbols are tangible objects/substances
- **Rules from incidents** — every abnormal rule carries the weight of an unstated past event
- **Limited perspective** — each document writer has incomplete, biased knowledge
- **Consequence opacity** — consequences of rule-breaking are never described
- **Anti-AI patterns** — no triple parallelisms, asymmetric structures, genuine "boring" content
- **Document authenticity** — each document passes the "would a real person write this?" test

## License

MIT
