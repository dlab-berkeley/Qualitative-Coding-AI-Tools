# Qualitative Coding with AI Tools: Repair the Codebook

### Learning Objectives

- Use contrasting passages to find the boundaries of a loosely defined code.
- Write a code definition that states what it captures, when to apply it, what evidence looks like, and what to exclude.
- Test a revised definition against new passages.

### Icons Used in This Notebook
🥊 **Challenge**: Interactive exercise. We'll work through these in the workshop!<br>
💡 **Tip**: How to do something a bit more efficiently or effectively.<br>

### Sections
1. [Repairing `T2-HARDSHIP`](#section1)
2. [Challenge 1: Find the Boundaries](#section2)
3. [Challenge 2: Rewrite the Definition](#section3)
4. [Challenge 3: Test and Compare](#section4)
5. [What We Repaired](#section5)

<a id='section1'></a>

# Repairing the `T2-HARDSHIP`Code

We deliberately gave the code `T2-HARDSHIP` a loose definition in the [codebook](codebook.md). By now, you may have seen AI tools (and perhaps humans) apply it inconsistently. When a coding from an AI model is inconsistent, it could suggest an issue with the way in which we're running the experiment, whether we're using the wrong model, too low a reasoning effort, or our prompt is not clear enough. But often times, it could simply mean that our code is not well defined.

<a id='section2'></a>

## 🥊 Challenge 1: Establishing the Boundaries of `T2-HARDSHIP`.

Let's dive deeper into this code and see if we can better interrogate why it might not be precise enough. The first passage below is a fairly clear case of hardship. The other three are less clear; when we ran the coding, the AI agent did not code them as hardship.

For each scenario, review the full passage (it's linked in the first column), and decide whether it should receive `T2-HARDSHIP`. Then, identify why it should receive that code - whether it stems from the facts of the scenario or the narrator's framing (or both).

| Passage | Evidence | What to consider | AI's code |
|---|---|---|---|
| [`bha_1561_004`](../data/Source_Passages.md#bha_1561_004) | "Those were hard times"; "my mom and dad were very proud of not going and applying for welfare, but we finally had to"; "just to make enough money to go buy a dozen eggs and some tortillas" | Material need, and the narrator calls it hard | [`T2-HARDSHIP`](../data/AI_Coding_Results.md#bha_1561_004) |
| [`bha_1561_003`](../data/Source_Passages.md#bha_1561_003) | "He's scared because he really thought that they were going to take him."; "It was hilarious" | Real fear, told as a family joke | [`T2-AMBIV`](../data/AI_Coding_Results.md#bha_1561_003) |
| [`bha_1592_002`](../data/Source_Passages.md#bha_1592_002) | "back-breaking labor"; "These guys are really here to get ahead, to work." | Physical toll, framed by an onlooker as an admirable work ethic | [`T2-DIGNITY`](../data/AI_Coding_Results.md#bha_1592_002) |
| [`bha_1593_027`](../data/Source_Passages.md#bha_1593_027) | "he didn't complain about what he made"; "But the Hispanic contract was the same. That didn't go up." | Unequal pay, presented by the grower's son as contentment | [`T2-NEGCOMP`](../data/AI_Coding_Results.md#bha_1593_027) |


<a id='section3'></a>

## 🥊 Challenge 2: Rewrite the Definition

Write Version 2 of `T2-HARDSHIP`, specific enough that another reader, or an AI agent, could apply it the way you would. Use the same four parts as the other codes in the codebook:

- **What this code captures**
- **Use this code when**
- **Evidence should look like**
- **Do not use this code when**

<a id='section4'></a>

## 🥊 Challenge 3: Apply the New Definition

Now, apply your Version 2 definition to the following three passages to see if it is precise enough.

| Passage | Evidence | AI's code |
|---|---|---|
| [`bha_1594_014`](../data/Source_Passages.md#bha_1594_014) | "we slept under the vehicles away from the sun, and we ate from the ground."; "to this day I know that" | [`T2-AMBIV`](../data/AI_Coding_Results.md#bha_1594_014) |
| [`bha_1588_004`](../data/Source_Passages.md#bha_1588_004) | "I felt so sorry for him because he couldn't stay, and I remember him crying when he left" | [`T2-DIGNITY`](../data/AI_Coding_Results.md#bha_1588_004) |
| [`bha_1591_007`](../data/Source_Passages.md#bha_1591_007) | "Dad — gave my dad a stomachache to think about them eating all that."; "apparently they liked it" | [`T2-AMBIV`](../data/AI_Coding_Results.md#bha_1591_007) |

Do this in two ways: apply the code yourself, and ask an AI agent to apply it using the prompt from before.

Do you get more consistent results?

<a id='section5'></a>

# What We Repaired

AI agents need precise instructions in order to complete their tasks effectively. Consider the following two prompts:

> Code this passage for hardship.

> Apply `T2-HARDSHIP` only when the passage describes a materially, physically, socially, or emotionally adverse condition **and** the text gives evidence that the condition is experienced, framed, or treated as consequential. Do not infer hardship solely from historical knowledge that the situation was exploitative.

The second is more precise, and more actionable by an AI model. It is also more auditable. Humans can go back and review the codes, and better understand why an AI model may or may not have applied a code.