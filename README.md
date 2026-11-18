# Conference Supplementary Material

Supplementary material for:

**A Critical-Path Guided Multi-agent Reinforcement Learning Framework based on Heterogeneous Graph Attention with Critical-Slack Action Ranking and Precedence-Certified Decoding for Reliability-Aware Dynamic Flexible Job Shop Scheduling under Machine Breakdowns**

## Files

- `CPR-PPO_Supplementary_Material.pdf` — compiled supplementary material (8 pages)
- `Manuscript_SupplementaryMaterial_.pdf` — identical copy kept for the original repository filename
- `source/` — LaTeX source, tables, and figure files

## Contents of the supplement

- Section I: notation and event mechanics (Table S1, Algorithm S1)
- Section II: mathematical model, feasibility, and MDP formulation
- Section III: heterogeneous graph and TRAE
- Section IV: CSAR, PCD, and CPR-S
- Section V: KACP training and convergence
- Section VI: complexity analysis
- Section VII: supplementary experimental statistics (Tables S4–S5, Figs. S1–S5)
- Section VIII: reproducibility protocol

## Build

```bash
cd source
pdflatex supplementary.tex
pdflatex supplementary.tex
```
