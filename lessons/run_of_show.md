# Instructor Run of Show — Qualitative Coding with AI Tools

**Length:** 100 minutes  
**Audience:** UC Berkeley PhD students in the humanities and other researchers doing qualitative work  
**Technical level:** Assume no programming background and very little familiarity with AI tools

---

# First: what this workshop is doing

Do not think of this as an AI demo.

The workshop is about qualitative coding. AI enters halfway through.

The basic sequence is:

> **people code → people disagree → AI codes → we check the AI → we revise the codebook**

That is enough to keep in your head while teaching.

By the end, participants should have seen three things for themselves:

1. AI output is something to check. It is not an answer key.
2. Asking for an exact quote gives us something concrete to verify.
3. When coding breaks down, the problem may be the model, the codebook, or the passage itself.

The phrase  keep returning to is:

> **No quote, no code.**

---

# Where the files are now

All of the workshop files you will use in class are currently in the `lessons` folder.

That includes the slides.

You do not need to explain the folder structure to participants unless someone asks.

The files are:

- `slides_intro.md`
- `01_hand_coding.md`
- `codebook.md`
- `exercise_1_hand_coding.md`
- `02_same_prompt_twice.md`
- `live_demo.md`
- `03_audit_ai_output.md`
- `corpus_32_passages.md`
- `precomputed_results.md`
- `04_repair_the_codebook.md`
- `slides_conclusion.md`
- `run_of_show.md`

There is also:

- `precomputed_results_sheet.csv`

Do not use the CSV in class unless someone specifically asks to see the structured data. The Markdown results file is much easier to read.

---

# What each file is for

## `slides_intro.md`

Project this at the beginning.

It gives the basic framing: what coding is, what the corpus is, and what participants are about to do.

---

## `01_hand_coding.md`

This is the short lesson page for the first activity.

It tells participants what to do.

---

## `codebook.md`

This is the shared rulebook.

Participants should keep it open during the first exercise and refer back to it later.

---

## `exercise_1_hand_coding.md`

This is the actual worksheet.

It contains the six passages participants code by hand.

---

## `02_same_prompt_twice.md`

This introduces the live AI comparison.

It explains why we are running the same task twice.

---

## `live_demo.md`

This has the fresh passage, the exact prompt, and the comparison questions.

Use this during the live demo.

---

## `03_audit_ai_output.md`

This is the guided audit exercise.

It walks participants through three actual problems in the precomputed output.

---

## `corpus_32_passages.md`

This is the source text.

If there is ever a disagreement about what the interview actually says, this is the file to check.

---

## `precomputed_results.md`

This is the AI output from the 32-passage run.

Participants compare it against `corpus_32_passages.md`.

It is not an answer key.

---

## `04_repair_the_codebook.md`

This is the last main exercise.

Participants return to `T2-HARDSHIP`, which was intentionally left loose, and rewrite it after seeing where the coding became unstable.

---

## `slides_conclusion.md`

Project this at the end.

It is short. Keep it short.

---

# What to have open before anyone arrives

Do this before the workshop starts.

Do not try to navigate the repository in front of the room.

Open these tabs in this order:

1. `slides_intro.md`
2. `codebook.md`
3. `exercise_1_hand_coding.md`
4. `01_hand_coding.md`
5. `02_same_prompt_twice.md`
6. `live_demo.md`
7. AI chat — blank conversation for Run 1
8. AI chat — another blank conversation for Run 2
9. `03_audit_ai_output.md`
10. `corpus_32_passages.md`
11. `precomputed_results.md`
12. `04_repair_the_codebook.md`
13. `slides_conclusion.md`
14. `run_of_show.md`

You do not need to project all of these. Most can sit in the background.

Also have a timer open.

Use a phone timer if that is easier. There is no reason to make the timing technical.

---

# Before class: check the live AI demo

A day or two before the workshop:

1. Sign in to the chat tool you plan to use.
2. Start a new chat.
3. Type something simple.
4. Make sure it answers.
5. Close that test chat.

That is all.

You do not need:

