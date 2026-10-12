# Qualitative Coding with AI Tools: AI Coding

### Learning Objectives

- Run the same coding prompt in two independent chats.
- Compare two AI outputs on codes, evidence, and stated ambiguity.
- Explain why a single run is not evidence that a procedure is reliable.

### Icons Used in This Notebook
⚠️ **Warning:** Heads-up about tricky stuff or common mistakes.<br>

### Sections
1. [Qualitative Coding with an AI Agent](#section1)
2. [Apply the Codebook with AI: Run 1](#section2)
3. [Apply the Codebook with AI: Run 2](#section3)
4. [Compare the Two Runs](#section4)

<a id='section1'></a>

# Qualitative Coding with an AI Agent

We're going to use an AI agent (feel free to use your favorite one, likely either Codex or Claude Code) to apply the codebook to the following passage:

## `bha_1574_003`: Raymundo Villa

> **Interviewer:** How would they change? Like if you saw one just over, and then after a few months and maybe the second year, were they dressed differently? Did they act differently? Were they a little more confident?
>
> **Villa:** The first year that they came, they were kind of a little bit raw, they didn’t know exactly what they were up against, but then the second time, I’d see them, they’d be a little more prepared. They knew what they were up against, and they kind of prepared a little better for what they were going to encounter here.
>
> **Interviewer:** Some people have suggested that they’re very submissive, *humildes*, and then you could see where they got a little bit more assertive and more confident. Did you see some of that?
>
> **Villa:** You could tell that they were getting a little more confident. At first, they were kinda like scared, very humiliated, they were scared to say anything, but second, third year, you could tell that they were more assertive. They could talk to you. At first, they wouldn’t even talk to you. They wouldn’t trust you at all.
>
> **Interviewer:** Would they even look you in the eye?
>
> **Villa:** They wouldn’t even look you in the eye, “Sí patronsito,” but then towards the end, they got a little more confident. Then they got to where they trusted you. At first, they didn’t trust you at all; you had to earn their trust.

**Source:** Raymundo Villa, interview no. 1574, Bracero Oral History Project, Institute of Oral History, University of Texas at El Paso.

We're going to code this passage **two separate times** in order to see if the AI agent is consistent.

<a id='section2'></a>

# Apply the Codebook with AI: Run 1

Open a **new chat** in your AI agent. Then, either (1) obtain the full workshop [codebook](codebook.md) and attach it to the chat, or (2) point the AI agent to this folder.

Then, paste the passage above, followed by the prompt that matches your setup.

**If you attached the codebook:**

```text
Using the codebook I provided, code this passage.

For every code you assign:

1. give the code;
2. quote the exact words from the passage that support it; and
3. explain your choice in one or two sentences.

Do not assign a code unless you can support it with an exact quotation from the passage.

More than one code may apply.

At the end, tell me which coding decision, if any, you found most ambiguous and why.
```

**If you pointed the AI agent to this folder:**

```text
Using the codebook in lessons/codebook.md, code this passage. Read only lessons/codebook.md. Do not open any other files in this folder.

For every code you assign:

1. give the code;
2. quote the exact words from the passage that support it; and
3. explain your choice in one or two sentences.

Do not assign a code unless you can support it with an exact quotation from the passage.

More than one code may apply.

At the end, tell me which coding decision, if any, you found most ambiguous and why.
```

Go ahead and send the prompt. What do you find? Do you agree with the results?

<a id='section3'></a>

# Apply the Codebook with AI: Run 2

Now open a **second, completely new chat**, and repeat the exercise above. That is, ask the AI agent, in a new conversation, to apply the codebook to the passage.

⚠️ **Warning:** Do not continue in the first conversation for Run 2.

<a id='section4'></a>

# Compare the Two Runs

Compare the codes obtained from each run. Do you notice the same codes, and the same evidence? Did both runs flag the same decision as ambiguous? What differences do you identify?

There are many variations you could consider pursuing to investigate further:
- You could run a different model.
- You could apply a different reasoning effort.
- You could use a different prompt.

The key takeaway here is that the applied codes you receive may not be consistent when using an AI agent. However, this does not mean the AI agent is useless. For example, humans aren't perfectly consistent either when applying codes.

So how do we decide which output to trust? In the next lesson, we check the AI's evidence against the source.