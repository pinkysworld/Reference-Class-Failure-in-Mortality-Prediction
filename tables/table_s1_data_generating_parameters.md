# Table S1. Data-generating parameters

| Component | Value |
|---|---|
| Feature order | age, comorbidity_burden, organ_dysfunction_score, treatment_intensity, inflammatory_burden, frailty |
| beta_reference | [0.70, 0.60, 0.95, -0.50, 0.55, 0.85] |
| beta_novel | [0.20, 0.55, 1.70, 1.25, 0.95, 1.55] |
| mu_reference | [0, 0, 0, 0, 0, 0] |
| mu_novel | [0.30, 0.25, 0.45, 0.40, 0.30, 0.55] |
| covariance | identity matrix in both regimes |
| intercept_reference (b0) | -0.95 |
| intercept_novel (b0) | -0.20 |
| reference prevalence | ~0.35 |
| novel prevalence | ~0.76 |
| reference Bayes (aleatoric) Brier | 0.151 |
| novel Bayes (aleatoric) Brier | 0.092 |
| training sizes | [250, 500, 1000, 2000, 4000, 8000] |
| test set per regime | 6000 |
| random seeds | 0 to seeds-1; generation streams seeded by default_rng(1000 + seed) |

Outcome model in each regime: P(Y = 1 | X = x) = sigmoid(b0 + beta . x).
