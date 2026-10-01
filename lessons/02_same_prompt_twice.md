# Lesson 2 — Run the Same Prompt Twice

**Time: about 8 minutes**

Now we bring in the AI.

But we are not asking whether it can produce an answer.

We are asking whether it produces the **same kind of answer twice**.

---

## Open this file

Use:

- [`live_demo.md`](lessons/live_demo.md)

It contains:

- the passage;
- the exact prompt;
- the instructions for Run 1 and Run 2; and
- a comparison table.

---

# What we are testing

The setup is simple:

> **same codebook + same passage + same prompt**

We will run that setup twice in two separate chats.

Nothing in the instructions changes.

The question is:

> **Does the model make the same coding decisions twice?**

---

# Why a new chat matters

For the second run, start a completely new chat.

Do not continue in the first conversation.

We want the two runs to be independent.

You do not need to understand anything technical about how the model works.

For this exercise, the important point is simply that the second answer should not be influenced by the first conversation.

---

# What to watch for

As the two answers appear, compare:

- which Tier 1 codes were assigned;
- which Tier 2 codes were assigned;
- which exact words the model used as evidence;
- what the model said was ambiguous;
- whether one answer seems more confident than the other.

Do not focus only on whether the code labels match.

Two runs may assign the same code but justify it differently.

That difference matters too.

---

# Do not correct the model yet

If you notice something questionable, make a note of it.

Do not immediately argue with the model or ask it to revise the answer.

We want to preserve the original output long enough to compare the two runs.

---

# Discuss

After both runs, use the comparison table in `live_demo.md`.

Ask:

- Did the model assign exactly the same codes?
- Did it use the same evidence?
- Did one run see ambiguity that the other did not?
- Are both answers defensible?
- If they differ, is the problem the model—or is the codebook leaving room for multiple interpretations?

---

# The point

A polished AI response can feel definitive.

But one run tells us very little about stability.

If the same passage and the same instructions produce different coding decisions, then:

> **“It worked once” is not evidence that the procedure is reliable.**

That does not mean every difference is a failure.

Some passages are genuinely ambiguous.

Some code definitions are loose.

Some model behavior is inconsistent.

The next lesson is about telling those possibilities apart.

---

## Next

Continue to:

[`03_audit_ai_output.md`](03_audit_ai_output.md)
