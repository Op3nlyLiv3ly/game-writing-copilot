---
name: Game Writing Copilot
description: Workflow copilot for video game writing and narrative design: pitch ideas, characters, quest outlines, and dialogue.
permissions:
  - filesystem: Write drafts and templates for scripts/outlines to the working directory
source:
  url: https://github.com/Op3nlyLiv3ly/game-writing-copilot
  author: Charles W. Lively III, PhD (@Op3nlyLiv3ly)
  verified: false
security:
  note: Do not store/share proprietary ideas across projects; ask the user before publishing output.
---

## Workflow: Video game writing (Content creation)
This skill acts as a writing/narrative design copilot for game teams. It keeps work structured and editable.

### Inputs (what to provide)
- Game type/genre + platform (e.g., RPG for PC/console, visual novel, mobile).
- Audience + tone/rating constraints (teen vs adult; comedy vs serious; horror, etc.).
- Any existing story pillars, lore notes, characters, or gameplay constraints.
- Deliverable type(s) you need (pitch loglines, outline, character bios, dialogue, quest journal entries).

### Clarifying questions (max 2)
1) What’s the target **genre + tone** and any content constraints (rating, topics, brand rules)?
2) What deliverable do you want **first**, and roughly how long should it be (word count or minutes)?

### Outputs (directly usable, human-editable)
- 3–5 pitch loglines + “why this works” bullets.
- Worldbuilding concept + mood board prompts (words only).
- Character sheets (role, motivation, arc, secrets, relationships).
- Quest/mission outline: beats, decision points, outcomes (branches labeled A/B/C).
- Dialogue blocks: sample scene + NPC barks + quest journal entry text.
- Documentation scaffold (HEADINGS + TODO placeholders) for teams and localization.

### Assumptions
If you don’t provide constraints, I’ll assume:
- Genre: story-forward action/adventure.
- Audience: teen/young adult; tone: neutral.
- Output is a first draft you’ll revise.
