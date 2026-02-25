# tss-analysis-pipeline

## Overview
転写開始点（TSS）の選択が、その後に産生される転写産物およびタンパク質配列の構造・機能多様化に与える影響を、ヒトゲノム全体を対象として網羅的に解析するための統合解析パイプライン。

## Data
- refTSS database  
  - refTSS_v4.1_human_hg38_annotation.txt  
  - refTSS_v4.1_human_coordinate.hg38.bed.txt
- Ensembl  
  - gencode.v48.pc_translations.fa
- RefSeq annotation  
  - GRCh38_latest_genomic.gff  
  - GRCh38_latest_protein.faa
- GenBank  
  - Protein and nucleotide sequences were retrieved individually via NCBI (ID-based query), not bulk download

## Directory structure
src/        : analysis scripts (Python / R)  
scripts/    : execution scripts  
notebooks/  : exploratory analysis  
data/       : input data (not tracked by git)  
results/    : outputs (not tracked by git)

