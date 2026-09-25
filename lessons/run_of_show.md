# Instructor Run of Show — Qualitative Coding with AI Tools

**Length:** 100 minutes  
**Audience:** UC Berkeley PhD students in the humanities/conducting qualitative reseach  

---

# What this workshop is trying to do

This is **not** a workshop about teaching participants to automate qualitative research.

It is a workshop about helping researchers see what changes when an AI system enters a qualitative coding workflow.

The workshop's central arc:

> **human coding → disagreement → AI coding → instability → evidence audit → codebook repair**

The participants should leave understanding three things:

1. AI-generated coding is an **output to inspect**, not an answer key.
2. Requiring exact evidence makes model output much easier to audit.
3. Disagreement can reveal a problem with the model, a problem with the codebook, or a genuinely ambiguous passage.

The main line to return to throughout the session is:

> **No quote, no code.**


# The 100-minute schedule at a glance

| Time | What happens | What you use | What participants use |
|---|---|---|---|
| 0:00–0:03 | Welcome | `slides/intro.md` | Nothing yet |
| 0:03–0:10 | Framing + corpus + coding | `slides/intro.md` | Follow slides |
| 0:10–0:13 | Codebook orientation | `slides/intro.md` + `codebook.md` | `codebook.md` |
| 0:13–0:29 | Exercise 1: hand coding | Final intro slide | `01_hand_coding.md`, `codebook.md`, `exercise_1_hand_coding.md` |
| 0:29–0:36 | Human disagreement debrief | No new file needed | Their worksheet |
| 0:36–0:41 | Draft `T2-HARDSHIP` Version 1 | Whiteboard / shared notes | Their notes |
| 0:41–0:50 | Same prompt twice | `02_same_prompt_twice.md`, `live_demo.md`, AI chats | `live_demo.md` |
| 0:50–0:53 | Governance pause | Speak directly | Listen |
| 0:53–1:08 | Audit AI output | `03_audit_ai_output.md`, corpus + results | Same files |
| 1:08–1:23 | Repair `T2-HARDSHIP` | `04_repair_the_codebook.md` | Same lesson |
| 1:23–1:35 | Conclusion + discussion | `slides/conclusion.md` | Discussion |
| 1:35–1:40 | Questions + buffer | As needed | As needed |

That is exactly 100 minutes.

---

# 7. Minute-by-minute facilitation guide

# 0:00–0:03 — Welcome

## Project

`slides/intro.md`

Start on:

> **Qualitative Coding with AI Tools**

## Greetings

> Welcome. This is not a programming workshop. You will not need Python, an API key, or any knowledge of how GitHub works. The skill we are using today is close reading.
>
> We are going to use AI, but the workshop is really about something more basic: when a model gives us a coding decision, how do we know what it actually did?


---

# 0:03–0:10 — Introductory framing

Move through the intro slides.

## Slide: “You do not need to be technical”

> If you can read a passage closely and explain why a phrase matters, you have the skill we need today.

---

## Slide: “What we are really asking”

> We are not asking whether the tool can produce labels. It obviously can. We are asking whether those labels remain attached to evidence we can inspect.

---

## Slides on the corpus / Bracero Program


> These are oral-history passages connected to the Bracero Program, the guest-worker system that operated from 1942 to 1964. You do not need prior expertise on the program for today’s exercises.
>
> The important thing is that these are human memories about labor, migration, family, wages, housing, injury, and dignity. That makes careless quotation or overconfident interpretation consequential.

---

## Slide: “What is qualitative coding?”

> Coding is attaching a label to a piece of text because we think something analytically meaningful is happening there.
>
> The label is not just a tag. It is a claim. And we should be able to show another reader what in the passage supports that claim.

---

# 0:10–0:13 — Orient everyone to the codebook

## Project

The intro slide:

> **The codebook is our shared rulebook**

open:

`packet/codebook.md`



## Explain only the architecture

> There are two tiers.
>
> Tier 1 is closer to the surface of the text: crops, sites, contracts, procedures, wages.
>
> Tier 2 asks for more interpretation: ambivalence, dignity, negotiating compliance and power, retrospective judgment, and hardship.

