# ARC-style open problems

Open mathematical problems in the style of the Alignment Research Center (ARC), such as mechanistic estimation and the no-coincidence principle, one folder per problem.

| Folder | Problem |
| --- | --- |
| [`arc-msp/`](arc-msp/) | Can the sample-free estimators of Wu et al. ([arXiv:2605.05179](https://arxiv.org/abs/2605.05179)), which beat Monte Carlo sampling for wide random MLPs at initialisation, be extended to Gibbs posteriors (Question 1) and to Hennick's local Gaussian law for SGD (Question 2)? |
| [`arc-ncp/`](arc-ncp/) | Prove or refute ARC's no-coincidence principle (Neyman, 2025) for random reversible circuits, and its analogue for cliques in Erdős–Rényi graphs. |

Build a problem's PDF with `latexmk -pdf -synctex=1 <file>.tex` inside its folder.