- Python
- an API key
- Codex
- an agent
- a terminal
- Git
- GitHub Desktop
- a notebook

For the live demo, you need a normal chat box.

If the interface shows the model name, write it down before class.

If you later describe the demo in teaching notes or methods notes, record:

- model name
- date
- whether you used a fresh chat
- exact prompt

Do not say the live demo used the same model as the precomputed 32-passage run unless you know that for sure.

---

# Before class: clean up your screen

You will be projecting a browser.

Before people arrive:

- close email
- close Slack or Teams
- close Messages
- close personal tabs
- turn off notifications
- make sure no sensitive material is visible
- increase browser zoom if the text is small

On a Mac, `Command +` makes browser text larger.

That is more useful than trying to make the Markdown look fancy.

---

# One tiny piece of browser knowledge worth showing participants

During the audit exercise, they will need to find passage IDs quickly.

Show this once:

- Mac: `Command + F`
- Windows: `Control + F`

Then type something like:

`bha_1582_005`

The browser jumps to that ID.

This saves several minutes of scrolling.

---

# 100-minute schedule

| Time | What happens | What you use | What participants use |
|---|---|---|---|
| 0:00–0:03 | Welcome | `slides_intro.md` | Nothing yet |
| 0:03–0:10 | What we are doing + corpus + basic coding | `slides_intro.md` | Follow slides |
| 0:10–0:13 | Codebook orientation | `slides_intro.md`, then `codebook.md` | `codebook.md` |
| 0:13–0:29 | Hand-code six passages | `01_hand_coding.md` / final intro slide | `codebook.md`, `exercise_1_hand_coding.md` |
| 0:29–0:36 | Debrief human disagreement | Their worksheet | Their worksheet |
| 0:36–0:41 | Draft `T2-HARDSHIP` Version 1 | Whiteboard / notes | Their notes |
| 0:41–0:50 | Same prompt twice | `02_same_prompt_twice.md`, `live_demo.md`, two chats | `live_demo.md` |
| 0:50–0:53 | Data / permissions pause | Speak directly | Listen |
| 0:53–1:08 | Audit the precomputed AI output | `03_audit_ai_output.md`, corpus, results | Same three files |
| 1:08–1:23 | Rewrite `T2-HARDSHIP` | `04_repair_the_codebook.md` | Same file |
| 1:23–1:35 | Closing slides + discussion | `slides_conclusion.md` | Discussion |
| 1:35–1:40 | Questions / buffer | Whatever is needed | Whatever is needed |

That is 100 minutes.

Do not feel obligated to hit every minute exactly. The hand-coding, audit, and codebook repair matter more than perfect timing.

---

# 0:00–0:03 — Welcome

## Project

`slides_intro.md`

Start on the title slide.

## Say:

> Welcome. This is not a programming workshop. You do not need Python, an API key, or any background in computer science.
>
> What we are doing today is much closer to ordinary close reading. We are going to code a small set of oral-history passages, see where we disagree, and then put an AI tool into the same process.
>
> The question is not “Can AI give me some labels?” It can. The question is what happens when we actually check the labels against the text.

Keep this short.

People do not need five minutes of reassurance that the workshop is nontechnical. Say it once, then start.

---

# 0:03–0:10 — Intro slides

Move through `slides_intro.md`.

Do not read the slides word for word.

The slides should give participants something to look at while you explain the basic setup.

---

## When you get to the “no technical background” point

Say:

> If you can read a passage and explain why one phrase matters, you already have what you need for this workshop.

Then move on.

---

## When you get to the Bracero corpus

Keep the history brief.

Say:

> We are working with short English-language passages from oral histories in the Bracero History Archive. The Bracero Program operated from 1942 to 1964.
>
> The passages deal with work, pay, housing, family, injury, migration, and how people remembered the program later.
>
> You do not need to know the history in advance to do the exercises.

If someone has deep historical knowledge and wants to add context, fine. But do not let the introduction turn into a separate history seminar.

---

## When you define qualitative coding

Say:

