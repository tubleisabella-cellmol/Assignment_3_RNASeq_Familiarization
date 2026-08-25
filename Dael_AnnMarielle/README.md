# RNA-seq Sample Information

# Student and Group Information

**Student Name:**
Ann Marielle U. Dael

**Group Number:**
2

# Group Paper

**Title:**
RNA-seq and qRT-PCR analyses reveal the physiological response to acute hypoxia and reoxygenation in *Epinephelus coioides*

**Citation**
Lai, X., et al. (2022). RNA-seq and qRT-PCR analyses reveal the physiological response to acute hypoxia and reoxygenation in *Epinephelus coioides.*

**Study Link**
https://doi.org/10.3389/fphys.2022.1049776

# Assigned RNA-seq Sample

**RNA-seq Accession:**
SRR22065108

**Condition:**
Acute Hypoxia (Tolerant)

**Biological Replicate:**
3

**Biological Meaning of The Sample:**
This sample consists of muscle tissue from the orange-spotted grouper, which was analyzed using RNA sequencing (RNA-seq). RNA was extracted from the muscle tissue and sequenced to examine the genes being actively expressed, providing information about muscle-related biological processes and gene functions in the fish.

# Sequencing Information

### RNA-Seq Dataset Characteristics

**Table 1.** *Sequencing Information.*
| Metric | Result |
|---|---|
| Sequence Type | Paired-end |
| Number of Reads | 26787341 |
| Read Length | 150 bp |
| GC Content | 51% |

## FastQC Summary

**Table 2.** *FastQC Summary.*
| FastQC Module | Forward (R1) | Reverse (R2) |
|---|---|---|
| Per base sequence quality | PASS | PASS |
| Per sequence quality scores | PASS | PASS |
| Per base sequence content | FAIL | FAIL |
| Per sequence GC content | FAIL | FAIL |
| Per base N content | PASS | PASS |
| Sequence length distribution | PASS | PASS |
| Sequence duplication levels | FAIL | FAIL |
| Overrepresented sequences | WARN | WARN |
| Adapter content | WARN | WARN |

# Screenshots

<img width="1895" height="907" alt="image" src="https://github.com/user-attachments/assets/e7b003c7-7d59-4c66-9337-eaa1703de6bf" />

**Figure 1.** *Galaxy History Showing the Imported RNA-seq dataset*

<img width="1905" height="502" alt="image" src="https://github.com/user-attachments/assets/2c5945b3-3634-4425-b453-649791c7ec77" />

**Figure 2.** *FastQC Basic Statistics Result*

<img width="1902" height="896" alt="image" src="https://github.com/user-attachments/assets/fbcd9de7-d741-4374-a8e6-1d7815506908" />

**Figure 3.** *FastQC Per Base Sequence Quality*

<img width="1913" height="893" alt="image" src="https://github.com/user-attachments/assets/3cb13dcd-d8b6-40e9-bc7d-65b48d055053" />

**Figure 4.** *FastQC Adapter Content* 

# Interpretation Questions

1. What biological question was the original RNA-seq study trying to answer?

The study examined how *Epinephelus coioides* responds to acute hypoxia and reoxygenation, and compared hypoxia-tolerant vs. hypoxia-sensitive fish.

2. Why did the authors use RNA-seq instead of only examining the genome?

RNA-seq was used to identify which genes are actively expressed under hypoxia, since the genome only shows DNA content, not gene activity.

3. What is the difference between genomic DNA and the RNA molecules measured by RNA-seq?

Genomic DNA is the stable full genetic code, while RNA-seq measures RNA molecules that reflect active transcription in specific tissues or conditions.

4. What is a biological replicate and why is it important?

A biological replicate is an independent sample from the same condition, such as another fish. Replicates confirm that results are consistent and not due to individual variation.

5. What is the difference between single-end and paired-end sequencing?

Single-end sequencing reads fragments from one end; paired-end reads both ends, giving more information for alignment and transcript analysis.

6. What is a FASTQ file?

A FASTQ file stores sequencing reads with nucleotide sequences and quality scores for each base.

7. What information does FastQC provide?

FastQC reports sequencing quality, GC content, read length, adapter contamination, and overrepresented sequences, highlighting potential issues in raw data.

8. What does a high per-base quality score indicate?

A high per-base quality score means the nucleotide call is reliable and less likely to be an error.

9. Why can adapter contamination be a problem?

Adapter contamination introduces non-biological sequences into reads, disrupting alignment and downstream analysis, so adapters must be trimmed.

10. Were all RNA-seq samples in your group similar in quality? Explain.

Overall, the samples were similar in quality, though some FastQC modules flagged issues like per-base content, GC content, or duplication.

11. Did any sample show a possible quality problem? What was it?

Yes, some samples showed problems such as abnormal per-base content, GC distribution, or duplication levels.

12. What additional steps would be needed before the researchers could compare gene expression between control and treatment samples?

Before comparing gene expression, reads must undergo quality control, trimming, alignment or quantification, then normalization and statistical analysis for differential expression.

# Conclusion

This exercise enhanced my understanding of how RNA-seq can be applied to investigate the response of *Epinephelus coioides* under hypoxic stress. By analyzing the FASTQ files alongside the FastQC reports, I gained practical insight into assessing sequencing quality, read distribution, GC content, and potential sources of error. Although certain FastQC modules flagged warnings or failures in specific reads, the dataset overall proved suitable for downstream analysis. Engaging in this activity allowed me to appreciate the essential preliminary steps required before advancing to gene-expression profiling.
