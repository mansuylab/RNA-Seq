<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [RNA-Seq data analysis](#rna-seq-data-analysis)
  - [01_fastqc](#01_fastqc)
  - [02_trimming](#02_trimming)
  - [03_quantification_salmon](#03_quantification_salmon)
  - [04_alignment_Rsubread](#04_alignment_rsubread)
  - [05_duplicates_analysis_dupRadar](#05_duplicates_analysis_dupradar)
  - [06_differential_gene_expression_limma_voom](#06_differential_gene_expression_limma_voom)
  - [07_differential_gene_expression_dream](#07_differential_gene_expression_dream)
  - [08_differential_transcript_usage_isoforSwitchAnalyzeR](#08_differential_transcript_usage_isoforswitchanalyzer)
  - [09_GSEA_analysis](#09_gsea_analysis)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

#<a href="https://zenhub.com"><img src="https://raw.githubusercontent.com/ZenHubIO/support/master/zenhub-badge.png"></a>
# RNA-Seq data analysis

This repository contain code for RNA-Seq data analysis.

## 01_fastqc
Quality check using `FASTQC`.

## 02_trimming
Quality control using `TrimGalore`.

## 03_quantification_salmon
Pseudoalignment with `salmon`.

## 04_alignment_Rsubread
Alignment using `Rsubread`.

## 05_duplicates_analysis_dupRadar
Assesment of PCR duplicates using `dupRadar`.

## 06_differential_gene_expression_limma_voom
Differential gene expression using `limma-voom` pipeline from `limma` package.

## 07_differential_gene_expression_dream
Differential gene expression using `dream` pipeline.

## 08_differential_transcript_usage_isoforSwitchAnalyzeR
Differential transcrip usage analysis using `DEXseq` and isoform switching analysis using `IsoformSwitchAnalyzeR`.

## 09_GSEA_analysis
Functional analysis (GSEA) using `fGSEA` package.