> Coding is just attaching a label to a piece of text because we think something analytically important is happening there.
>
> The important part is not the label by itself. We should be able to show another person what in the passage made us use that label.

Then move into the codebook.

---

# 0:10–0:13 — Open the codebook

## Project

`codebook.md`

Participants should open the same file.

Do not read all ten codes aloud.

Show them the two-tier structure.

Say:

> Tier 1 is the more concrete set: crop, site, contract, procedure, wage.
>
> Tier 2 asks for more interpretation: ambivalence, dignity, negotiating compliance and power, retrospective judgment, and hardship.
>
> Keep this open. You are not supposed to memorize it.

Then show the rule:

> **No quote, no code.**

Say:

> Every code needs exact words from the passage.
>
> Not a paraphrase. Not a summary. Not “this seems like hardship.”
>
> Give me the words.

That is enough.

---

# 0:13–0:29 — Exercise 1: hand coding

## Participants open

- `01_hand_coding.md`
- `codebook.md`
- `exercise_1_hand_coding.md`

If three tabs feels like too much, tell them:

> You really only need the codebook and the worksheet. The lesson page just tells you what we are doing.

The worksheet matters. The lesson page does not need to stay open.

---

## Give the instructions

Say:

> Work alone for 12 minutes.
>
> For each passage, choose any code or codes you think fit. Copy the exact words that support the code. Then give yourself a short reason.
>
> You can use more than one code. You can also decide that none fit.
>
> After 12 minutes I will stop you and give you four minutes to compare with someone near you.

Start the timer.

---

# During the 12 minutes

Do not keep talking.

Walk around.

Answer questions quietly.

The room needs time to read.

---

## If someone asks, “What is the correct code?”

Say:

> I want your best reading first. We will compare afterward.

Do not give them the answer.

---

## If someone asks whether several codes can apply

Say:

> Yes.

---

## If someone asks whether they have to use a Tier 1 and a Tier 2 code

Say:

> No. Use whatever actually fits.

---

## If someone gets stuck on `T2-HARDSHIP`

Say:

> Use your best judgment. That code is intentionally loose right now.

Do not tell them where we are going with it.

---

# A note to yourself about the six passages

Do not announce this before they code.

`bha_1561_001` and `bha_1574_002` sit next to each other for a reason.

One describes deductions and a paycheck that ends up at about two dollars.

The other says the workers were paid in full and that the narrator never saw wage deductions.

Let someone in the room notice this.

Do not say:

> Here are two contradictory accounts.

The discovery works better if they make it.

---

# At 12 minutes

Stop the timer.

Say:

> Stop wherever you are. You do not need to finish every passage.
>
> Now compare with one person near you.
>
> Find one passage where you agreed and one where you disagreed.

Give them four minutes.

---

# 0:29–0:36 — Debrief the human coding

Bring the room back.

Do not go passage by passage and reveal an answer key.

There is no reason to turn this into grading.

Start with the room.

Ask:

> Who had at least one disagreement with your partner?

Then:

> Did anyone use the same code but choose different evidence?

Then:

> Did anyone notice two passages that seemed to be saying different things about pay or deductions?

Let them talk.

---

# Questions to use

> Was the disagreement about the passage, or about what the code means?

> Did Tier 1 feel easier than Tier 2?

> Did anyone use `T2-HARDSHIP` and then realize they were not completely sure what counted as hardship?

> Did anyone decide not to code something because the evidence was not quite there?

You do not need to ask all four.

Use whatever gets the room talking.

---

# Instructor notes on the six passages

These are not “the answers.”

They are places to push if the discussion dies.

---

## `bha_1593_024`

The obvious Tier 1 anchor is:

- `T1-PROC`

The narrator is describing how people were entered into the weight books.

If someone raises the difference between names and numbers, let them talk about it.

Do not force a Tier 2 label.

---

## `bha_1561_001`

Likely codes:

- `T1-WAGE`
- `T1-PROC`
- `T2-HARDSHIP`

There is also strongly evaluative language:

> “almost slave labor”

A useful question:

> What exactly are you treating as the hardship here: the paycheck, the family always being behind, or the narrator’s later judgment?

