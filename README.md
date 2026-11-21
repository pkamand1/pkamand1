# Patricia Kamanda

I am a data scientist working across biomedical signal processing, multi-omics, and health informatics. My work pairs statistical modeling and machine learning with several years as an applications scientist in the sequencing industry, where I built and supported analysis pipelines for research and clinical laboratories.

## What I work on

- Physiological signal processing and deep learning for ECG in Python, including the validation of wearable device measurements against clinical reference signals (NeuroKit2, HeartPy, statsmodels, PyTorch)
- Transcriptomic, proteomic, and metabolomic analysis, from bulk and single-cell RNA-seq to RPPA and LC-MS data
- Reproducible sequencing pipelines in Nextflow with Docker and Singularity
- Clinical and longitudinal data, with mixed models, survival analysis, SQL, and SAS
- Clinical operations and trial data: scheduling and billing analytics, CDISC SDTM, edit checks, and risk-based monitoring
- Analytics engineering and decision science: layered SQL warehouses, dbt, query tuning, forecasting, and optimization
- [ClinInfoJobs.com](https://clininfojobs.com), a job board I built and run for health informatics roles that do not require a clinical license, automated end to end with GitHub Actions

## Selected projects

### Signal processing and machine learning

| Project | What it shows |
| --- | --- |
| [ecg-heartbeat-classification-pytorch](https://github.com/pkamand1/ecg-heartbeat-classification-pytorch) | A 1D residual network in PyTorch against classical baselines, evaluated on unseen patients |

### Clinical and health data

| Project | What it shows |
| --- | --- |
| [ambulatory-clinic-operations-analytics](https://github.com/pkamand1/ambulatory-clinic-operations-analytics) | A SQL star schema for Power BI, no-show prediction, a difference-in-differences evaluation of text reminders, provider productivity, charge lag, and coding review |
| [clinical-trial-data-management](https://github.com/pkamand1/clinical-trial-data-management) | Edit checks and query listings, protocol deviations, CDISC SDTM mapping with XPT output and conformance checks, and risk-based site monitoring |
| [pbc-longitudinal-survival](https://github.com/pkamand1/pbc-longitudinal-survival) | Linear mixed models, Cox and time-dependent Cox models, and competing risks in R |
| [sas-sql-longitudinal-cohort](https://github.com/pkamand1/sas-sql-longitudinal-cohort) | Cohort construction, data quality checks, and medication adherence in MySQL and SAS |

### Analytics engineering and optimization

| Project | What it shows |
| --- | --- |
| [game-telemetry-sql-analytics](https://github.com/pkamand1/game-telemetry-sql-analytics) | A layered MySQL warehouse with stored procedures, views, partitioning, and measured query tuning; the same models in dbt with tests; retention, stability, and bot detection |
| [inventory-fulfillment-optimization](https://github.com/pkamand1/inventory-fulfillment-optimization) | An explainable demand forecast, deterministic and stochastic linear programs, Monte Carlo policy evaluation, and replenishment simulation |

### Genomics and omics

| Project | What it shows |
| --- | --- |
| [nf-viral-consensus](https://github.com/pkamand1/nf-viral-consensus) | A Nextflow pipeline for viral whole-genome sequencing, from QC to phylogeny |
| [nf-metagenomic-classification](https://github.com/pkamand1/nf-metagenomic-classification) | A Nextflow pipeline for quality control, host read removal, and taxonomic classification of short and long reads |
| [scrnaseq-pbmc-interferon](https://github.com/pkamand1/scrnaseq-pbmc-interferon) | Single-cell RNA-seq in Python with Scanpy, Harmony integration, and pseudobulk PyDESeq2 |
| [scrnaseq-pseudobulk-benchmark](https://github.com/pkamand1/scrnaseq-pseudobulk-benchmark) | Why cell-level tests flood multi-donor studies with false positives, and how pseudobulk avoids it, on simulated data with known truth |
| [rnaseq-deseq2-paired-design](https://github.com/pkamand1/rnaseq-deseq2-paired-design) | A paired-design bulk RNA-seq analysis with DESeq2 |
| [bulk-rnaseq-de-benchmark](https://github.com/pkamand1/bulk-rnaseq-de-benchmark) | DESeq2, edgeR, limma-voom, and simpler tests compared on simulated counts: false discovery control, power, and outliers |
| [tcga-brca-rppa-proteomics](https://github.com/pkamand1/tcga-brca-rppa-proteomics) | limma subtype differences, clustering, and survival models on TCGA proteomics |
| [melanoma-pdx-rppa-treatment-analysis](https://github.com/pkamand1/melanoma-pdx-rppa-treatment-analysis) | Protein and phosphoprotein responses of melanoma xenografts to BRAF and MEK inhibition, dasatinib, and their combination |
| [urine-metabolomics-age-bmi-sex](https://github.com/pkamand1/urine-metabolomics-age-bmi-sex) | Untargeted urinary metabolomics with univariate testing and OPLS-DA |
| [ckd-exercise-serum-metabolomics](https://github.com/pkamand1/ckd-exercise-serum-metabolomics) | Targeted serum metabolomics of chronic kidney disease with and without voluntary exercise |
| [metabolomics-drift-imputation-benchmark](https://github.com/pkamand1/metabolomics-drift-imputation-benchmark) | QC-based drift correction and missing-value imputation for LC-MS, compared on simulated studies |
| [culex-pipiens-sex-biased-expression-reanalysis](https://github.com/pkamand1/culex-pipiens-sex-biased-expression-reanalysis) | A reanalysis of published RNA-seq expression data (Martynova, Kamanda & Sim, 2022) |

## Tools

Python, R, SQL (MySQL, DuckDB, dbt), SAS, Nextflow, Docker, Singularity, Scanpy, DESeq2, edgeR, limma, scikit-learn, statsmodels, PuLP, PyTorch, Power BI, Tableau, Plotly Dash, and GitHub Actions.

## Find me

[clininfojobs.com](https://clininfojobs.com) · [ORCID](https://orcid.org/0000-0003-1046-1225)
