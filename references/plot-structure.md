# Plot Structure Auditor

Map the writer's manuscript against a structural framework to identify missing beats,
bloated sections, misfired turning points, and pacing imbalances at the macro level.

This skill operates on the *whole manuscript* (or a detailed outline), not individual scenes.

---

## Frameworks

Ask the writer which framework they want to use, or infer from context. If they don't
have a preference, default to Three-Act unless the genre strongly suggests otherwise
(e.g., romance → use Save the Cat's beat sheet variant; mystery → use the mystery structure).

| Framework | Best for |
|-----------|----------|
| Three-Act Structure | General fiction, literary, drama |
| Save the Cat (Blake Snyder Beat Sheet) | Commercial fiction, thriller, screenplay |
| Hero's Journey | Epic fantasy, adventure, mythology-adjacent |
| Freytag's Pyramid | Classical drama, tragedy, short stories |
| Dan Harmon's Story Circle | Character-driven, contemporary, TV-influenced |
| Mystery Structure | Crime, thriller, whodunit |

Load the relevant framework reference from the section below before auditing.

---

## Process

1. **Ingest the material.** Writer provides either: a chapter-by-chapter summary, a full
   outline, or the full manuscript. Work with whatever level of detail is available.
   More detail = more precise audit.

2. **Map to the framework.** Identify where each structural beat lands (or fails to land)
   in the manuscript. Use chapter numbers or scene identifiers as anchors.

3. **Identify gaps and bloat.** Flag beats that are missing, underdeveloped, or arrived
   at too early or too late. Identify sections that are structurally inert.

4. **Report.** Output the structural map + a prioritized list of issues.

---

## Framework References

### Three-Act Structure

| Beat | Typical Position | Description |
|------|-----------------|-------------|
| Opening image / status quo | Act 1 start (~0–5%) | World as it is before the story |
| Inciting incident | Act 1 (~10–15%) | The event that kicks the story into motion |
| First turning point / lock-in | Act 1 end (~20–25%) | Protagonist commits to the journey; no going back |
| Rising action / midpoint | Act 2a (~50%) | A major reversal or revelation that raises stakes |
| Crisis / dark night | Act 2 end (~75%) | All seems lost; protagonist hits their lowest point |
| Climax | Act 3 (~85–90%) | The decisive confrontation |
| Resolution | Act 3 end (~95–100%) | New equilibrium |

**Common failures:**
- Inciting incident too late (reader loses patience)
- Lock-in moment weak or absent (story feels meandering)
- Midpoint is just a scene, not a structural reversal
- Dark night skipped or rushed (climax feels unearned)

---

### Save the Cat Beat Sheet (15 Beats)

| Beat | Position | Description |
|------|----------|-------------|
| Opening image | 1% | Snapshot of the "before" world |
| Theme stated | 5% | Someone states what the story is really about |
| Set-up | 1–10% | Establish characters, world, stakes |
| Catalyst | 10% | The inciting incident |
| Debate | 10–20% | Hero resists the call |
| Break into Two | 20% | Hero commits; act 2 begins |
| B Story | 22% | A secondary story (often a relationship) that carries the theme |
| Fun and Games | 20–50% | The promise of the premise; what the trailer shows |
| Midpoint | 50% | False victory or false defeat; stakes raise |
| Bad Guys Close In | 50–75% | Everything starts going wrong |
| All Is Lost | 75% | The worst moment |
| Dark Night of the Soul | 75–80% | Hero processes the loss |
| Break into Three | 80% | The solution appears |
| Finale | 80–99% | Hero executes the solution |
| Final image | 99–100% | Mirror of opening image; shows how the world has changed |

---

### Hero's Journey (12 Stages)

Ordinary World → Call to Adventure → Refusal of the Call → Meeting the Mentor →
Crossing the Threshold → Tests/Allies/Enemies → Approach to the Inmost Cave →
The Ordeal → The Reward → The Road Back → The Resurrection → Return with the Elixir

**Note:** Hero's Journey is *not* a beat sheet with fixed positions. It's a thematic
sequence. Map it qualitatively — identify which stage each major section corresponds to.

---

### Mystery Structure

| Beat | Description |
|------|-------------|
| Crime / hook | The inciting crime or mystery — must be vivid and immediately engaging |
| Investigation opens | Protagonist enters the case; establish stakes and initial suspects |
| First false lead | A promising clue leads nowhere, raising the question further |
| Complication | New information changes the picture; the case gets harder |
| Dark turn | Someone else gets hurt, or the protagonist is threatened |
| Revelation | The real picture starts to emerge; clues click together |
| Confrontation | Protagonist faces the antagonist with the truth |
| Resolution | Loose ends resolved; justice (or its failure) delivered |

**Common failures:**
- Clues are unfair (reader had no access to them)
- Solution relies on information introduced after the midpoint
- Confrontation doesn't put the protagonist at genuine risk

---

## Output Format

```markdown
## Plot Structure Audit — [Title]
**Framework used:** [Framework name]
**Material analyzed:** [Outline / chapter summaries / full text — chapters N–N]

---

### Structural Map

| Beat | Expected Position | Actual Position | Status |
|------|------------------|-----------------|--------|
| [Beat name] | [~%] | [Ch. N] | ✅ / ⚠️ Late / ⚠️ Early / ❌ Missing |

---

### Issues Found

#### [Issue name]
**Beat:** [Which beat]
**Problem:** [Specific description of what's missing, weak, or mistimed]
**Impact:** [What this costs the reader — momentum, stakes, emotional payoff]

---

### Structural Strengths
[1–3 things the manuscript is doing well at the macro level]

---

### Priority Fixes
1. [Most critical structural problem to address first]
2. [Second priority]
3. [Third priority]
```

---

## Critical Rules

**Structure serves story, not the other way around.** If the writer has deliberately
subverted a framework for effect, say so — and assess whether it's working, not just
whether it's orthodox.

**Position is approximate.** Beat positions are guidelines, not rules. A midpoint at
45% vs. 55% is not a problem. A midpoint at 30% or 70% usually is.

**Missing ≠ wrong.** Some beats can be compressed, merged, or inverted intentionally.
Flag it, explain the risk, let the writer decide.

**Work with what you have.** A rough outline gives you a structural map. A full manuscript
gives you a precise one. Adjust confidence language accordingly.