---

## `bha_1574_002`

Likely:

- `T1-WAGE`
- possibly `T1-PROC`

Important:

Do not use this passage to “correct” Pompa.

They are different narrators describing different experiences.

Oral histories do not have to agree.

That is part of why this is a good corpus for the exercise.

---

## `bha_1592_012`

This is useful because people can reasonably split.

Possible discussion:

- `T2-DIGNITY`
- `T2-AMBIV`

Ask:

> Are the workers being shown as people making plans and trying to improve their families’ situation?
>
> Or is the stronger thing in the passage the way the community is watching and interpreting what they buy?

Let both readings sit for a moment.

---

## `bha_1573_004`

Strong candidate:

- `T2-NEGCOMP`

Also possible:

- `T2-HARDSHIP`

Ask:

> Who gets to make the decision here?
>
> Who gets hurt?
>
> Who says they are not responsible afterward?

---

## `bha_1588_003`

Strong candidate:

- `T2-AMBIV`

The narrator literally says:

> “mixed feelings”

and then moves between merchant profit and people not treating the braceros well.

This is a good place to show that sometimes a Tier 2 code is actually easier than expected.

---

# 0:36–0:41 — Draft `T2-HARDSHIP`, Version 1

Use a whiteboard, projected notes document, or anything you can type into quickly.

Write:

> **T2-HARDSHIP — Version 1**

Then ask:

> Based on what you just coded, what should count as hardship?

Take their words.

Do not try to make the definition elegant.

You want the room’s first version, including its messiness.

---

## Questions if they need help

> Does low pay automatically count?

> Does physical danger count even if the narrator tells the story very flatly?

> Does embarrassment count?

> Does cold housing count?

> Does the narrator have to say that something was bad?

> Is hardship a condition, a feeling about the condition, or both?

Write down enough to have a Version 1.

Then stop.

Do not solve it yet.

Say:

> Good. Leave it there. We are coming back to it.

Make sure you can find the note again later.

---

# 0:41–0:50 — Same prompt twice

## Participants open

- `02_same_prompt_twice.md`
- `live_demo.md`

## Project

`live_demo.md`

The passage is:

`bha_1574_003`

This is a fresh passage. They did not hand-code it in Exercise 1.

That is deliberate.

---

# Run 1

Switch to the first blank AI chat.

Do this slowly enough that the room can see what you are doing.

## Step 1: paste the codebook

Copy the full contents of `codebook.md`.

Paste it into the chat.

Do not summarize it.

Do not paste only Tier 2.

Use the same codebook the participants used.

---

## Step 2: paste the demo passage and prompt

Go to `live_demo.md`.

Copy:

- the `bha_1574_003` passage
- the exact prompt underneath it

Paste it into the same chat.

Send.

---

## Step 3: read the answer

Do not immediately argue with the model.

Ask participants to note:

- Tier 1 codes
- Tier 2 codes
- quoted evidence
- what the model calls ambiguous

You do not need to read every sentence of the response aloud.

---

# Run 2

Switch to the second blank chat.

This needs to be a new conversation.

Repeat the exact same steps:

1. paste `codebook.md`
2. paste the same passage
3. paste the same prompt
4. send

Do not mention Run 1 in the second chat.

---

# Compare the two

Use the questions in `live_demo.md`.

Ask:

> Same codes?

> Same evidence?

> Same ambiguity?

> Same level of confidence?

Do not jump straight to “Which one is right?”

First establish what changed.

---

# If the two answers are different

Good. Use the difference.

Ask:

> Where did the difference happen?

Was it:

- code choice
- evidence choice
- explanation
- ambiguity note

Do not spend the whole workshop deciding which run “wins.”

---

# If the two answers are almost identical

Also fine.

Do not rerun it five times trying to force disagreement.

Say:

> These two runs happened to be very similar. That tells us something about these two runs. It does not prove that the coding is reliable across the whole corpus.

Then look for smaller differences.

Did the explanation change?

Did it quote a different phrase?

Did one run mention an ambiguity the other ignored?

