# AI-Newton — if we can do it for physics, we can do it for medicine

Saved 2026-10-01. User note: if a machine can discover physical laws from raw experiments, the same job should be pointed at biology.

## Paper

- **Title:** AI-Newton: A Concept-Driven Physical Law Discovery System without Prior Physical Knowledge
- **Authors:** You-Le Fang, Dong-Shan Jian, Xiang Li, Yan-Qing Ma
- **arXiv:** https://arxiv.org/abs/2504.01538 (v1 2 Apr 2025, revised 11 Dec 2025)
- **PDF:** https://arxiv.org/pdf/2504.01538

## What it actually did

Unsupervised system. No physics textbook loaded in. Fed a large noisy set of classical mechanics experiments (about 46). It proposed interpretable concepts, wrote candidate laws, then generalized those laws across experiments.

It rediscovered:

- Newton’s second law
- conservation of energy
- universal gravitation

The interesting part is not that Newton was right. The interesting part is the loop: raw multi-experiment data → interpretable concept → law that holds outside the experiment it was fit on.

## Why it belongs in this arsenal

Medicine is still mostly one-experiment empirical models. A drug works in one trial, one tissue, one endpoint. The aging-rate and repair problems need the other thing: a law that is common across experiments.

Same doctrine, pointed at biology:

1. Pool raw multi-experiment data (organ clocks, injury time series, drug perturbations, single-cell states).
2. Propose interpretable concepts, not just a black-box score. Examples worth hunting: a repair-vs-scar switch, a homing address (as in the sLeX bone MSC edit), a safe reprogramming window, a vessel-growth term.
3. Demand the concept generalize. A law that only fits one cell line is not a law.
4. Hand the surviving concept to a wet lab or a trial, not to another paper.

## Limit

This paper is classical mechanics, not a patient. Rediscovering Newton from noisy lab rigs is easier than rediscovering why a lung scars. Biology is higher-dimensional, feedback-heavy, and the “experiment” is a person. The transfer is the method, not a claim that AI-Newton already knows medicine.

## Standing use

When a new regenerative result lands (bone homing, lung stem-cell pulse, eye reprogramming), ask the AI-Newton question: what concept is common across the experiments, and what would falsify it in the next tissue?
