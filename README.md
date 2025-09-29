```markdown
# Benchmarking Expert Chatbot Personas

![Last Commit](https://img.shields.io/github/last-commit/tiffani3ng/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas)
![Repo Size](https://img.shields.io/github/repo-size/tiffani3ng/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas)

*A Mini-Project for IPHS 391 (Fall 2025) on persona prompt design and rubric-based benchmarking.*

---

## Overview

This repository explores **how effectively large language models (LLMs) can emulate designed personas** when guided by carefully engineered prompts. It provides:

* A **persona definition** and constraints,
* A **10-turn conversation transcript**,
* A **scoring rubric** and rubric history,
* A structured **report** synthesizing findings.

The goal is to make persona benchmarking **transparent, repeatable, and comparable** for both technical and non-technical audiences.

---

## Methodology

1. **Persona Prompt Engineering**

   * Crafted a detailed persona (biographical details, tone, quirks, conversational style).
   * Used constraint-based instructions (sentence length, emoji policy, capitalization/punctuation habits).
   * Iteratively refined prompts to balance **specificity** (to anchor the persona) with **flexibility** (to handle diverse inputs).

2. **Conversation Protocol**

   * Ran **10-turn dialogs** with the persona to elicit a range of behaviors (casual chat, preferences, references to background).
   * Kept user prompts consistent to enable fair comparison across iterations.

3. **Evaluation Framework**

   * Applied a **0–100 point rubric** with weighted factors that assess:

     * Persona alignment with the system prompt,
     * Style/voice fidelity,
     * Contextual responsiveness,
     * Creativity and depth,
     * Engagement and coherence,
     * Adherence to explicit prompt constraints.

---

## Results

* **Overall Score:** **90/100**
* **Strengths:** Coherent, engaging replies; conversational flow matched the intended “roommate/friend” dynamic.
* **Weaknesses:** Inconsistent enforcement of persona-specific quirks (e.g., strict tone/emoji/capitalization rules).

**Key Takeaway:** Even with strong prompt engineering, LLMs tend to drift toward generic styles during longer conversations. A structured rubric surfaces these gaps and enables targeted prompt revisions.

---

## Highlight: Persona Prompt Techniques

* **Constraint-based style controls:** sentence length limits, emoji policies, capitalization/punctuation rules.
* **Behavioral quirks:** casual shorthand, emphasis patterns, “voice” tics to differentiate from generic chat.
* **Grounded backstory:** academic, cultural, and social context to steer factual anchors and references.
* **Iteration loop:** refine → converse → score → adjust weights/constraints (tracked in rubric and metaprompt histories).

---

## Files Description

* **`mp1_chatbot_report.docx`** — Full project write-up (overview, methods, results, discussion).
* **`prompt_persona.txt`** — The persona’s system prompt and stylistic constraints used for evaluation.
* **`chat_history.md`** — 10-turn conversation transcript used to assess persona fidelity.
* **`chat_rubric.txt`** — Rubric with factors, behavioral indicators, and weights (0–100 scoring).
* **`chat_rubric_history.md`** — Versioned notes on rubric changes (what changed and why).
* **`metaprompt_history.txt`** — Iterations and notes on the metaprompt/persona prompt design.
* **`README.md`** — This landing page.

---

## Usage Instructions

### Quick Start (Replicate the Study)

1. **Clone:**

   ```bash
   git clone https://github.com/tiffani3ng/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas.git
   cd iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas
   ```
2. **Review the Persona & Rubric:**

   * Open `prompt_persona.txt` and `chat_rubric.txt`.
3. **Run a 10-Turn Conversation:**

   * Paste the persona prompt into your LLM (e.g., ChatGPT).
   * Conduct a 10-turn exchange (keep your prompts consistent if comparing versions).
4. **Score with the Rubric:**

   * Use `chat_rubric.txt` to grade each factor (apply weights to compute 0–100).
5. **Compare & Iterate:**

   * Log scores and observations.
   * Adjust constraints and re-test; record changes in `chat_rubric_history.md` and/or `metaprompt_history.txt`.

### Reusing the Rubric

* Keep factors and weights consistent across tests to ensure **fair comparisons**.
* If you modify weights, document rationale in `chat_rubric_history.md`.

---

## Installation

No code build is required. Any modern LLM interface is sufficient to replicate the conversation and scoring workflow.

---

## Contributing

Contributions are welcome! Consider:

* Proposing rubric refinements or alternative factor definitions,
* Adding new personas and transcripts,
* Sharing comparative results across models.

Open a PR with a clear summary of changes and rationale. For substantial changes (e.g., rubric weights), include notes in `chat_rubric_history.md`.

---

## Acknowledgments

Developed as part of **IPHS 391 (Fall 2025)**.

---
```
