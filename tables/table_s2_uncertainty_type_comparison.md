# Table S2. Reference-class failure compared with related forms of uncertainty

| Type | Definition | Reduced by more same-source data? | Typical detection route | Clinical example |
|---|---|---|---|---|
| Aleatoric uncertainty | Irreducible randomness within a valid class | No | Calibration within the class | Outcome variability among otherwise comparable patients |
| Sampling uncertainty | Finite-sample estimation noise | Yes | Learning curves, confidence intervals | Model improves as more representative cases accrue |
| Model uncertainty | Uncertainty about which specification is best | Partly | Model comparison, ensembling | Different model families disagree |
| Covariate shift | Change in P(X) | Sometimes | Input-distribution monitoring | New case mix at a deployment site |
| Concept shift | Change in P(Y given X) | Only with outcomes from the new mechanism | Subgroup and temporal calibration | Treatment-limitation pathway changes the outcome mechanism |
| Reference-class failure | No valid, transportable conditional for the individual case | No | Combined domain, subgroup, and outcome-level stress tests | End-of-life patient outside the development population's meaningful class |
