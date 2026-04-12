# World-Building Codex

Track and maintain the rules, history, geography, and lore of a fictional world.
Sister skill to the Continuity Tracker — where that skill tracks *narrative events*,
this skill tracks *world facts that constrain the narrative*.

Use this for fantasy, sci-fi, alternate history, or any story with a built world
that has its own internal logic.

---

## The Core Principle

A world that contradicts itself destroys reader trust faster than almost any other
failure. The codex exists to make internal consistency *automatic* — so the writer
can focus on story and trust that the world holds together.

Everything in the codex is a *constraint*. Once it's in, it applies everywhere.

---

## Modes

### Mode 1: Build the Codex

Writer provides world-building material (chapters, notes, documents, or a mix).
You extract and organize everything into the codex schema.

**Process:**
1. Read everything before extracting.
2. Separate world facts from narrative events. ("The war ended 200 years ago" is a
   world fact. "The characters visit the battlefield" is a narrative event — that goes
   in the Continuity Tracker.)
3. Flag internal contradictions immediately.
4. Note where rules are implied vs. explicitly stated.

### Mode 2: Update the Codex

New chapter or notes expand the world. Add new entries, update existing ones, surface
any contradictions with previously established facts.

**Contradiction format:**
> ⚠️ WORLD CONTRADICTION — [Category]: Previously established [X]. New material states [Y]. Which is canon?

### Mode 3: Query

Writer asks a world-building question: "Can my character travel from X to Y in three days?"
/ "Would this technology exist in my world?" / "What do we know about the religion in the
southern provinces?"

Answer from the codex. If not established, say so clearly. Optionally offer to help
the writer define it — but don't invent without permission.

### Mode 4: Consistency Check

Writer drafts a scene and asks whether anything violates established world rules.

Read the scene. Check every claim against the codex. Flag violations with exact quotes.

---

## Codex Schema

```markdown
# World Codex — [World / Project Name]
**Source material:** [What was used to build this]
**Last updated:** [Chapter N / Date]

---

## Physics & Fundamental Rules

Rules about how the world *works* at a base level — what's possible, what isn't.

- [e.g., "Magic is drawn from living things; using it shortens the user's lifespan"]
- [e.g., "FTL travel exists but induces 1:3 time dilation for the traveler"]
- [e.g., "The dead can be reanimated but retain no memories from life"]

Flag implied rules separately:
- implied: [e.g., "Fire magic appears stronger than water magic based on battle descriptions"]

---

## Geography

### [Region / Location Name]
- **Type:** [continent / city / kingdom / planet / dimension / etc.]
- **Location relative to other established places:** [brief]
- **Climate / physical character:** [if established]
- **Political status:** [if established]
- **Travel distances / times:** [if established — these are continuity constraints]
- **Notable features:** [anything plot-relevant]

---

## Political & Social Structure

### [Faction / Nation / Institution Name]
- **Type:** [empire / guild / religion / government / etc.]
- **Power:** [how much influence, over what]
- **Leadership:** [who, how selected]
- **Relationship to other factions:** [ally / enemy / neutral / complex]
- **Established history:** [relevant past events]
- **Current status:** [as of the story's present]

---

## History & Timeline

Major historical events that predate or contextualize the story.
These are world facts, not narrative events.

| Event | When (relative or absolute) | Significance |
|-------|----------------------------|--------------|
| [Event] | [e.g., "200 years before the story"] | [Why it matters to the present] |

---

## Magic / Technology Systems

### [System Name]
- **How it works:** [mechanics, sources, limits]
- **Who can use it:** [access rules]
- **Cost / consequence:** [what using it requires or risks]
- **Hard limits:** [what it explicitly cannot do]
- **Established uses in the text:** [chapter citations]

---

## Cultures & Peoples

### [Group / Species / Culture Name]
- **Physical characteristics:** [if non-human or distinctly described]
- **Cultural norms:** [established customs, taboos, values]
- **Language notes:** [if relevant — accent, idioms, script]
- **Relationship to other groups:** [established dynamics]

---

## Religion & Belief

### [Religion / Belief System Name]
- **Core tenets:** [as established in text]
- **Practices:** [rituals, observances]
- **Deities / figures:** [named entities and their domains]
- **Institutional structure:** [if any]
- **Relationship to magic / technology:** [if relevant]

---

## Economy & Resources

- **Currency:** [name, form, value relationships if established]
- **Key resources:** [what's scarce, what's abundant, what drives conflict]
- **Trade patterns:** [who trades with whom, if established]

---

## Open Questions & Undefined Areas

Things the story has gestured at but not fully defined. Track these so the writer
can either define them or deliberately leave them ambiguous.

| Element | Referenced In | Status |
|---------|--------------|--------|
| [e.g., "The origin of the Rift"] | Ch. 4 | Undefined — writer to decide |

---

## Active Contradictions

> ⚠️ [Description — awaiting writer's decision]
```

---

## Critical Rules

**World facts constrain story.** Once a rule is in the codex, the narrative can't violate it
without acknowledgment. If the story needs to break a rule, the writer needs to know that's
what they're doing.

**Implied rules are provisional.** Mark them clearly. An implied rule observed twice might
be a pattern; observed once might be coincidence. Don't encode it as hard law until confirmed.

**This is not a world-building brainstorm tool.** The codex records what exists in the text.
If the writer wants to brainstorm new world elements, that's a different task — and any new
elements only enter the codex once the writer confirms them.

**Scope discipline.** Don't let the codex become a wiki of every world detail that could
theoretically be interesting. Track what's established and what's *constraining*. A character's
favorite food is not a codex entry unless it matters to the plot.
