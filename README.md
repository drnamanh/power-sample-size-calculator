# Power & Sample Size Calculator

Công cụ tính cỡ mẫu và power cho nghiên cứu dịch tễ, lâm sàng và cho các thiết kế transcriptomics (bulk RNA-seq, scRNA-seq và spatial transcriptomics).

Power and sample size calculator for epidemiology, clinical research and transcriptomics designs — Vietnamese / English / Korean (top-right language selector).

## Use

Open `index.html` in a browser, or enable GitHub Pages:

Settings → Pages → Deploy from a branch → Branch: `main`, Folder: `/ (root)` → Save.

Then open: `https://drnamanh.github.io/power-sample-size-calculator/`

## Calculators (16)

**Clinical & Epidemiology:** two-sample t-test, two proportions, paired t-test, Pearson correlation, log-rank survival, one proportion (with FPC)
**Clinical trials:** superiority, non-inferiority & equivalence (TOST) for continuous and binary outcomes
**Bulk RNA-seq:** Hart 2013 negative-binomial, DEPower (DESeq2-matched, preprint)
**scRNA-seq:** scPower pseudobulk, rare-cell capture (Poisson), scPS (Hsu et al., Bioinformatics 2024, GEE distribution-free + ICC)
**Spatial transcriptomics:** pseudobulk per core/TMA + design effect DEFF, PoweREST (Shui et al., PLoS Comput Biol 2025, Visium DEG in ROI), STORM (Li et al., bioRxiv 2026, preprint, analytic SVG power)

Preprint methods are labelled PREPRINT — not yet peer-reviewed.

## Source

Single self-contained HTML file (`index.html`, no build step, no server needed).
