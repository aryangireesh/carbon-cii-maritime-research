# Carbon CII maritime research artifact

This repository accompanies a study that predicts annual vessel fuel consumption from matched EU MRV and vessel-characteristics data, then separately assesses IMO Carbon Intensity Indicator (CII) rating transitions under an evaluated emissions scenario.

The reproducibility archive below contains project analysis scripts, the derived analytical dataset, supporting results, source provenance, and the paper's figures. It does not contain the manuscript's author/title page or corresponding-author contact details.

[Download the complete code and data archive](Carbon_CII_Public_Repository.zip)

## Key results

- Matched analytical cohort: 4,515 vessels.
- Nested five-fold XGBoost validation: R² 0.9477 ± 0.0164; MAE 467.65 ± 41.84 tonnes; RMSE 1,014.75 ± 201.92 tonnes (outer-fold mean ± population SD).
- Separate deterministic CII scenario: 4,126 paired vessels; 858 improved, 2,167 unchanged, and 1,101 worsened.

The emissions scenario is not a forecast or causal estimate. The CII rating transition table is not a classifier confusion matrix.

## Reproducibility and source notes

Instructions, data source links, checksums, and rights notes are in the archive. No reuse licence is assigned to the combined dataset or project code in this release.
