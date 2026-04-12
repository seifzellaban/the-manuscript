# Character Voice

Fingerprint a character's speech and behavioral patterns from the text, then use that
profile to check whether new dialogue and action feel genuinely in-character — or whether
the writer is accidentally making everyone sound the same.

---

## Modes

### Mode 1: Build a Voice Profile

Writer provides dialogue samples (and optionally action/interiority) for a character.
You extract a fingerprint.

**What to extract:**

**Vocabulary tier** — Does this character use simple/blunt words, elevated/literary language,
technical jargon, regional slang, archaic diction, profanity? What words do they *never* use?

**Sentence rhythm** — Short, punchy. Long and winding with subordinate clauses? Fragments?
Run-ons? Do they trail off, interrupt, or finish every thought?

**Speech habits** — Verbal tics ("look,", "I mean,", "right?"), filler patterns, how they
address others (formal titles vs. first names vs. nicknames), whether they ask questions
or make statements, hedging language vs. directness.

**What they talk about** — Topics they gravitate toward, deflect from, or obsess over.
What they notice in a room. What metaphors they reach for.

**What they *don't* say** — Avoidances, euphemisms, subjects they go silent on.

**Emotional register** — How do they express anger, fear, joy, grief? Do they emote openly
or suppress? Do they get sarcastic, cold, loud, or quiet under pressure?

**Contrast markers** — What makes this voice distinct from other characters in the same manuscript?

### Mode 2: Check Dialogue

Writer provides a passage and asks if it sounds like a specific character.

**Process:**
1. Load the character's voice profile (writer must provide it, or build one from samples first).
2. Read the passage.
3. Flag specific lines that feel off. Explain *why* — cite the profile element it violates.
4. Suggest alternatives only if the writer asks. Your job first is diagnosis, not rewrite.

**Feedback format:**
> ⚠️ VOICE DRIFT — Line: "[exact line]"
> Issue: [Character] typically [profile element]. This reads more like [what it sounds like instead].
> Suggestion (if requested): "[alternative phrasing]"

### Mode 3: Multi-Character Voice Audit

Writer asks whether characters are sounding too similar across a chapter or scene.

**Process:**
1. Extract dialogue by character from the provided text.
2. Compare against profiles if available, or derive rough profiles from the samples.
3. Identify where voices blur — where you could swap a line between characters and it wouldn't matter.
4. Report specific collision points with examples.

---

## Voice Profile Schema

```markdown
## Voice Profile — [Character Name]
**Sampled from:** [Chapters/scenes used as source]
**Sample size:** [approximate word count of dialogue analyzed]

### Vocabulary
- **Tier:** [simple / mixed / elevated / technical / regional]
- **Signature words/phrases:** [list]
- **Words they avoid:** [list, if observable]

### Sentence Rhythm
- **Typical length:** [short / medium / long / variable]
- **Structure:** [fragments / complete / run-ons / subordinate-heavy]
- **Trailing patterns:** [interruptions / ellipses / decisive endings]

### Speech Habits
- **Verbal tics:** [list]
- **How they address others:** [formal / first name / nicknames / varies]
- **Question-to-statement ratio:** [mostly questions / mostly statements / balanced]
- **Hedging:** [direct / hedges often / never commits]

### Emotional Register
- **Under pressure:** [gets cold / gets loud / deflects with humor / shuts down / etc.]
- **Expresses affection by:** [teasing / direct statement / action / avoidance]
- **Anger tell:** [specific observable behavior]

### Topical Patterns
- **Gravitates toward:** [topics, metaphor domains]
- **Avoids / deflects:** [topics]
- **Worldview in a sentence:** [what lens do they see everything through]

### Contrast Notes
- **Most distinct from:** [other character name] because [specific difference]
- **Most easily confused with:** [other character name] — watch for [specific collision point]
```

---

## Critical Rules

**Profile before check.** You cannot check voice consistency without a profile. If the writer
asks you to check dialogue but hasn't built a profile, build one from existing samples first.

**Quote exactly.** When flagging drift, always quote the exact line. Vague references are useless.

**Explain the violation.** "This doesn't sound like her" is not feedback. "She uses short declarative
sentences; this 40-word subordinate clause reads like [other character]" is feedback.

**Don't rewrite unprompted.** Diagnose first. Offer rewrites only when asked.

**Small sample = low confidence.** If you're building a profile from fewer than ~300 words of
dialogue, flag that the profile is provisional and may need revision with more samples.