Then:

> You do not need to memorize these. Keep the codebook open.

---

## Introduce the main rule

Returning to the intro slide:

> **No quote, no code.**


> Every time we apply a code today, we need exact words from the passage.
>
> Not a paraphrase. Not a summary. Not “the vibe of the passage.”
>
> Exact words.

---

# 0:13–0:29 — Exercise 1: hand coding

## Tell participants what to open

Participants should open:

1. [`lessons/01_hand_coding.md`](../lessons/01_hand_coding.md)
2. [`codebook.md`](..//codebook.md)
3. [`exercise_1_hand_coding.md`](../exercise_1_hand_coding.md)


> Keep the codebook and exercise sheet open. The lesson page only tells you what we are doing.

---

## Explain the timing


> You have 12 minutes working alone.
>
> For each passage, choose any codes you think apply, copy the exact evidence, and give a short reason.
>
> Then I’ll give you four minutes to compare with someone near you.
>
> There is no need to finish perfectly.


---

## During the 12 minutes


If someone asks, “What is the correct code?”, say:

> Make the strongest case you can from the definition and the passage. We will compare reasoning afterward.

If someone asks whether multiple codes are allowed:

> Yes.

If someone asks whether they have to use every code:

> No.

If someone is stuck on `T2-HARDSHIP`, say:

> Use your best judgment for now. We deliberately have not made that definition complete.

Do not explain what the final hardship definition should be.

---

`bha_1561_001` describes deductions and a tiny remaining paycheck.

`bha_1574_002` says the workers were paid in full and no wages were deducted.

They appear back to back on purpose.

---

## At 12 minutes

> Stop where you are. You do not need to finish every passage.
>
> Now compare with one person near you for four minutes.
>
> Find one place where you agreed and one place where you disagreed.

Start a 4-minute timer.

---

# 0:29–0:36 — Debrief human disagreement

Bring the room back.


## Start with a show of hands


> Who found at least one passage where you and your partner used different codes?

Then:

> Who found a passage where you used the same code but chose different evidence?

Then:

> Did anyone notice two passages that seem to contradict each other?

Let someone identify the deduction contradiction if possible.

---

## Useful prompts

Ask:

> Was the disagreement about the passage, or about what the code means?

> Did anyone feel that a Tier 1 code was easier to defend than a Tier 2 code?

> Did anyone use `T2-HARDSHIP` but feel unsure about what actually counted as hardship?

---

## Facilitator anchors — not an answer key

If discussion stalls, these are useful places to probe.

### `bha_1593_024`

Likely anchor:

- `T1-PROC`

Why it is useful:

- the narrator describes a recordkeeping system;
- the racial distinction in names versus numbers may also provoke interpretive discussion.

---

### `bha_1561_001`

Likely discussion:

- `T1-WAGE`
- `T1-PROC`
- `T2-HARDSHIP`
- possibly retrospective/evaluative language because of “almost slave labor”

Useful question:

> Is the hardship the dollar amount, the family being perpetually behind, or the narrator’s retrospective framing?

---

### `bha_1574_002`

Likely discussion:

- `T1-WAGE`
- possibly `T1-PROC`

Useful point:

> This is testimony about the narrator’s own experience of payroll. It does not “disprove” the previous passage. Different narrators, farms, and experiences can conflict.

---

### `bha_1592_012`

Useful interpretive tension:

- `T2-DIGNITY`
- possibly `T2-AMBIV`

Ask:

> Does the passage grant workers agency, or is it primarily about outsiders watching and interpreting their behavior?



---

### `bha_1573_004`

Strong anchor:

- `T2-NEGCOMP`

Potentially:

- `T2-HARDSHIP`

Ask:

> Who had the power to make the decision? Who bore the consequences? Who later denied responsibility?

---

### `bha_1588_003`

Strong anchor:

- `T2-AMBIV`

Because the narrator explicitly says:

> “mixed feelings”

and juxtaposes merchant profit with mistreatment.

---

# 0:36–0:41 — Draft `T2-HARDSHIP`, Version 1

This is a live group exercise.


Write at the top:

> **T2-HARDSHIP — Version 1**

Ask:

> Based on what you just coded, what should count as hardship?

---

## Useful questions

Ask:

> Does low pay automatically count?

> Does physical danger count if the narrator does not emotionally frame it as hardship?

> Does embarrassment or shame count?

> Does a difficult material condition count on its own?

> Does the narrator have to describe the condition negatively?

---

## Stop after five minutes


> We are going to come back to it after we see what the AI does.

Save the note or leave it visible somewhere you can recover later.

---

# 0:41–0:50 — Lesson 2: same prompt twice

## Participants open

[`lessons/02_same_prompt_twice.md`](../lessons/02_same_prompt_twice.md)

and

[`packet/live_demo.md`](../packet/live_demo.md)

## You project

`packet/live_demo.md`

The demo passage is:

`bha_1574_003`

This passage was not in the hand-coding exercise.

That is intentional.

---

# How to run the demonstration

## Run 1

Switch to the first blank AI chat.

### Step 1

Paste the **entire participant codebook** into the chat.

Do not summarize it.

Do not paste only the Tier 2 codes.

The model should receive the same codebook participants are using.

### Step 2

From `live_demo.md`, paste:

- the `bha_1574_003` passage;
- the exact prompt beneath it.

### Step 3

Send.

Read the answer with the room.

---

## What to record

Ask participants to note:

- Tier 1 codes;
- Tier 2 codes;
- evidence spans;
- ambiguity note.


---

## Run 2

Switch to the second blank AI chat.

It must be a genuinely new conversation.

Repeat the same sequence:

1. paste the same codebook;
2. paste the same passage;
3. paste the same prompt;
4. send.


---

# What if the two answers differ?

Good.

Ask:

> What changed?

Then narrow it:

> Different code?

> Same code, different evidence?

> Different confidence?

> Different ambiguity note?

---

# What if the two answers are almost identical?

Also fine.

Do **not** panic and do not keep rerunning until you manufacture disagreement.

> On these two runs, the output happened to be stable. That is useful information, but two matching runs do not establish reliability for the model, the codebook, or the larger corpus.

Then compare smaller things:

- exact wording of evidence;
- explanation language;
- ambiguity;
- omitted codes.


---

# What if the model gives an obviously strange answer?

Do not correct it immediately.

Say:

> Keep that. This is exactly the kind of output we need to learn how to audit.

The next exercise is designed for that.

---

# 0:50–0:53 — Governance pause

Stop the activity.

## Say roughly

> Before we go further, one important distinction.
>
> The fact that we can paste text into an AI chat window does not mean that we should paste any research data into one.
>
> The source chunks in today’s workshop are marked unrestricted in their repository metadata. Your own interviews, fieldnotes, archival materials, or human-subjects data may have very different conditions.
>
> Before using a consumer AI tool with your own material, check the relevant consent language, research protocol or IRB requirements, repository terms, confidentiality obligations, institutional policy, and the terms of the tool itself.
>
> Today’s exercise is a method demonstration, not blanket permission to upload research data.


---

# 0:53–1:08 — Lesson 3: audit the AI output

## Participants open

[`lessons/03_audit_ai_output.md`](../lessons/03_audit_ai_output.md)

They will also need:

- [`packet/corpus_32_passages.md`](../packet/corpus_32_passages.md)
- [`packet/precomputed_results.md`](../packet/precomputed_results.md)

## Explain the relationship between the two files

Say:

> The corpus is the source.
>
> The precomputed-results file is the AI output.
>
> We are going to compare one against the other.

If participants confuse the two, repeat:

> **Corpus = what the interview passage actually says.**
>
> **Results = what the AI claimed about it.**

---

# Show how to find a passage

This is worth demonstrating once.

Project `corpus_32_passages.md`.

Press:

- `Command + F` on Mac, or
- `Control + F` on Windows.

Type:

`bha_1582_005`

Show that the browser jumps to the passage.

Then do the same in `precomputed_results.md`.

Say:

> You do not have to scroll through 32 passages. Search by ID.


---

# Audit 1 — changed word

Use:

`bha_1582_005`

The AI output says:

> “it was a necessity thing...”

The source says:

> “it was a necessary thing.”

Ask:

> Is that catastrophic?

Probably not.

Then ask:

> Is it verbatim?

No.

The point:

> When we explicitly ask for exact evidence, “almost exact” is still a failed evidence check.


---

# Audit 2 — silent omission

Use:

`bha_1590_004`

The AI presents:

> “They'd pick a lock of cotton out of a bough instead of grabbing and pulling. They'd have to show them”

But the source contains another sentence between those two:

> “They'd pull one at a time.”

Ask:

> What would make this acceptable as an edited quotation?

Expected answer:

- an ellipsis;
- some visible indication that words were removed.

Explain:

> Shortening quotations is normal. Silently joining non-contiguous text while presenting it as a direct span is the problem.

---

# Audit 3 — accurate quote, questionable code

Use:

`bha_1588_003`

The AI applies `T1-WAGE` to:

> “sending money back home... money orders”

Ask:

> Is the quotation real?

Yes.

Then:

> Does sending money home describe wages, a pay rate, a deduction, or a payment mechanism?


The point:

> Accurate evidence does not guarantee a good code.

---

# Independent audit


> Pick any passage we have not discussed. Compare the result against the source and classify what you find.

They should use the categories in Lesson 3.

If time is tight, make this two minutes alone and two minutes with a partner.

---

# 1:08–1:23 — Lesson 4: repair the codebook

## Participants open

[`lessons/04_repair_the_codebook.md`](../lessons/04_repair_the_codebook.md)

Bring back the room’s earlier:

> **T2-HARDSHIP — Version 1**

Say:

> We now have more evidence about how the code behaves. Let’s see whether the problem was only the model—or whether the definition itself needed work.

---

# Suggested pacing inside the 15 minutes

## 1:08–1:10 — Re-read Version 1

Ask participants to look at their earlier notes.

Do not edit the definition yet.

---

## 1:10–1:15 — Compare the four hardship cases

Use the cases already embedded in Lesson 4:

- `bha_1561_001` — material deprivation;
- `bha_1561_002` — shame/social experience;
- `bha_1573_004` — physical danger;
- `bha_1574_001` — difficult material conditions plus evaluative language.

Do not spend equal time on all four if discussion is rich.

The purpose is to surface boundaries.

---

## 1:15–1:19 — Write Version 2

Participants draft their own revised definition.

If doing this as a whole group, structure it under four headings:

### What the code captures

### Use this code when

### Evidence should look like

### Do not use this code when

This is more useful than trying to write one elegant sentence.

---

## 1:19–1:22 — Test Version 2

Use one or more of:

- `bha_1591_007`
- `bha_1589_001`
- `bha_1594_014`

Ask:

> Does our new wording give us a clearer decision here?

If the answer is still “not really,” that is useful.

A codebook revision can fail its first test.

---

## 1:22–1:23 — Name the methodological point

Say:

> We did not repair the AI.
>
> We repaired the research instrument.

Then:

> A model disagreement can sometimes tell us that the prompt is weak. But it can also tell us that our code definition is carrying unresolved assumptions.

---

# Important note about the polished example in Lesson 4

Near the end of the participant lesson, there is an example of a more auditable `T2-HARDSHIP` instruction.

Do **not** show or discuss that example until participants have already written Version 2.

Otherwise you anchor the room to the example before they do the interpretive work themselves.

If time is tight, you may skip that example entirely.

---

# 1:23–1:35 — Conclusion slides

Project:

[`slides/conclusion.md`](../slides/conclusion.md)

Move more slowly than you did through the introduction.

These slides are the synthesis.

---

## Slide: “What did we actually learn?”

Say:

> The question was never simply whether AI is good or bad for qualitative research.
>
> The question is whether we can see and evaluate what it did.

---

## Slide: “The model gave us output”

Emphasize:

> Output is not findings.

A code, a quote, and an explanation can all look research-like before they have been checked.

---

## Slide: “Three different problems”

Reinforce the taxonomy:

1. bad quotation;
2. real quotation, weak code;
3. genuine interpretive ambiguity.

Say:

> Those problems require different responses.

---

## Slide: “The codebook is part of the system”

Say:

> A stronger prompt cannot fully compensate for a category we have not actually defined.

---

## Slide: “What AI was useful for today”

Do not make the ending purely cautionary.

Name the useful things:

- speed;
- consistency of format;
- ability to apply the same instruction repeatedly;
- ability to expose ambiguous definitions;
- creation of an inspectable first pass.

---

## Slide: “What AI did not replace”

Say:

> The responsibility for interpretation did not disappear.
>
> It moved.

That is a concise line worth using.

---

## Slide: workflow

Read the sequence:

> small corpus → human coding → draft codebook → AI first pass → evidence audit → codebook revision → test again

Say:

> The first AI output is not the end of the workflow. It is an object you use to stress-test the method.

---

## Final discussion prompt

Ask:

> What would you trust this tool to code?
>
> And what would you never hand it?

Give the room several minutes.

Encourage concrete answers.

Useful follow-ups:

> Would your answer change for Tier 1 versus Tier 2?

> Would your answer change if the source were confidential?

> Would your answer change if you had 50 documents versus 5,000?

> What would you insist on checking manually?

---

# 1:35–1:40 — Questions and buffer

Use this time for:

- questions;
- links;
- anything that ran long;
- pointing participants back to the repository.

Do not introduce a new exercise here.

If the workshop ran exactly on time, ask:

> What is one change you would make before trying this on your own project?

Then close.

---

# 8. What not to do during the workshop

## Do not make the AI the star of the session

The central object is the **research workflow**, not the product interface.

---

## Do not present the precomputed output as a benchmark or gold standard

It is deliberately something to audit.

---

## Do not tell participants the “right” code too early

Especially during Exercise 1.

The disagreement is part of the data for the workshop.

---

## Do not explain away every model error

If the model misquotes something, call it what it is.

You do not need to defend the model.

---

## Do not treat every disagreement as model failure

Humans disagree too.

Sometimes the code is underspecified.

Sometimes the passage is genuinely multivalent.

---

## Do not let the room spend 20 minutes debating the history of the Bracero Program

Historical questions are legitimate, but the session has a methods objective.

Say:

> That historical question matters, but for this exercise I want us to stay with what the passage and codebook let us claim.

---

## Do not introduce APIs, embeddings, fine-tuning, temperature, tokenization, RAG, or agent architecture unless someone asks after the workshop

None of those concepts are necessary for the learning objective.

---

# 9. Troubleshooting guide

# Problem: A participant says, “I don’t understand GitHub.”

Say:

> You do not need to understand GitHub. Think of this as a webpage containing our workshop documents. Click the filename I name and read it in your browser.

If needed, walk them directly to the file.

---

# Problem: A participant sees raw text and thinks something is broken

Say:

> This is a Markdown file. It is just a text document. Nothing is running.

If GitHub displays rendered headings and bullets, use that view.

Do not teach Markdown syntax unless someone asks.

---

# Problem: A participant cannot keep three tabs straight

Simplify.

For Exercise 1, tell them:

> Keep only the codebook and worksheet open.

For the audit:

> Keep only the corpus and results file open.

The lesson page can remain on the projector.

---

# Problem: Someone cannot access the AI chat tool

They can still participate.

The live demo is instructor-led.

Tell them:

> Watch the projected runs and record what you notice.

Do not spend workshop time troubleshooting their account.

---

# Problem: Your own AI chat stops working

Use `precomputed_results.md`.

Say:

> The live generation is not the learning objective. We already have model output to inspect.

Then move directly into the audit exercise.


---

# Problem: Run 1 and Run 2 are identical

Do not rerun repeatedly.

Use the identical result as a discussion point:

> Two matching runs are evidence about these two runs, not proof of general reliability.

Then move on.

---

# Problem: Run 1 and Run 2 are wildly different

Good.

Ask:

> Is the difference caused by evidence selection, code assignment, or explanation?



---

# Problem: The AI gives a quotation that does not exist

Do not fix it in the chat.

Save it as an example.

Say:

> This is exactly why our rule is no quote, no code.

Then move into the audit lesson.

---

# Problem: Participants get stuck asking “What is the correct answer?”

Say:

> In this workshop, “correct” has two different levels.
>
> A quotation can be factually checked.
>
> An interpretation can be better or worse supported, but reasonable readers may still disagree.


---

# Problem: Discussion runs long

Protect these parts:

1. hand-coding;
2. same-prompt comparison;
3. evidence audit;
4. codebook repair.

Cut from:

- historical background;
- independent audit time;
- number of test passages in Lesson 4;
- number of conclusion slides discussed aloud.


---

# 10. If you are 5 minutes behind

Use this compressed plan:

- shorten the Exercise 1 debrief by 2 minutes;
- make the Version 1 hardship discussion 3 minutes instead of 5;
- use only one independent audit passage;
- test Version 2 against one passage instead of three.


---

# 11. If you are 10 minutes behind

Skip the independent audit in Lesson 3.

In Lesson 4:

- discuss only Cases A, C, and D;
- draft Version 2 as a whole group;
- test it against only `bha_1594_014`.

Use only these conclusion slides:

1. What did we actually learn?
2. Three different problems
3. The codebook is part of the system
4. A workflow you can take home
5. Closing question

---

# 12. If you are ahead of time



Good extra questions:

> Which Tier 1 code would you be most comfortable scaling?

> Which Tier 2 code would you insist on auditing heavily?

> What would count as enough evidence that a coding workflow is stable?

> Would you want the model to be conservative and miss some codes, or expansive and over-code?

> What should be documented in a methods section if AI assisted with coding?

---

# 13. Suggested language for common participant questions

## “Is AI worse than a human coder?”

> That is not a question we can answer from this exercise as a general claim. What we can do is compare specific coding decisions, evidence, and sources of disagreement.

---

## “Should I use this for my dissertation?”

> Start with the data permissions and the research task. If the material can appropriately be used with the tool, test the workflow on a small corpus first and audit the output before scaling.

---

## “Can I just ask the AI to make the codebook?”

> You can ask it for suggestions, but that is a different research task. Today we are assuming the researcher has already made the analytic categories and is testing how they behave.

---

## “What model should I use?”

> Today’s lesson does not depend on identifying one universally best model. Whatever model you use, the coding still needs evidence and an audit procedure.

---

## “How many times should I run the same prompt?”

> Two runs today are a demonstration, not a statistical reliability test. For a real project, you would need a more systematic evaluation plan.

---

## “Is exact quotation too strict?”

> It is strict on purpose. We are using the evidence span as an audit trail. You can design a different workflow, but then you need another way to verify what the model based its coding on.

---

# 14. Instructor-only notes on tone

Keep the session calm and method-focused.

Avoid:

- “AI is amazing.”
- “AI is dangerous.”
- “Humans are subjective but AI is objective.”
- “The model hallucinated, therefore it is useless.”
- “The model got the right answer.”

Prefer:

- “What evidence supports that?”
- “What kind of disagreement is this?”
- “Is that quotation actually in the source?”
- “What does the codebook tell us to do?”
- “Would another reader be able to reproduce this decision?”
- “What would we change before scaling this?”

---

# 15. The simplest possible mental model for you as instructor

If you lose your place, remember this sequence:

### 1. Humans code first.

Use:

- `codebook.md`
- `exercise_1_hand_coding.md`

### 2. Humans disagree.

Discuss why.

### 3. Leave `T2-HARDSHIP` messy.

Write Version 1.

### 4. AI codes one fresh passage twice.

Use:

- `live_demo.md`
- two new chat windows

### 5. Check AI evidence against the source.

Use:

- `corpus_32_passages.md`
- `precomputed_results.md`
- `03_audit_ai_output.md`

### 6. Repair the code.

Use:

- `04_repair_the_codebook.md`

### 7. Name the larger lesson.

Use:

- `slides/conclusion.md`

That is the workshop.

Everything else supports those seven moves.

