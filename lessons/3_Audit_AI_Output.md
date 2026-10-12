# Qualitative Coding with AI Tools: Audit the AI Output

### Learning Objectives

- Check an AI's quoted evidence against the source, word for word.
- Judge whether accurate evidence actually supports the assigned code.
- Distinguish quotation errors, coding errors, and genuine ambiguity.

### Icons Used in This Notebook
🥊 **Challenge**: Interactive exercise. We'll work through these in the workshop!<br>
⚠️ **Warning:** Heads-up about tricky stuff or common mistakes.<br>

### Sections
1. [Checking the AI's Evidence](#section1)
2. [Challenge 1: Check Three Coding Decisions](#section2)
3. [Challenge 2: Audit a Passage on Your Own](#section3)

<a id='section1'></a>

# Checking the AI's Evidence

In the last lesson, we used an AI agent to code a sample text multiple times. You may have found that you obtained different results across runs. In this part, we will audit the AI outputs to better understand how it codes the results.

Open [`AI_Coding_Results.md`](../data/AI_Coding_Results.md), a precomputed AI coding run, side by side with [`Source_Passages.md`](../data/Source_Passages.md), the original passages.

⚠️ **Warning:** The results file is **not an answer key**. These coding results were generated in September 2026 using Codex, and so may not look like results you obtain whenever you take this workshop.

When a coding decision looks wrong, it's usually for one of three reasons:

- **The quotation is not exact.** The AI changed or dropped words but still presents the text as a direct quotation.
- **The quotation is exact, but it does not support the code.** The evidence is real; the coding decision is weak.
- **The passage is genuinely ambiguous.** The AI's answer may be defensible and simply depend on viewpoint or chance.

<a id='section2'></a>

## 🥊 Challenge 1: Check Three Coding Decisions

For each decision below, find the AI's quotation in the source passage. Is it exact? If so, does it support the code? Check the code's definition in [`codebook.md`](codebook.md).

| Passage | Code | AI's evidence |
|---|---|---|
| `bha_1582_005` | `T2-RETRO` | "it was a necessity thing... So they served a good purpose while they were here" |
| `bha_1590_004` | `T1-PROC` | "They'd pick a lock of cotton out of a bough instead of grabbing and pulling. They'd have to show them" |
| `bha_1588_003` | `T1-WAGE` | "I know I remember them sending money back home a lot, and I'm pretty sure it's probably money orders" |


<a id='section3'></a>

## 🥊 Challenge 2: Audit a Passage on Your Own

Pick **one other passage** in `AI_Coding_Results.md` and check every code the AI assigned against the source and the codebook. Decide which of the three problems above, if any, you find.

Then, compare with a partner. If you disagree, try and pointpoint why: are you looking at different words, applying different definitions, or reading an ambiguous passage differently?

Each kind of problem calls for a different fix. Quotation errors mean the output needs to be checked; coding errors may mean the codebook needs to be clearer; and genuine ambiguity may need no fix at all. In the next lesson, we return to `T2-HARDSHIP` and ask what we would have to change in its definition to make the next coding decision better.
