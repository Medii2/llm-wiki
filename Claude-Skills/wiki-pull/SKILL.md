\---

name: wiki-pull

description: >

&#x20; Retrieve and synthesize relevant prior knowledge from the user's global research wiki or Obsidian vault before starting substantial project work. Use this whenever beginning literature reviews, empirical design, data work, model building, writing, slides, synthesis, or project planning, even if the user does not explicitly mention the wiki. Also use when entering an existing project and needing to understand what is already known.

\---



\# Wiki Pull



Use this skill to pull relevant prior knowledge from the global research wiki into the current project context before doing substantial work.



\## Goal



Do not start from zero if the user already has relevant knowledge in the wiki.



This skill should:

\- find relevant prior notes

\- summarize what is already known

\- identify what can be reused

\- identify what is still missing

\- connect the project to the right wiki pages



\## Preconditions



Before proceeding, confirm that the global wiki / vault is accessible in the current session.



If it is not accessible:

\- stop

\- say that the global wiki is not currently available

\- ask the user to add the wiki directory to the session

\- do not hallucinate wiki contents



\## Inputs to inspect



Check, when available:

\- the current user request

\- the current project files

\- `wiki-links.md`

\- the global wiki folders, especially:

&#x20; - `20\_summaries/`

&#x20; - `30\_concepts/`

&#x20; - `40\_methods/`

&#x20; - `50\_datasets/`

&#x20; - `70\_projects/`

&#x20; - `90\_synthesis/`



\## Workflow



\### Step 1: Understand the current task

Identify what kind of task is being started:

\- literature review

\- conceptual framing

\- identification strategy

\- method choice

\- dataset selection

\- model design

\- writing

\- slides

\- project planning

\- replication or debugging



\### Step 2: Search the wiki

Search for notes that are relevant to the current task.



Prefer:

\- existing summaries over raw notes

\- concept and method notes over fragmented mentions

\- related project notes when the task resembles earlier work



\### Step 3: Select the most useful notes

Choose only the most relevant material.

Do not overwhelm the user with everything you find.



\### Step 4: Synthesize

Produce a concise synthesis that answers:

\- What do we already know?

\- What can be reused directly?

\- What is still unclear or missing?

\- Which wiki notes matter most for this task?



\### Step 5: Update the project bridge if useful

If `wiki-links.md` exists, update it when helpful by adding the most relevant wiki notes and noting missing knowledge gaps.



Do not write into the global wiki during a pure pull step unless the user explicitly asks for that.



\## Output format



When you use this skill, structure the result like this:



\### Relevant wiki knowledge

\- concise bullets or a short structured summary



\### Most relevant notes

\- note/file names or clear references



\### Reuse opportunities

\- what should directly inform the current work



\### Gaps

\- what still needs to be figured out



\### Optional project bridge update

\- what was added or clarified in `wiki-links.md`



\## Guardrails



Do not:

\- dump large excerpts

\- list every weakly related note

\- fabricate wiki contents

\- modify the global wiki unless clearly asked

\- create duplicate project notes unnecessarily



\## Standard

This skill is successful if the user can begin the task with a clear view of:

\- what already exists

\- what should be reused

\- what is missing

