# Cardiovascular Digital Twin for LVAD Fault Analysis

**James Vu** — Engineering Honours, UNSW Canberra
Supplementary results for poster presented at Poster Day.

## Contents
- [Overview](#overview)
- [Model](#model)
- [Results](#results)
- [Data and code](#data-and-code)

## Overview

Two or three sentences on what the project does and why. Assume the
reader just walked away from your poster and wants the detail you
didn't have room for.

## Model

![Model schematic](figures/model-schematic.png)
*Fig. 1 — Lumped-parameter circulation model with LVAD coupling.*

## Results

| Condition | CO (L/min) | MAP (mmHg) | Recovery time (s) |
|---|---|---|---|
| Baseline | 5.2 | 92 | — |
| Fault A | 3.8 | 71 | 14.2 |
| Fault B | 4.1 | 78 | 9.6 |

![Pressure-volume loops](figures/pv-loops.png)
*Fig. 2 — PV loops under baseline and fault conditions.*

<details>
<summary><b>Sensitivity analysis (8 further figures)</b></summary>

![Sensitivity sweep](figures/sensitivity-01.png)
*Fig. 3 — ...*

</details>

## Data and code

- [`data/results.csv`](data/results.csv) — full numerical results
- [`src/`](src/) — simulation code
- [`poster.pdf`](poster.pdf) — the poster itself

## Contact

[your email] · [supervisor, if appropriate]