If there is genuinely no meaningful difference, move on.

The rest of the workshop does not depend on dramatic variation here.

---

# If the model gives a bizarre answer

Do not fix it in the chat.

Say:

> Keep that in mind. We are about to check model output against the source.

Then move on.

A strange answer is useful material.

---

# 0:50–0:53 — Short pause on data and permissions

Stop sharing the chat if possible.

This should feel separate from the live demo.

Say:

> Before we keep going, one quick thing about research data.
>
> The fact that we can paste text into a chat box does not mean we should paste any research material into one.
>
> The workshop chunks we are using are marked unrestricted in the source metadata. Your own interviews, fieldnotes, archival materials, or human-subjects data may have completely different rules.
>
> Before using a consumer AI tool with your own material, check the consent language, IRB or research protocol if there is one, repository terms, confidentiality obligations, institutional policy, and the tool’s own terms.
>
> Today’s corpus is a teaching example. It is not a general permission slip.

Then move on.

Do not turn this into a long policy lecture.

---

# 0:53–1:08 — Audit the AI output

## Participants open

- `03_audit_ai_output.md`
- `corpus_32_passages.md`
- `precomputed_results.md`

## Project

Start with `03_audit_ai_output.md`.

Explain the three files in one sentence each:

> `corpus_32_passages.md` is the source.
>
> `precomputed_results.md` is what the AI said.
>
> `03_audit_ai_output.md` tells us what to check.

That is all they need.

---

# Show `Command + F` / `Control + F`

Project `corpus_32_passages.md`.

Press:

- Mac: `Command + F`
- Windows: `Control + F`

Type:

`bha_1582_005`

Show that the browser jumps there.

Then do the same in `precomputed_results.md`.

Say:

> Search by passage ID. Do not scroll through 32 passages looking for it.

This one demonstration will save time.

---

# Audit 1 — one changed word

Use:

`bha_1582_005`

The AI gives:

> “it was a necessity thing...”

The source says:

> “it was a necessary thing.”

Ask:

> Is that a huge distortion?

Probably not.

Then:

> Is it an exact quotation?

No.

That is enough.

Say:

> We asked for verbatim evidence. This is not verbatim.
>
> The fact that the mistake is tiny is actually useful. Tiny mistakes are easy to miss.

Do not oversell this as some dramatic hallucination.

It is a small error.

That is exactly why it belongs here.

---

# Audit 2 — a sentence disappears

Use:

`bha_1590_004`

The AI gives:

> “They'd pick a lock of cotton out of a bough instead of grabbing and pulling. They'd have to show them”

The source has another sentence in between:

> “They'd pull one at a time.”

Ask:

> Is the model allowed to shorten a quotation?

Yes.

Then:

> What is missing?

An ellipsis or some visible sign that text was removed.

Say:

> Researchers shorten quotations all the time. The problem is not the shortening. The problem is pretending that two non-contiguous sentences were one continuous quotation.

---

# Audit 3 — the quote is real, but does the code fit?

Use:

`bha_1588_003`

The AI assigns `T1-WAGE` to:

> “sending money back home... money orders”

First ask:

> Is the wording actually in the passage?

Yes.

Then ask:

> Does this describe a wage, rate, deduction, paycheck, or way the worker was paid?

Let them argue.

This is the useful part.

The quote itself is fine.

The coding decision may not be.

Say:

> This is a different problem from the first two. The source is not wrong. The question is whether the code definition reaches this far.

---

# Independent audit

Give participants a few minutes.

Say:

> Pick one passage we have not already discussed.
>
> Find it in the results file and in the source corpus.
>
> Decide what kind of case it is.

They can use the categories in `03_audit_ai_output.md`.

Give them about two minutes alone and two minutes with a partner if time allows.

---

# Bring them back

Ask for one or two examples.

Do not collect ten.

The goal is simply to show that they can now do the audit themselves.

Useful question:

> What kind of problem did you find?

Possible answers:

- exact quote, good code
- bad quote
- good quote, weak code
- another code fits better
- real ambiguity
- unclear codebook

That list is enough.

