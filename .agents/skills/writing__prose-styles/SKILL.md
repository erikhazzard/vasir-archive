---
name: writing__prose-styles
description: Writes prose in one of five house voices, lyrical fiction, lyrical realism, narrative journalism, explanatory and technical prose, and the house voice for players and users. Use for fantasy or real-world storyteller fiction (in the vein of The Name of the Wind), reported narrative, columns and newsletters, technical explanations, docs and reviews, or in-game and in-app copy.
---

# Prose styles

This skill holds five voices. Each lives in its own file under `voices/`. Pick one, read its file in full, and follow it.

## Pick the voice

| Voice | File | Use it for |
|---|---|---|
| Lyrical fiction | [voices/lyrical-fiction.md](voices/lyrical-fiction.md) | Fantasy prose from a storyteller looking back on a legend's life. Asked for by name, as a fantasy storyteller-memoir, or as prose like The Name of the Wind or Kvothe. |
| Lyrical realism | [voices/lyrical-realism.md](voices/lyrical-realism.md) | The same lyrical storyteller set in the real world. Asked for by name, or lyrical first-person memoir prose with no fantasy setting. |
| Narrative journalism | [voices/narrative-journalism.md](voices/narrative-journalism.md) | Reported narrative nonfiction, business and financial narrative, newspaper-style columns, newsletter intros, or any topic told as reported narrative. |
| Explanatory and technical | [voices/explanatory.md](voices/explanatory.md) | Prose that explains or argues for a reader who has to act on it: explanations for teammates, direct answers, design arguments and explainers, API reference entries, tutorials, incident summaries, code reviews, migration notes, and numbers for a general reader. |
| House (Plainspoken Lyricism) | [voices/house.md](voices/house.md) | Player- and user-facing text in games and apps: item and flavor text, lore, onboarding, notifications, store and update copy. |

Choosing:
- **A voice named.** Use it.
- **Lyrical, no setting given.** Use lyrical fiction when the subject or request suggests fantasy, and lyrical realism otherwise.
- **Explaining or in-product.** Text shown inside a game or app, including update copy, uses the house voice. Explanations, docs, reviews and incident notes for teammates or developers use explanatory prose.
- **Nothing named.** Match the request to the table. If two fit equally, use the house voice.

## Follow one file

- **Read the chosen voice file in full** before drafting, then follow it, with the reader's-perspective pass below, as your complete instructions. Do the same for any reference file it tells you to read.
- **Read only that voice.** Do not open the other voice files or mix their rules. Their rules conflict on purpose. For example, lyrical fiction forbids real-world names, and lyrical realism forbids made-up kingdoms and currencies.
- **Paths.** Links inside voice files point to files in this skill. Run scripts from this skill's folder, for example `python3 -I scripts/hardchecks.py …`.
- **Your reply is the piece only**, as the voice file describes. Do not mention which voice you chose.

## Always write from the reader's perspective

Whatever the voice, read [references/writing-from-reader-perspective.md](references/writing-from-reader-perspective.md) in full before drafting, and revise the draft once against its mandates before you reply. The voice file wins any conflict, and the pass never removes anything the voice requires or any fact, step, number or caveat the piece needs.
