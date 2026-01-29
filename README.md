# fem-rDNA_Masters
Bioinformatic analysis of a CRISPR–modified zebrafish line, linking 45S-M promoter modification classes to pedigree transmission, qPCR copy number, and Telo-Seq long-read evidence.

## Amplicon sequencing (start here)
Run **Modification Class** after the variant-caller pipeline from **Moser et al. 2025** to assign modification classes and summarise reference conformity.
This generates the inputs for: **Fig 4.5–4.7** (Sire 11/19/15+29 transmission) and **Fig 4.8** (HI by F0 sire).
At the end, reformat/export tables for compatibility with **Modification Class Pedigrees** and **qPCR Analysis**.
If heterozygosity analysis is required, add the **Heterozygosity Index** code at the end of **Modification Class Pedigrees**.

## qPCR
Use **qPCR Analysis** to join qPCR copy-number estimates to the same formatted amplicon outputs.
Generates: **Fig 4.10** (copy number vs reference conformity), **Fig 4.11** (copy number by sex), **Fig 4.12** (copy number by modification status).

## Telo-Seq
Use **Telo-Seq** scripts to annotate long reads spanning the subtelomeric 45S-M region and detect class-VI deletion evidence.
Generates: **Fig 4.14–4.15** (annotated long reads), **Fig 4.16-4.17** (class VI deletion).
