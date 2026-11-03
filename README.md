# Namer Skill

An agent skill for naming mobile applications, SaaS products, open source tools, and consumer brands.

Namer combines metaphor exploration, sound symbolism, and availability verification into a structured seven-step workflow. It helps you find names that sound natural, tell a compressed story, and avoid common tech naming clichés.

## Why use this skill

Naming often stalls in two ways: brainstorming devolves into a thesaurus search that generates generic tech clichés, or someone picks a favorite name only to discover it is already taken by a competitor or trademarked by an established brand.

This skill treats naming as a strategic process:
- It maps concrete metaphors before generating names.
- It tests candidates against pronunciation across target languages, including English, Portuguese, Spanish, and Chinese.
- It verifies availability on app stores, domain registries, and trademark records before presenting finalists.

## Installation

### For Google Antigravity
Clone or copy this repository into your skills directory:

```bash
git clone https://github.com/zerracas/namer-skill.git ~/.gemini/skills/namer
```

Or as a workspace skill in your project:
```bash
git clone https://github.com/zerracas/namer-skill.git .agents/skills/namer
```

### For Claude Code, Cursor, and other AI assistants
Copy `SKILL.md` to your agent skills folder, or reference it in your system instructions.

## How it works

When invoked, the skill guides the agent through seven stages:

1. Naming brief: Captures core purpose, audience, tone, languages, and constraints.
2. Metaphor mapping: Identifies physical analogies and conceptual territories.
3. Candidate generation: Produces 30 to 50 raw candidates internally across multiple naming types.
4. Anti-pattern filtering: Eliminates predictable suffixes, awkward spellings, and names that fail the bar test.
5. Availability verification: Checks app stores, domains, and trademarks for conflicts.
6. Evaluation: Scores surviving candidates on sound, memorability, and legal defensibility.
7. Finalist presentation: Delivers three to five vetted candidates with origin stories, sentence tests, and suggested taglines.

## License

MIT License. See [LICENSE](LICENSE) for details.