---

# 1:08–1:23 — Repair `T2-HARDSHIP`

## Participants open

`04_repair_the_codebook.md`

Bring back the Version 1 definition you wrote earlier.

Project it if possible.

Say:

> We left this code intentionally loose. Now we have more evidence about how people and the model use it.

Do not say:

> Now we are going to make the correct definition.

There may not be one final perfect definition.

The goal is a clearer one.

---

# 1:08–1:10 — Look at Version 1 again

Give them a minute or two to reread what they wrote.

Ask:

> What already looks too broad?

> What is missing?

Do not edit yet.

---

# 1:10–1:15 — Work through the hardship cases

The lesson gives four cases:

- `bha_1561_001` — money / family falling behind
- `bha_1561_002` — shame and being made fun of
- `bha_1573_004` — injury and danger
- `bha_1574_001` — cold housing and no mattresses

You do not have to spend equal time on each.

The questions matter more than finishing all four.

Ask things like:

> Does material deprivation count by itself?

> Does shame count?

> Does danger count even if the narrator is emotionally flat?

> Does the word “miserable” make the housing case easier?

Let participants notice where they are drawing boundaries.

---

# 1:15–1:19 — Write Version 2

Have participants draft a new definition.

Use the headings already in `04_repair_the_codebook.md`:

### What this code captures

### Use this code when

### Evidence should look like

### Do not use this code when

This is easier than trying to write one beautiful sentence.

If you are doing it as a whole group, type under those headings while people talk.

---

# 1:19–1:22 — Test Version 2

Use one or more:

- `bha_1591_007`
- `bha_1589_001`
- `bha_1594_014`

Ask:

> Does the new definition make this case easier to decide?

If the answer is still no, that is fine.

A revised code can still need work.

That is normal.

---

# 1:22–1:23 — Close the exercise

Say:

> We did not fix the model just now. We changed the codebook.
>
> That is useful because sometimes repeated model disagreement is telling us something about our own category.

Then move to the conclusion.

Do not linger here if you are running behind.

---

# Important: the polished `T2-HARDSHIP` example near the end of Lesson 4

Do not show it before participants write Version 2.

Otherwise they will simply imitate it.

Once they have their own definition, you can show the example as:

> Here is one way this could be made more explicit.

Not:

> Here is the correct answer.

If time is short, skip it.

---

# 1:23–1:35 — Conclusion

## Project

`slides_conclusion.md`

Do not recap every minute of the workshop.

The room just did the exercises.

Use the conclusion slides to name what changed.

---

## “What did we actually learn?”

Say:

> I do not think the useful conclusion here is “AI is good” or “AI is bad.”
>
> The more useful question is whether we can see what it did well enough to judge it.

---

## “The model gave us output”

Say:

> It gave us codes, quotations, explanations, and ambiguity notes.
>
> None of those become findings just because they look polished.

---

## “Three different problems”

Name them plainly:

1. The quote is wrong.
2. The quote is right, but the code is weak.
3. The passage genuinely allows more than one reading.

Say:

> Those are different problems. Do not fix them in the same way.

---

## “The codebook is part of the system”

Say:

> If the code is vague, the model will use that vagueness.
>
> So will people.

That is enough.

---

## “What AI was useful for”

Let the room answer first if there is time.

Possible answers:

- it works quickly
- it applies the same format repeatedly
- it gives us something to compare
- it exposes fuzzy code definitions
- it can help with a first pass

Do not oversell it.

---

## “What AI did not replace”

Say:

> We still had to decide what counted as evidence, what the codes meant, and what we were willing to trust.
>
> That work did not disappear.

---

## Workflow slide

Read the sequence:

> small corpus → human coding → draft codebook → AI first pass → evidence audit → codebook revision → test again

Then say:

> Do not start by throwing 5,000 documents at a model.
>
> Start small enough that you can still read the mistakes.

That sounds more concrete than talking about “scaling responsibly.”

---

# Final discussion question

Ask:

> What would you trust this tool to code?
>
> What would you never hand it?

Give them a few minutes.

Good follow-ups:

