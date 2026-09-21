# BLAZAR_I reproducibility package — v1.0.0

**Associated article:**  
*Population-Scale Optical Variability of Fermi Blazars in ZTF: Stochastic Timescales, Diagnostic Calibration, and Sampling Effects*

**Authors:** Davron Mirzaqulov, Sobir Turaev, Shuhrat Ehgamberdiev

## Purpose

This Zenodo-ready archive contains the principal analysis code, machine-readable final tables,
vector figure products, and provenance documentation supporting the BLAZAR_I population study
of optical variability in Fermi blazars with ZTF.

**The manuscript and manuscript source files are intentionally excluded.**

## Archive contents

- `scripts/` — data acquisition, cleaning, core diagnostics, robustness tests,
  confounder analyses, injection–recovery calibration, and temporal validation.
- `tables/` — machine-readable CSV versions of the principal final numerical results.
- `figures/` — publication vector-PDF figure products.
- `environment/` — Python environment guidance.
- `metadata/` — Zenodo metadata template and file-level checksums.
- `docs/` — data-access, provenance, pipeline order, and licensing notes.

## Not included

This archive deliberately excludes:

- manuscript LaTeX sources,
- manuscript PDF,
- bibliography files,
- cover letters or journal submission files,
- private credentials/tokens,
- raw bulk Fermi-LAT and ZTF survey products.

The public external survey/catalog products remain under the provenance and terms of their
original providers. Full reconstruction starts by obtaining those inputs from the original
services and then running the numbered scripts.

## Final analysis sample

The final GOLD+SILVER analysis sample contains **1061 blazars**:
**727 BL Lacs** and **334 FSRQs**.

## Scientific interpretation hierarchy

1. **Primary:** temporally reproducible population-level rest-frame DRW-timescale contrast
   between FSRQs and BL Lacs.
2. **Conditional supporting:** raw rms-flux / colour-curvature co-occurrence, which is not
   retained after optical dynamic-range adjustment.
3. **Secondary:** class-specific binary endpoint incidences.
4. **Descriptive only:** double-lognormal / mixture-like flux-PDF classifications.

The corresponding numerical values and caveats are stored in
`tables/final_claim_hierarchy.csv`.

## Citation

After Zenodo assigns the DOI, cite this archive separately from the journal article.
A `CITATION.cff` file is included and can be updated with the assigned DOI.

## Version

**v1.0.0** — first Zenodo-ready reproducibility release.
