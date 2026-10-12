# D-Lab Qualitative Coding with AI Tools Workshop

[![Open Slides](https://img.shields.io/badge/open-slides%20-purple)](https://dlab-berkeley.github.io/Qualitative-Coding-AI-Tools/slides/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for the D-Lab Qualitative Coding with AI
Tools workshop.

## Prerequisites

**No prior experience with programming is required.** You should have some familiarity with using an AI tool like ChatGPT/Codex or Claude.

## Workshop Goals

Suppose you have read part of your material closely, built a codebook, and still
have hundreds of documents to code. An AI tool can apply the codebook to all of
them quickly. This workshop is about checking whether it applied the codebook
correctly.

We work with 32 short excerpts from oral histories about the Bracero Program,
from the Institute of Oral History at the University of Texas at El Paso. You
code six passages by hand and compare your coding with a partner's. You then have
an AI agent code one passage twice and compare the two runs. Next, you audit a
full set of AI coding results against the source text. Finally, you rewrite one
loosely defined code so that it can be applied consistently.

## Learning Objectives

After this workshop, you will be able to:

- Apply a codebook to a passage, supporting each code with an exact quotation.
- Identify where a disagreement between two coders comes from: the evidence they
  chose, how they read it, or how the code is defined.
- Run the same coding prompt twice through an AI agent and describe how the two
  outputs differ.
- Check AI-supplied quotations against the source text, and distinguish an
  inexact quotation, an accurate quotation that does not support the code, and a
  passage that supports more than one reading.
- Revise a vague code definition to state what it includes and excludes, and test
  the revision on new passages.

This workshop does not cover the following:

- **Inductive or emergent coding**
- **Building a codebook from scratch**
- **Programmatic coding via API**

## Getting Set Up

There is nothing to install. You should use an Agentic AI tool of your choice, such as Codex or Claude Code.

1. **Set up your coding agent.** Set up either Codex or Claude Code. If you are not sure how, check out our Agentic AI for Knowledge Work workshop.
2. **Download these workshop materials:**
   - Click the green "Code" button at the top right of this repository.
   - Click "Download ZIP".
   - Extract it somewhere you can find quickly — Desktop or Documents.
   - **Keep the folder intact.** The batch block needs `passages/` and
     `codebook.md` sitting side by side.
4. Optional, if you use git: `git clone https://github.com/dlab-berkeley/Qualitative-Coding-with-AI-Tools.git`

Full instructions, written for people who have never done any of this, are in
[`setup-guide.md`](setup-guide.md).

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

## Additional Resources

* [Bracero History Archive](https://braceroarchive.org/): The archive our passages
  come from — a project of the Roy Rosenzweig Center for History and New Media,
  the Smithsonian National Museum of American History, Brown University, and the
  Institute of Oral History at UT El Paso.
* [ScholarWorks@UTEP: Bracero Oral History Project](https://scholarworks.utep.edu/bracero/):
  Full interview transcripts as PDFs, item by item, with terms of use recorded on
  each record.

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

# Contributors

- **Allyson Kohen Tang**
- **Pratik Sachdeva**
- Claude Opus 5.5