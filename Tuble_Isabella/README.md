# Group 2 Hypoxia

## Isabella Tuble ##

## RNA-seq and qRT-PCR analyses reveal the physiological response to acute hypoxia and reoxygenation in *Epinephelus coioides* ##

Lai X, Zhong Z, Lin B, Wu Y, Ma Y, Zhang C, Yang Y, Zhang M, Qin W, Fu X and Shu H (2022) RNA-seq and qRT-PCR analyses reveal the physiological response to acute hypoxia and reoxygenation in *Epinephelus coioides*. Front. Physiol. 13:1049776. doi: 10.3389/fphys.2022.1049776

# RNA-seq accession number: PRJNA895010

# Treatment Condition

# Acute Hypoxia (Sensitive)

The acute hypoxia-sensitive sample (EMW group) represents muscle tissue from Epinephelus coioides that is vulnerable to low oxygen stress. Biologically, it reflects a phenotype with reduced tolerance, showing strong transcriptomic changes under DO ≈ 0.6 mg/L, including activation of the HIF-1 pathway, glycolysis, apoptosis, and immune regulation. This highlights a stress-sensitive response where energy metabolism and survival mechanisms are triggered but less sustained compared to tolerant fish.

## The data are paired-end ##

## Number of reads: FastQC report shows 17,342,519 reads. ##

## Read length: Fixed at 150 bp per read. ##

## GC content: Average 51% GC. ##

# FastQC Summary 

Total reads: 17,342,519

Read length: 150 bp

GC content: 51%

No sequences flagged as poor quality

Per-base quality:

Excellent overall (median Q ~37 across all bases)

Slight drop at the last bases but still high

Per-sequence quality:

Majority of reads scored Q ≥ 30

Distribution strongly skewed toward high-quality reads

Per-base sequence content:

Fail — imbalance in base composition at early cycles (common in Illumina runs)

GC distribution:

Fail — deviates from normal distribution, indicating bias

Sequence duplication:

Fail — high duplication levels (~15% deduplicated), suggesting reduced library complexity

Overrepresented sequences:

Warning — several sequences flagged, but no database hits (likely technical artifacts)

Adapter content:

Pass — minimal adapter contamination detected

# 3 Screenshots 

## Per base sequence quality plot ##

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/caa8845f-89c3-4a17-9965-a93ab3844286" />

## Per sequence GC content plot ##

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/6ee10a17-34aa-4c55-a066-b59373bbbf77" />

## Sequence duplication levels plot ##

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/85a1378b-a9d1-4d25-a757-9b1db07f1f77" />

# Interpretation Questions 

## 1. What biological question was the original RNA-seq study trying to answer? ##

The study aimed to determine how the muscle transcriptome of Epinephelus coioides responds to acute hypoxia and to identify molecular pathways involved in hypoxia tolerance and reoxygenation. 

## 2. Why did the authors use RNA-seq instead of only examining the genome? ##

The authors used RNA-seq instead of relying solely on the genome because RNA-seq reveals which genes are actively expressed and how their expression levels change under hypoxia. The genome provides the blueprint, but RNA-seq captures the dynamic activity of genes in real time, making it essential for studying stress responses.

## 3. What is the difference between genomic DNA and the RNA molecules measuredbyRNA-seq? ##

Genomic DNA represents the permanent genetic code of the organism, while RNA molecules measured by RNA-seq reflect the genes being transcribed in a specific tissue under certain conditions. RNA-seq therefore provides a snapshot of functional gene activity, whereas DNA alone cannot show which genes are turned on or off.

## 4. What is a biological replicate and why is it important? ##

A biological replicate is an independent sample taken from different individuals within the same experimental group. Replicates are crucial because they account for natural biological variation and ensure that observed differences in gene expression are consistent and reproducible rather than random noise.

## 5. What is the difference between single-end and paired-end sequencing? ##

Single-end sequencing reads fragments from one end only, while paired-end sequencing reads both ends of the same fragment. Paired-end sequencing provides more information about fragment length and structure, improving alignment accuracy and detection of transcript isoforms, which is why it was chosen in this study.

## 6. What is a FASTQ file? ##

A FASTQ file contains raw sequencing reads along with a quality score for each base, combining sequence information with confidence levels. This makes it more informative than a FASTA file, which only contains sequence data without quality metrics.

## 7. What information does FastQC provide? ##

FastQC provides a comprehensive quality assessment of sequencing data, including per-base quality scores, GC content, sequence composition, duplication levels, adapter contamination, and overrepresented sequences. These metrics help researchers identify potential issues before downstream analysis.

## 8. What does a high per-base quality score indicate? ##

A high per-base quality score indicates that the sequencing machine was confident in calling each nucleotide, meaning the reads are reliable. This reduces the likelihood of errors in alignment and gene expression quantification, strengthening the accuracy of the dataset.

## 9. Why can adapter contamination be a problem? ##

Adapter contamination is problematic because adapters are artificial sequences added during library preparation. If not removed, they can interfere with read alignment, distort quality metrics, and introduce biases in downstream analyses such as differential expression.

## 10. Were all RNA-seq samples in your group similar in quality? Explain. ##

The RNA-seq samples in the group were generally of good quality, but not identical. While most passed general sequence quality and adapter checks, some showed warnings or failures in categories like GC content, sequence duplication, and overrepresented sequences, indicating variability across replicates.

## 11. Did any sample show a possible quality problem? What was it? ##

Yes, some samples showed quality problems. For example, SRR22065105 failed in per-base sequence content, per-sequence GC content, and duplication levels, while SRR22065111 failed in sequence content and duplication with warnings for GC content and overrepresented sequences. These issues highlight the need for careful filtering.

## 12. What additional steps would be needed before the researchers could compare gene expression between control and treatment samples? ##

Before comparing gene expression between control and treatment groups, researchers must perform preprocessing steps such as quality filtering, read alignment to the reference genome, gene counting, and statistical analysis of differential expression. In this study, Fastp, TopHat2, and DESeq2 were used to ensure reliable comparisons.

# Short Conclusion 

In conclusion, the RNA-seq study revealed how Epinephelus coioides muscle responds to acute hypoxia and reoxygenation, highlighting the central role of the HIF-1 signaling pathway in regulating energy metabolism, apoptosis, and immune responses. FastQC analysis confirmed that the sequencing data were generally high quality, with strong per-base scores and balanced GC content, though some samples showed duplication and GC bias. These findings emphasize the importance of RNA-seq in uncovering dynamic gene expression changes beyond the static genome, and they provide a foundation for comparing control vs treatment samples in future hypoxia tolerance studies. Overall, the results contribute valuable insights into stress adaptation mechanisms in aquaculture species.
