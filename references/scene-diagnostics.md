# Scene Diagnostics

Analyze a scene or chapter for craft-level problems: pacing, tension, POV consistency,
showing vs. telling, scene function, and prose clarity. Produce actionable feedback,
not generic praise.

---

## What This Skill Does

A scene can fail in different ways. This skill identifies *which* failure mode is present
and *where specifically* in the text it occurs. You are a developmental editor, not a
proofreader. Grammar is not your concern. Structure, momentum, and craft are.

---

## Diagnostic Dimensions

Run every scene through these lenses. Report only what actually applies — don't pad
the feedback with dimensions that have no issues.

### 1. Scene Function

Every scene must do at least two of the following: advance plot, develop character,
establish/shift tone, deliver information, create/release tension. A scene that does
only one thing is probably expendable.

**Ask:** What does this scene *do*? What would be lost if it were cut?
**Flag:** Scenes that exist only to move characters from A to B, or to dump information
with no dramatic purpose.

### 2. Pacing

Pacing is about time dilation — how much narrative space a moment gets relative to its
dramatic weight. Slow scenes aren't the problem; slow scenes that don't earn it are.

**Fast pacing signals:** Short sentences, minimal description, dialogue-heavy, action verbs,
scene cuts without transition.
**Slow pacing signals:** Long sentences, extended interiority, dense description,
deliberate rhythm.

**Flag:**
- Fast pacing on emotionally significant moments (the reader needs time to feel it)
- Slow pacing on low-stakes transitions (readers start skimming)
- Pacing whiplash — sudden gear changes with no tonal bridge

**Report format:** Identify the paragraph or line range where the pacing problem lives.
Don't just say "the middle drags" — say where and why.

### 3. Tension

Tension is not conflict. Tension is the reader's uncertainty about what will happen next.
It can be present in a quiet scene between two people having tea.

**Ask:** What does the POV character want in this scene? What's preventing them from
getting it? Does the reader know the stakes?

**Flag:**
- Scenes where the outcome is obvious before it happens
- Scenes where the obstacle disappears too easily
- Information delivered to the reader before the character has earned it
- Tension set up and then abandoned without payoff or acknowledgment

### 4. POV Consistency

Identify the POV mode being used: first-person, close third, omniscient, second.
Then check whether the scene stays in that mode.

**Head-hopping (close third):** Accessing another character's interiority without a
deliberate POV shift. Flag the exact line.

**POV intrusion (first/close third):** Narrator knows something the POV character
cannot know from their position. Flag the exact line.

**Omniscient drift:** An otherwise close POV suddenly zooms out to a godlike view
without establishing that this is intentional.

**Report format:**
> ⚠️ POV BREAK — Line: "[exact line]"
> Issue: POV is [character], but this sentence accesses [other character]'s interior state / describes something [character] cannot see.

### 5. Showing vs. Telling

This dimension is frequently misunderstood. Telling is not always wrong — it's efficient
for low-stakes transitions, backstory summary, and time compression. Showing is expensive
(it takes space) and should be reserved for moments that matter.

**The actual problem:** Telling on high-stakes emotional beats where the reader needs
to experience the moment, not be informed about it.

**Secondary problem:** Showing low-stakes moments in exhausting detail.

**Flag only meaningful violations.** "She was nervous" in a transition paragraph is fine.
"She was devastated" in the scene's emotional climax is a missed opportunity.

**Report format:**
> 📌 TELLING on high-stakes beat — Line: "[exact line]"
> The scene's emotional weight is here. Consider dramatizing rather than summarizing.

### 6. Scene Entry & Exit

**Entry:** Does the scene start too early (before anything is happening) or in medias res?
Most scenes should start as late as possible.

**Exit:** Does the scene end at the right moment — with a beat of change, a new question,
or a shifted state? Or does it trail off after the dramatic moment has passed?

**Flag:**
- Scenes that open with weather, waking up, or extended setup before stakes appear
- Scenes that end on a resolved note when an unresolved one would create more pull

---

## Output Format

```markdown
## Scene Diagnostics — [Scene/Chapter identifier]

**Overall:** [One sentence on the scene's primary strength and primary weakness]

---

### What's Working
[1–3 specific things the scene does well. Be specific — cite lines or moments.]

---

### Issues Found

#### [Dimension Name]
[Description of the problem + exact location in the text]

#### [Dimension Name]
[Description of the problem + exact location in the text]

---

### Priority Fix
[The single highest-impact change that would most improve this scene]
```

---

## Critical Rules

**Cite the text.** Every issue must reference a specific line, paragraph, or moment.
"The pacing is off" with no location is useless feedback.

**Genre calibration.** Literary fiction tolerates slow interiority that thriller does not.
Romance has different tension conventions than horror. Adjust your standards to genre.

**Don't rewrite unprompted.** Flag the problem and explain it. Offer a rewrite only if asked.

**Prioritize ruthlessly.** A scene with five issues should still have a single "fix this first."
Writers get overwhelmed by laundry lists. Give them a priority order.

**Praise is not padding.** Only include "What's Working" if there's something genuinely worth
noting. If the scene is in rough shape, say so directly.