> Would your answer change for Tier 1 versus Tier 2?

> What if the interviews were confidential?

> What if you had 50 documents? What about 5,000?

> What would you insist on checking yourself?

Stop when the discussion has made the point.

---

# 1:35–1:40 — Questions / buffer

Use this time however you need it.

If you are exactly on time, ask:

> What is one thing you would change before trying this on your own project?

Then take final questions.

Do not start another exercise.

---

# If the room is very quiet

Do not panic.

Humanities graduate students often need a little time before speaking.

Ask narrower questions.

Instead of:

> What do you think?

Try:

> Who used `T2-HARDSHIP` on this passage?

or:

> Who did not?

or:

> Which exact phrase made you choose that code?

Concrete questions are easier to answer.

---

# If the room starts debating history instead of coding

Do not shut them down abruptly.

Say:

> That is a real historical question. For this exercise, though, I want to separate what we know from outside the passage from what this code can support from the passage itself.

Then bring them back to the text.

---

# If someone says, “But humans make mistakes too”

Agree.

Say:

> Yes. That is why we started with human disagreement before we showed the AI.

Then ask:

> What kind of check would you want for either one?

That keeps the discussion from becoming “humans versus machines.”

---

# If someone asks, “Which answer is correct?”

Say:

> For the quotation, we can check.
>
> For the interpretation, we can ask whether the evidence and code definition support it.
>
> Sometimes two interpretations will both be defensible.

Short answer. Do not turn it into a lecture on epistemology.

---

# If someone says, “Isn’t this just inter-coder reliability?”

Say:

> It is related, but we are not calculating a reliability statistic today.
>
> We are looking closely at where the disagreement comes from before reducing it to a number.

---

# If someone asks, “Why not just have AI build the codebook?”

Say:

> That would be a different exercise.
>
> Today I want the analytic categories to come from the researcher so that we can see what happens when the model tries to apply them.

---

# If someone asks, “What model should I use?”

Do not pretend there is one best answer.

Say:

> For today, the model choice is less important than the fact that we can inspect the evidence.
>
> For a real project,  record the exact model and date, then test the workflow on a small sample before doing anything larger.

---

# If someone asks, “How many runs do I need?”

Say:

> Two runs today are just a demonstration.
>
> They are not a reliability study.

That is enough.

---

# If someone asks, “Why exact quotation? Isn’t that too strict?”

Say:

> It is strict on purpose.
>
> I want an audit trail.
>
> If the model cannot point me to the text, I have no quick way to check why it used the code.

---

# If someone cannot use GitHub

Do not teach GitHub.

Say:

> Think of it as the webpage where the workshop files live.

Then show them the exact filename.

That is all they need.

---

# If someone sees raw Markdown and thinks something broke

Say:

> Nothing is broken. It is just a text file.

If the rendered GitHub view is available, use that.

Do not start explaining Markdown syntax.

---

# If someone cannot access the AI chat

They can still do the workshop.

The live demo is instructor-led.

Say:

> Just follow the projected run and record what you notice.

Do not spend 10 minutes fixing their login.

---

# If your own AI chat fails

Do not waste the workshop troubleshooting.

Skip the live generation.

Go straight to:

`precomputed_results.md`

Say:

> The live tool is not cooperating. We already have model output, so we can still do the part that matters: checking it.

Then continue with the audit.

---

# If the two live runs are identical

Do not keep rerunning.

Say:

> These two runs matched. That does not tell us what happens across the whole corpus, but it tells us that this particular example was stable twice.

Move on.

---

# If the two live runs are wildly different

Do not ask the room to decide which one is “the real answer.”

Ask:

> What changed?

Then sort the difference:

- code
- quote
- explanation
- ambiguity

Move on once the room sees the difference.

---

# If the AI invents a quote during the live demo

Do not correct it in chat.

Say:

> Keep that. We are about to do an evidence audit.

Then use it if helpful.

---

# If discussion runs long

Protect these four pieces:

1. hand coding
2. live comparison
3. evidence audit
4. codebook repair

Cut time from:

