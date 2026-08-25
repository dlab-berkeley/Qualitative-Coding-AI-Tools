# D-Lab Qualitative Coding with AI Tools Workshop

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for the D-Lab Qualitative Coding with AI
Tools workshop.

> **No installation, no programming, no API keys.** This workshop runs entirely in
> a web browser. There is no DataHub or Binder link because there is no code to
> run — see [Getting Set Up](#getting-set-up) below.

## Prerequisites

**No prior experience with programming or AI tools is required.** This workshop is
designed for researchers who have never written a line of code.

What we do assume: that you have read something closely and decided what was in
it. If you have hand-coded interview transcripts, fieldnotes, archival testimony,
or open-ended survey responses, you already have the skill this workshop is built
on.

Optional, and more useful afterwards than before:

- **Introduction to Qualitative Data Analysis** — if you have never built a codebook
- **Python Text Analysis** — if you want the programmatic version of this workflow

Check out D-Lab's [Workshop Catalog](https://dlab-berkeley.github.io/dlab-workshops/)
to browse all workshops, see what's running now, and review prerequisites.

## Workshop Goals

You have close-read a subset of your material and built a codebook. There are
seven hundred more documents.

In this workshop, we cover applying an existing, human-built codebook across a
large body of text using AI tools — and, more importantly, how to tell whether the
tool is doing what you think it is. First, we hand-code a passage on paper and
compare answers across the room. Then we have a chat tool code the same passage,
twice, and look at what changes. Then we use an agent to code forty passages at
once, and spend the rest of the session finding out where it failed and why.

We work with oral histories from the Bracero History Archive, in English and
Spanish.

## Learning Objectives

After this workshop, you will be able to:

- Distinguish coding tasks that are safe to delegate to an AI tool from tasks that
  are not, using evidence from your own run rather than intuition.
- Write a code definition precise enough that two people applying it reach the
  same answer.
- Apply a codebook across a body of text using a chat tool and an agent, without
  writing code.
- Check a model's coding against human coding, and read disagreement as
  information rather than as a score.
- Judge what may and may not be pasted into a consumer AI tool, given your own
  data and your own protocol.
- Document a coding run to the standard a methods section requires.

This workshop does not cover the following:

- **Inductive or emergent coding.** We assume your categories already exist. The
  interpretive work of building them is yours, and we are not automating it.
- **Building a codebook from scratch.** Covered in D-Lab's qualitative methods
  offerings.
- **Programmatic coding via API.** Covered in the follow-on session in this series,
  which uses a Python notebook and gives you reproducibility a chat window cannot.
- **Computing inter-coder reliability statistics.** We discuss what they are and
  why they matter, but do not calculate Cohen's kappa or Krippendorff's alpha.

## Getting Set Up

There is nothing to install. Do this **a few days before the workshop**, not the
night before.

1. **Make sure you can sign in** to the AI chat tool named in your workshop email,
   and that typing something gets you an answer back. Account problems are the most
   common reason people lose the first half hour.
2. **Check whether you have agent access.** The batch block uses Codex, which
   usually requires a paid plan. Look for it in your tool's sidebar.
   - *You have it* — nothing else to do.
   - *You don't* — completely fine, and expected. You will be paired with someone
     who does, and there is a pre-computed results file in this repository, so you
     miss none of the argument. **Do not buy a subscription for this workshop.**
3. **Download these workshop materials:**
   - Click the green "Code" button at the top right of this repository.
   - Click "Download ZIP".
   - Extract it somewhere you can find quickly — Desktop or Documents.
   - **Keep the folder intact.** The batch block needs `passages/` and
     `codebook.md` sitting side by side.
4. Optional, if you use git: `git clone https://github.com/dlab-berkeley/Qualitative-Coding-with-AI-Tools.git`

Full instructions, written for people who have never done any of this, are in
[`setup-guide.md`](setup-guide.md).

## Is the AI Tool Not Working on Your Computer?

Everything here has a fallback, and nobody sits out.

- **No account, or the tool is down?** The first half of the session is on paper.
  For the second half, open [`results-precomputed.md`](results-precomputed.md) — it
  contains a completed run over the same passages, and every exercise from that
  point works identically.
- **No Codex access?** Pair up with a neighbour, or use the same pre-computed file.
  Two people reading one results table is arguably better than one anyway.
- **Nothing working at all?** Come anyway, and arrive ten minutes early.

Because this workshop needs no installation and no CalNet ID, there is no DataHub
or Binder instance. If your department blocks the tool we name, tell us before the
day and we will sort out an alternative.

## Run the Materials

There is no code to run. During the session you work from two files:

1. **[`participant-handbook.md`](participant-handbook.md)** — open this at the start
   and keep it open. Every prompt you need to paste is in it, along with the
   worksheets for each exercise. You should never have to copy anything off a slide.
2. **[`codebook.md`](codebook.md)** — the ten codes we apply. You paste this into the
   chat tool as part of the prompt, and refer to it while hand-coding.

The passages live in [`passages/`](passages/), one short text file each. Open one in
any text editor to see what they look like — but **please do not code them before
the workshop**, since the first exercise depends on everyone meeting the passage
cold.

## Repository Contents

| File | What it is |
|---|---|
| `setup-guide.md` | Pre-workshop setup. Read this first. |
| `participant-handbook.md` | Prompts and worksheets. Work from this during the session. |
| `codebook.md` | The ten codes, in two tiers. |
| `passages/` | ~40 oral history passages, English and Spanish. |
| `gold-standard.md` | Eight passages coded by hand, for checking the model's work. |
| `results-precomputed.md` | A completed run, for anyone without agent access. |
| `lesson-plan.md` | The session structure. For facilitators, and for the curious. |

## Additional Resources

* [Bracero History Archive](https://braceroarchive.org/): The archive our passages
  come from — a project of the Roy Rosenzweig Center for History and New Media,
  the Smithsonian National Museum of American History, Brown University, and the
  Institute of Oral History at UT El Paso.
* [ScholarWorks@UTEP: Bracero Oral History Project](https://scholarworks.utep.edu/bracero/):
  Full interview transcripts as PDFs, item by item, with terms of use recorded on
  each record.
* Klaus Krippendorff, *Content Analysis: An Introduction to Its Methodology*: The
  standard reference on inter-coder reliability. Predates all of this and still
  applies.
* Johnny Saldaña, *The Coding Manual for Qualitative Researchers*: On coding
  practice, codebook construction, and what makes a definition hold up.
* [D-Lab Consulting](https://dlab.berkeley.edu/consulting): Free, one-to-one, and
  takes walk-ins. Bring your codebook and your material.

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance
data-intensive social science and humanities research. Our goal at D-Lab is to
provide practical training, staff support, resources, and space to enable you to
use computational tools for your own research applications. Our services cater to
all skill levels and no programming, statistical, or computer science backgrounds
are necessary. We offer these services in the form of workshops, one-to-one
consulting, and working groups that cover a variety of research topics, digital
tools, and programming languages.

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You
can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming
events, learn about how to utilize our
[consulting](https://dlab.berkeley.edu/consulting) and
[data](https://dlab.berkeley.edu/data) services, and check out upcoming
[workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab Workshops in This Series

## No Programming Required

- **Qualitative Coding with AI Tools** (this workshop)

## Building on This

- **Codebook Development with AI Tools** — using models to refine and stress-test
  code definitions
- **Evaluating Model Output at Scale** — agreement statistics, LLM-as-judge, and
  when to abandon a measure
- **Agentic Workflows for Large Corpora** — multi-step pipelines, provenance, and
  audit trails

*The follow-on sessions are in development. Tell us at the end of the workshop what
you would want in them.*

# Contributors

- **Allyson Kohen Tang** — D-Lab Curriculum Fellow; workshop design and materials
- **Pratik Sachdeva** — D-Lab; technical review


---

*Workshop materials licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
Interview transcripts are the property of the Institute of Oral History, The
University of Texas at El Paso, and are redistributed here under the terms of use
recorded on each interview's ScholarWorks record.*
