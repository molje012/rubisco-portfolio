# Rubisco Biochemical Landscape — Analysis

Reproduction of key figures from:
Prywes et al. (2025) "A map of the rubisco biochemical landscape." Nature.

## Contents
- `rubisco_analiza.ipynb` — fitness vs KC scatter plot
- `HeatmapPractice.ipynb` — fitness heatmap of the active site region (Fig. 1g)
- `reliability_analysis.ipynb` — original analysis: why dead mutants have unreliable KC fits (99.6% of dead mutants have CoV > 1)
## Dataset
Supplementary Data 2 from the original paper — enrichments, Vmax and KC values 
for 8,760 single amino acid mutants of R. rubrum rubisco.

## Key findings reproduced
- Bimodal fitness distribution (dead vs neutral mutations)
- A102Y and V266T as improved CO2 affinity mutants
- Active site positions (K166, K191, K329) show near-zero fitness tolerance
