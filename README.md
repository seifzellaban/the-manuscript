# The Manuscript

A master creative writing skill for long-form fiction and prose. Built for Qwen Code / Claude Code agents to provide professional-level developmental editing, continuity tracking, and submission support.

## What It Does

The Manuscript handles the full writer's workflow — from first draft to agent submission — through seven specialized sub-skills:

| Sub-Skill | Purpose |
|-----------|---------|
| **Continuity Tracker** | Track characters, events, timelines, and facts across chapters. Build and maintain a living story bible. Catch contradictions. |
| **Character Voice** | Fingerprint speech patterns, check dialogue consistency, audit multi-character voice collisions. |
| **Scene Diagnostics** | Analyze pacing, tension, POV consistency, showing vs. telling, scene function. Actionable feedback, not generic praise. |
| **Plot Structure** | Map manuscripts against structural frameworks (Three-Act, Save the Cat, Hero's Journey, Mystery, etc.). Find missing beats and pacing imbalances. |
| **Prose Style** | Capture the author's voice from samples. Check for stylistic drift. Draft passages in the writer's style. |
| **World-Building Codex** | Track lore, magic systems, history, geography, and cultural rules for fantasy/sci-fi. Enforce internal consistency. |
| **Query Letter** | Write query letters, synopses, and pitch documents following agent industry standards. |

## Structure

```
the-manuscript/
├── SKILL.md                    # Main skill with routing logic and universal rules
└── references/                 # Sub-skill files (schemas, workflows, output formats)
    ├── character-voice.md
    ├── continuity-tracker.md
    ├── plot-structure.md
    ├── prose-style.md
    ├── query-letter.md
    ├── scene-diagnostics.md
    └── worldbuilding-codex.md
```

## How It Works

1. **Route** — The agent identifies what the writer needs from their request
2. **Load** — Reads the relevant sub-skill reference file (never improvises)
3. **Execute** — Follows the sub-skill's schema and output format precisely
4. **Universal rules** apply across all sub-skills:
   - Never invent facts about the writer's story
   - Never silently resolve contradictions — surface them
   - You are an editor, not a co-author (unless explicitly asked to write)
   - Adapt to writer experience level (novice vs. experienced)

## When to Trigger

Any time a user is writing, editing, or planning fiction:

- Mentions of chapters, characters, plot, drafts, manuscripts, scenes
- "Does this contradict…", "is my pacing off", "write in my style"
- "Check my character's voice", "help me write a query letter"
- "Build a world bible", "where is my story structurally"
- Story bibles, world-building, lore, magic systems

## Installation

Place `the-manuscript/` in your agent's skills directory, or install `the-manuscript.skill` as a packaged skill file.

## Design Principles

- **One source of truth** — Structured outputs (bibles, codexes, profiles) live in defined schemas, not scattered prose
- **Distinguish stated from implied** — Mark inferences with `implied:` so writers can confirm or correct
- **Genre awareness** — Calibrate feedback to genre norms, not universal standards
- **Specificity over generality** — Every piece of feedback cites specific lines or moments
- **Structure serves story** — Frameworks are tools, not rules. Flag deviations, explain risks, let the writer decide

## License

MIT. See [LICENSE](LICENSE) for details.
