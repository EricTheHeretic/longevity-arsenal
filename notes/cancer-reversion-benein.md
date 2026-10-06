# Cancer reversion — BENEIN / KAIST

Added 2026-10-06. Source post: https://x.com/BrianRoemmele/status/2107318368764391582

**Paper:** Jeong-Ryeol Gong, Chun-Kyung Lee, Hoon-Min Kim, et al., Kwang-Hyun Cho. Control of Cellular Differentiation Trajectories for Cancer Reversion. *Advanced Science* 12(3), 2025. DOI: 10.1002/advs.202402132. KAIST.

## What it is

BENEIN (single-cell Boolean network inference and control) reads a single-cell transcriptome and proposes a small set of master regulators whose inhibition should push cells onto a normal differentiation path.

Applied to human large-intestine data, it named MYB, HDAC2, and FOXA2. Simultaneous knockdown in three colorectal cancer cell lines and in xenograft mice pushed cells toward a normal-like enterocyte state: more differentiation, less malignancy, transcriptomes closer to adjacent normal tissue in TCGA.

This is reversion, not killing. The cell is steered, not poisoned.

## Why it is in the arsenal

Same doctrine as partial reprogramming: change the program, keep the cell. If a cancer cell can be walked back to a differentiated state, the damage of treatment drops. The method is the transferable piece — a network-control loop that names a small target set, then checks it in cells and mice.

## Limit

Cell lines and xenografts. Not a human trial. Knockdown of three transcription factors is not a drug. Needs a deliverable inhibitor set, a tumor type where differentiation is the failure mode, and a trial that measures residual disease, not just a dish marker.