- historical background
- independent audit
- number of hardship test cases
- conclusion discussion

Do not cut the codebook repair if you can avoid it.

That is where the earlier exercises come together.

---

# If you are 5 minutes behind

Do this:

- shorten the human-coding debrief by 2 minutes
- make `T2-HARDSHIP` Version 1 a 3-minute exercise
- skip partner discussion after the independent audit
- test Version 2 on only one passage

Do not speed-read the live demo.

---

# If you are 10 minutes behind

Skip the independent audit entirely.

For the hardship repair:

- use `bha_1561_001`
- use `bha_1573_004`
- use `bha_1574_001`
- write Version 2 as a group
- test only `bha_1594_014`

For the conclusion, use only the slides that cover:

- what we learned
- three kinds of problems
- the codebook
- the take-home workflow
- closing question

---

# If you are ahead of time

Do not fill the extra time with technical material.

Ask better methodological questions.

For example:

> Which Tier 1 code would you be comfortable applying to hundreds of passages?

> Which Tier 2 code would you check almost every time?

> Would you rather have a model miss some codes or over-code aggressively?

> What would you need to report in a methods section?

> At what point would you decide this workflow is creating more cleanup than it saves?

Those are better uses of extra time than explaining embeddings.

---

# Do not introduce these in this workshop

Unless someone asks at the very end, do not introduce:

- embeddings
- RAG
- fine-tuning
- tokenization
- temperature
- APIs
- vector databases
- agent architecture
- prompt-engineering jargon

None of that is necessary for what participants are doing.

It will make the workshop feel more technical than it is.

---

# Avoid saying

Avoid:

- “AI is objective.”
- “Humans are subjective.”
- “The model hallucinated, therefore AI is useless.”
- “The AI got the right answer.”
- “This is the gold standard.”
- “This proves the model is reliable.”
- “This proves the model is unreliable.”
- “This is safe to automate.”

Prefer:

- “Show me the evidence.”
- “Is that quote actually there?”
- “Does the code definition support that?”
- “What kind of disagreement is this?”
- “Would another reader understand why you made that choice?”
- “What would you change before using this on a larger corpus?”

---

# The simplest version of the workshop

If you lose your place, remember this:

## 1. People code first

Use:

- `codebook.md`
- `exercise_1_hand_coding.md`

## 2. People disagree

Ask why.

## 3. Leave `T2-HARDSHIP` unfinished

Write Version 1.

## 4. Run one fresh passage through AI twice

Use:

- `live_demo.md`
- two blank chats

## 5. Check the AI against the source

Use:

- `03_audit_ai_output.md`
- `corpus_32_passages.md`
- `precomputed_results.md`

## 6. Rewrite the code

Use:

- `04_repair_the_codebook.md`

## 7. Close

Use:

- `slides_conclusion.md`

That is the workshop.

---

# Final pre-class checklist

## Files

- [ ] `slides_intro.md` opens
- [ ] `01_hand_coding.md` opens
- [ ] `codebook.md` opens
- [ ] `exercise_1_hand_coding.md` opens
- [ ] `02_same_prompt_twice.md` opens
- [ ] `live_demo.md` opens
- [ ] `03_audit_ai_output.md` opens
- [ ] `corpus_32_passages.md` opens
- [ ] `precomputed_results.md` opens
- [ ] `04_repair_the_codebook.md` opens
- [ ] `slides_conclusion.md` opens

## Live demo

- [ ] AI chat account works
- [ ] Run 1 chat is blank
- [ ] Run 2 chat is blank
- [ ] I know which model is selected
- [ ] I wrote down the model name and date
- [ ] I know where the exact prompt is in `live_demo.md`

## Room

- [ ] Notifications are off
- [ ] Browser text is large enough to read
- [ ] Timer is ready
- [ ] Repository link is easy to share
- [ ] I have somewhere to write `T2-HARDSHIP — Version 1`
- [ ] I can find that Version 1 again later
- [ ] Optional paper copies of `codebook.md` and `exercise_1_hand_coding.md` are available

Then stop setting things up and teach.
