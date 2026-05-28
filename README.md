# rules-horror — 规则怪谈生成器

Claude Code skill for generating authentic Chinese rules horror (规则怪谈) stories.

## Usage

In Claude Code, trigger with `/规则怪谈` or by asking in Chinese:

```
/规则怪谈
/规则怪谈 场景：老旧居民楼
生成一篇医院主题的规则怪谈
```

Without a specified setting, the skill randomly picks from a pool of everyday locations.

## What Makes Rules Horror Work

Rules horror generates fear through:
- **Contradiction**: Different documents give incompatible instructions
- **Implication**: Horror is never stated directly — the reader assembles it
- **Everyday corruption**: Familiar places (schools, offices, convenience stores) become uncanny
- **Cognitive contamination**: Understanding the rules makes you more vulnerable

## Skill Architecture

```
rules-horror/
  SKILL.md                       # Main workflow (6-step generation process)
  references/
    genre-guide.md               # Symbol theory, logical techniques, horror mechanics
    anti-patterns.md             # Common mistakes + quality checklist (18 anti-patterns)
    classic-examples.md          # Analyzed extracts from classic works
```

## Design Principles

- **Physical concept nodes** — all core symbols must be tangible objects/substances
- **Rules from incidents** — every abnormal rule carries the weight of an unstated past event
- **Limited perspective** — each document writer has incomplete, biased knowledge
- **Consequence opacity** — what happens if you break a rule is never stated
- **Anti-AI patterns** — no triple parallelisms, no symmetric structures, genuine "boring" content mixed in
- **Document authenticity** — each document passes the "would a real person write this?" test

## License

MIT
