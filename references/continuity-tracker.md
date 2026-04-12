# Continuity Tracker

Track and maintain a living story bible — a structured record of everything established
in the manuscript. Catch contradictions. Answer continuity questions. Keep the writer
grounded in their own world.

---

## Modes

### Mode 1: Ingest — Build the Bible from Scratch

Writer provides chapters. You extract everything worth tracking.

**Process:**
1. Read the full input before extracting anything.
2. Extract entities into the schema below.
3. Flag ambiguities or contradictions *within* the provided text.
4. Present the completed bible. Note which chapters it now covers.

### Mode 2: Update — Add New Chapters

Writer provides a new chapter + existing bible.

**Process:**
1. Read the new chapter fully.
2. Check every new claim against the existing bible. Surface contradictions *before* updating.
3. Add new entities and facts. Update changed entries.
4. Return the full updated bible — not a diff.
5. End with a "What's new in Ch. N" summary, 3–5 bullets max.

**Contradiction format:**
> ⚠️ CONTRADICTION — [Entity]: Chapter N established [X]. This chapter states [Y]. Which is correct?

### Mode 3: Query — Answer Continuity Questions

Writer asks a specific question about their story.

**Process:**
1. Answer directly from the bible. Cite the chapter where the fact was established.
2. If not in the bible: "This hasn't been established yet — you're free to define it."
3. If inference is needed (timeline math, geography logic), show your reasoning.
4. Never invent facts.

---

## Story Bible Schema

```markdown
# Story Bible — [Working Title]
**Chapters covered:** [e.g., 1–7]
**Last updated:** [Chapter N]

---

## Characters

### [Character Name]
- **First appears:** Chapter N
- **Physical description:** [Only what's been stated on the page]
- **Age / age range:** [If established]
- **Role:** [protagonist / antagonist / supporting / mentioned]
- **Established traits:** [Behavioral facts shown or stated]
- **Relationships:** [See Relationships section]
- **Arc status:** [What has changed so far]
- **Open threads:** [Unresolved promises about this character]

---

## Locations

### [Location Name]
- **First mentioned:** Chapter N
- **Established facts:** [Physical details, rules, history]
- **Characters associated:** [Who lives/works/has been here]
- **Notable events:** [What has happened here]

---

## Objects & Artifacts

### [Object Name]
- **First appears:** Chapter N
- **Description:** [Physical, magical, or functional properties]
- **Current location/holder:** [As of last mention]
- **Significance:** [Narrative role]

---

## Timeline

| Event | Chapter | Time Anchor |
|-------|---------|-------------|
| [Event] | Ch. N | [e.g., "3 days before the festival"] |

---

## World Rules & Established Facts

- [e.g., "Magic requires physical contact with the source"]
- [e.g., "The war ended 40 years before the story begins"]

---

## Relationships

- **[Name] ↔ [Name]:** [Nature] — [Status as of last update]

---

## Open Threads & Foreshadowing

| Thread | Introduced | Notes |
|--------|------------|-------|
| [Setup that hasn't paid off] | Ch. N | [Context] |

---

## Active Contradictions & Flags

> ⚠️ [Description — awaiting writer's decision]
```

---

## Edge Cases

**Non-linear narrative:** Build timeline in chronological order. Note if narrative order differs.

**Multiple POVs:** Track POV as a character field. Flag if POV consistency breaks within a scene.

**Fantasy / sci-fi:** The World Rules section is critical. Lore established in Ch. 2 constrains Ch. 9.

**Partial draft / scene fragment:** Still extract. Label as "Scene — [description]" in coverage note.

**Draft placeholders ("[INSERT SCENE]", "TBD"):** Note them as open threads, don't skip them.
