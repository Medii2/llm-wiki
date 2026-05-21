\---

name: wiki-push

description: >

&#x20; Write durable knowledge from the current project back into the user's global research wiki or Obsidian vault after meaningful work blocks. Use this whenever new reusable knowledge has been produced, such as paper summaries, method insights, dataset lessons, conceptual clarifications, project synthesis, or reusable research reasoning, even if the user does not explicitly mention updating the wiki.

\---



\# Wiki Push



Use this skill to write durable knowledge from the current project back into the global research wiki.



\## Goal



Turn project work into reusable long-term knowledge.



This skill should:

\- identify what is worth preserving

\- distinguish durable knowledge from temporary project clutter

\- update existing wiki notes where possible

\- create clean new notes only when needed

\- keep the wiki coherent and non-duplicative



\## Preconditions



Before proceeding, confirm that the global wiki / vault is accessible in the current session.



If it is not accessible:

\- stop

\- say that the global wiki is not currently available

\- ask the user to add the wiki directory to the session

\- do not invent file updates



\## What counts as durable knowledge



Good candidates:

\- clean paper summaries

\- method lessons

\- dataset notes

\- conceptual clarifications

\- synthesis across sources

\- reusable project insights

\- definitions that will matter again

\- decisions that future projects may benefit from



Poor candidates:

\- scratch notes

\- temporary logistics

\- half-formed thoughts

\- duplicate notes

\- raw copied text without synthesis

\- project-specific clutter with no broader reuse value



\## Inputs to inspect



Check, when available:

\- the current user request

\- the current project files

\- `notes/`

\- `wiki-links.md`

\- recent outputs, summaries, or decisions

\- the existing global wiki structure, especially:

&#x20; - `20\_summaries/`

&#x20; - `30\_concepts/`

&#x20; - `40\_methods/`

&#x20; - `50\_datasets/`

&#x20; - `70\_projects/`

&#x20; - `90\_synthesis/`



\## Workflow



\### Step 1: Identify durable knowledge

Decide what has been learned that deserves to survive beyond this project session.



\### Step 2: Check for an existing destination

Look for an existing wiki note that should be updated.



Prefer updating existing notes over creating new ones.



\### Step 3: Write or update cleanly

When updating the wiki:

\- write concise, reusable prose

\- structure clearly

\- remove redundancy

\- keep notes easy to reuse later

\- preserve or add useful links where appropriate



\### Step 4: Update the project bridge

Update `wiki-links.md` when useful to record:

\- what was written back

\- which wiki notes now matter for the project

\- what still remains to be pushed later



\### Step 5: Report clearly

Summarize:

\- what was updated

\- what was created

\- what was intentionally left out because it was too temporary



\## Output format



When using this skill, structure the result like this:



\### Durable knowledge identified

\- what is worth preserving



\### Wiki updates made

\- existing notes updated

\- new notes created



\### Project bridge update

\- what changed in `wiki-links.md`



\### Not pushed

\- what was intentionally kept out of the wiki



\## Guardrails



Do not:

\- dump raw project notes into the wiki

\- create duplicate pages without checking first

\- overfit the wiki to one project's temporary needs

\- fabricate updates when the vault is not accessible

\- overwrite substantial notes carelessly



\## Standard

This skill is successful if the wiki becomes more useful for future work without becoming cluttered.

