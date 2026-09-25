# Lesson 3 — Audit the AI Output

**Time: about 15 minutes**

Up to this point, we have asked whether the AI gives stable answers.

Now we ask a different question:

> **Can we trust the evidence it gives us?**

Open these two files side by side:

- [`corpus_32_passages.md`](../packet/corpus_32_passages.md) — the source text
- [`precomputed_results.md`](../packet/precomputed_results.md) — the AI coding output

The results file is **not an answer key**. Treat it like a research assistant's work that needs to be checked.

---

## What are we checking?

There are at least three different things that can go wrong.

### 1. The quotation is not exact

The model may change a word, drop a phrase, or combine pieces of text while presenting the result as a direct quotation.

### 2. The quotation is real, but it does not support the code

A model can quote the source accurately and still make a weak coding decision.

### 3. The passage is genuinely ambiguous

Sometimes the model's answer is defensible, but another answer would also be defensible.

Those are different problems.

We want to learn how to tell them apart.

---

# Audit 1 — One word changed

Go to:

- source passage: `bha_1582_005`
- AI result: `bha_1582_005`

The AI gives this evidence for `T2-RETRO`:

> “it was a necessity thing... So they served a good purpose while they were here”

Now find that language in the source passage.

### What do you notice?

Write down the exact difference:

> 

### Does the difference matter?

- [ ] No. It changes nothing.
- [ ] Maybe. The meaning is close, but it is still not an exact quotation.
- [ ] Yes. It changes the meaning in a meaningful way.

Why?

- 

---

## What actually happened?

The source says:

> “it was a **necessary** thing.”

The AI reports:

> “it was a **necessity** thing.”

This is a very small change.

That is exactly why it matters.

The output still sounds plausible. A reader moving quickly might never notice it.

If we asked for a **verbatim evidence span**, however, this is not verbatim.

> **Close enough is not the same as exact.**

---

# Audit 2 — The invisible omission

Now go to:

- source passage: `bha_1590_004`
- AI result: `bha_1590_004`

For `T1-PROC`, the AI gives this quotation:

> “They'd pick a lock of cotton out of a bough instead of grabbing and pulling. They'd have to show them”

Find those sentences in the source.

### Is that one continuous quotation?

- [ ] Yes
- [ ] No

What is missing?

> 

---

## The missing sentence

The source actually says:

> “They'd pick a lock of cotton out of a bough instead of grabbing and pulling. **They'd pull one at a time.** They'd have to show them.”

The AI has silently removed a sentence and joined the two remaining pieces together.

The problem is not that researchers can never shorten a quotation.

We do it all the time.

The problem is that an omission should be visible:

> “They'd pick a lock of cotton out of a bough instead of grabbing and pulling... They'd have to show them.”

An ellipsis tells the reader that something has been removed.

Without it, the model has created a sentence sequence that does not actually appear in the source.

---

# Audit 3 — The quotation is real. Is the code?

Now go to:

- source passage: `bha_1588_003`
- AI result: `bha_1588_003`

The AI assigns `T1-WAGE` and gives this evidence:

> “I know I remember them sending money back home a lot, and I'm pretty sure it's probably money orders”

Check the quotation against the source.

This time, the wording is there.

So the quotation itself is not the problem.

Now return to the codebook.

### Does this fit `T1-WAGE`?

Remember that `T1-WAGE` is for a wage, pay rate, paycheck amount, deduction, or mechanism by which workers were paid.

What is happening in this quotation?

- 

Would you keep `T1-WAGE`?

- [ ] Yes
- [ ] No
- [ ] Unsure

Why?

- 

---

## This is a different kind of problem

The AI has not invented the evidence.

The question is whether **sending money home** is the same thing as describing **wages or a pay mechanism**.

You may disagree with someone else in the room.

That is fine.

But notice what kind of disagreement this is:

- the source text is not in dispute;
- the quotation is accurate;
- the question is whether the **code definition** covers what the passage describes.

That is a coding problem, not a quotation problem.

---

# Try one on your own

Pick **one other passage** from `precomputed_results.md`.

Do not choose one we have already discussed.

Check it against `corpus_32_passages.md`.

### Passage ID

`bha_`

### What did the AI assign?

- 

### What evidence did it give?

> 

### Which category best describes what you found?

- [ ] The quotation is exact and the code seems well supported.
- [ ] The quotation is not exact.
- [ ] The quotation is exact, but the code seems weak.
- [ ] Another code seems more appropriate.
- [ ] The passage is genuinely ambiguous.
- [ ] The codebook itself may need revision.
- [ ] Something else:

### Explain briefly

- 

---

# Compare with someone else

Compare the passage you checked with a partner.

You do not need to agree.

Instead, ask each other:

1. **Are we looking at the same source words?**
2. **Are we applying the same definition?**
3. **If we disagree, where exactly does the disagreement enter?**

---

# What counts as a model failure?

By now, you have seen several possibilities.

A model can:

- change source wording;
- silently combine non-contiguous text;
- quote accurately but apply a questionable code;
- make a defensible interpretation that differs from yours.

Those should not all be collapsed into a single category called “the AI was wrong.”

For qualitative research, the more useful question is:

> **What kind of disagreement or failure is this, and what should we change because of it?**

Sometimes the answer is: check the model more carefully.

Sometimes the answer is: rewrite the prompt.

Sometimes the answer is: revise the codebook.

And sometimes the answer is simply: this passage supports more than one reasonable interpretation.

---

## Keep this distinction for the next exercise

In the next part of the workshop, we return to `T2-HARDSHIP`.

We deliberately started with a loose definition.

Now that you have seen how both humans and AI use it, we can ask a more useful question than:

> “Who got it right?”

We can ask:

> **What would we have to change in the definition to make the next coding decision better?**
