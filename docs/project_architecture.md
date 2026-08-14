# NGS Assay Validation Framework Architecture

## Objective
Develop a reproducible framework for evaluating NGS assay performance using GIAB benchmark datasets.

## Inputs
- GIAB HG002 BAM
- GIAB Truth VCF
- GIAB Benchmark BED

## Outputs
- Coverage statistics
- QC metrics
- TP/FP/FN counts
- Precision
- Recall
- F1 score
- Automated report
 
## Workflow
 
GIAB BAM
↓
BAM/VCF Ingestion
↓
QC Metrics
↓
Coverage Analysis
↓
GIAB Truth Set Comparison
↓
Performance Metrics
↓
Quarto Validation Report
 

