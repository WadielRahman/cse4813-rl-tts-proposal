# Reinforcement Learning and Test-Time Scaling for Improving Reasoning in LLMs

**A Deep Learning Perspective (2024–2026)**

Research proposal presentation for **CSE 4813 – Deep Learning**, United International University (UIU), Bangladesh.

- **Student:** [Student Name] ([Student ID])
- **Instructor:** [Instructor Name]
- **Semester:** [Semester]

## Overview

This repository holds a browser-based slide deck proposing a literature-based study, with an optional small experiment, of two approaches to improving reasoning in Large Language Models:

- **Reinforcement Learning (RL):** a training-time approach that changes model behaviour through reward feedback (e.g. PPO, GRPO).
- **Test-Time Scaling (TTS):** an inference-time approach that spends extra computation (more reasoning tokens, multiple samples, search, verification) without necessarily updating model parameters.

The slides cover background, the research problem, both approaches, a comparison, how they might be combined, existing research, research gaps, objectives and research questions, methodology, metrics and benchmarks, expected contributions and limitations, a timeline, and a mapping to the course outline.

> **Status:** This is a proposal. No experiments have been run and no results are reported.

## View the slides

- **Live deck:** `https://<your-username>.github.io/<repo-name>/` (after enabling GitHub Pages)
- **Locally:** download the repository and open `index.html` in any modern browser. No build step or internet connection is required.

## Controls

| Key / control | Action |
|---|---|
| → / Space / Next ▶ | Reveal next point, then next slide |
| ← / Prev ◀ | Previous point or slide |
| Home / End | First / last slide |

The deck scales to fit any screen at 16:9 and records the current slide in the URL hash (e.g. `#s5`).

## Project structure

```
index.html   # the entire deck (HTML, CSS and JavaScript, self-contained)
README.md
```

## Editing

1. Open `index.html` in a text editor.
2. Replace the bracketed placeholders (`[Student Name]`, `[Student ID]`, `[Instructor Name]`, `[Semester]`).
3. Adjust the timeline table on the "Expected Contributions, Limitations, Timeline" slide.
4. Each slide is a `<section class="s">` block. Elements with class `f` appear step by step.

## Key references

Verify each link and title before relying on it.

1. DeepSeek-AI (2025). *DeepSeek-R1*. arXiv:2501.12948
2. Snell, C. et al. (2025). *Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters*. ICLR 2025. arXiv:2408.03314
3. Xu, F. et al. (2025). *Towards Large Reasoning Models: A Survey of Reinforced Reasoning with Large Language Models*. arXiv:2501.09686
4. Pan, Q. et al. (2025). *A Survey of Slow Thinking-based Reasoning LLMs using Reinforced Learning and Inference-time Scaling Law*. arXiv:2505.02665

The full reference list is on the final slides of the deck. Most entries are arXiv preprints.

## Academic integrity

Explanations are written in the author's own words, and no experimental results, statistics or citations are claimed beyond those listed in the references. Illustrative equations and examples are labelled as simplified or constructed.
