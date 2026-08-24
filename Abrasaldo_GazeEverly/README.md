## RNA-Seq Sample Information

## Student Information

Student Name: Gaze Everly M. Abrasaldo  
Group Number: Group 2

## Selected Paper

**Paper Title:** RNA-seq and qRT-PCR analyses reveal the physiological response to acute hypoxia and reoxygenation in *Epinephelus coioides*

**Full Citation:** Lai, X., et al. (2022). RNA-seq and qRT-PCR analyses reveal the physiological response to acute hypoxia and reoxygenation in *Epinephelus coioides*.


**Study Link:** [https://doi.org/10.3389/fphys.2022.1049776]

## Assigned RNA-Seq Dataset

RNA-seq Accession: SRR22065109

Condition: Acute Hypoxia (Tolerant)

Biological Replicate: 2

## 4. Biological Meaning of the Sample

This sample represents muscle tissue from an orange-spotted grouper exposed to acute hypoxia and classified as hypoxia-tolerant. The RNA-seq data are used to examine gene-expression patterns associated with the response to hypoxia.

## Sequencing Information

| Metric          | Result       |
|-----------------|--------------|
| Sequencing Type | Paired-end   |
| Number of Reads | 22492202     |
| Read Length     | 150          |
| GC Content (%)  | 51           |

## FastQC Summary

| FastQC Module | Forward (R1) | Reverse (R2) |
|---|---|---|
| Per base sequence quality | PASS | PASS |
| Per sequence quality scores | PASS | PASS |
| Per base sequence content | FAIL | FAIL |
| Per sequence GC content | WARN | FAIL |
| Per base N content | PASS | PASS |
| Sequence length distribution | PASS | PASS |
| Sequence duplication levels | FAIL | FAIL |
| Overrepresented sequences | WARN | WARN |
| Adapter content | PASS | PASS |



## Screenshots

<img width="1168" height="2083" alt="IMG_1979" src="https://github.com/user-attachments/assets/342ba629-70b0-428a-b505-547727639ede" />

Figure 1: Galaxy History Showing the Imported RNA-seq dataset

<img width="1168" height="2087" alt="IMG_1981" src="https://github.com/user-attachments/assets/54fc129f-2e52-4948-822b-b511fe2a14a9" />

Figure 2: FastQC Basic Statistics Result

<img width="1169" height="2251" alt="IMG_1982" src="https://github.com/user-attachments/assets/d41ee137-f202-4771-94db-37055a4fdfdd" />

Figure 3. FastQC Per Base Sequence Quality

<img width="1168" height="2293" alt="IMG_1983" src="https://github.com/user-attachments/assets/866fa876-a484-45e4-a942-216fe6ec7dad" />

Figure 4. FastQC Adapter Content
   
## Interpretation Questions

1. What biological question was the original RNA-seq study trying to answer?

The study aimed to identify gene-expression changes in orange-spotted grouper (*Epinephelus coioides*) associated with acute hypoxia and to understand the molecular responses related to hypoxia tolerance and sensitivity.

2. Why did the authors use RNA-seq instead of only examining the genome?

RNA-seq was used because it measures RNA molecules and shows which genes are actively expressed under different conditions. Examining only the genome would show the DNA sequence but not the changes in gene expression.

3. What is the difference between genomic DNA and the RNA molecules measured by RNA-seq?

Genomic DNA contains the organism's genetic information, while RNA molecules represent genes that are being expressed at a particular time or under a particular condition.

4. What is a biological replicate and why is it important?

A biological replicate is a separate biological sample from the same experimental condition. It is important because it helps measure natural biological variation and makes the results more reliable.

5. What is the difference between single-end and paired-end sequencing?

Single-end sequencing reads each DNA fragment from one end, while paired-end sequencing reads each fragment from both ends. Paired-end sequencing provides more information about the sequence and its position.

6. What is a FASTQ file?

A FASTQ file is a file format that stores sequencing reads together with their quality scores.

7. What information does FastQC provide?

FastQC provides information about the quality of sequencing data, including per-base sequence quality, GC content, sequence duplication, overrepresented sequences, and adapter contamination.

8. What does a high per-base quality score indicate?

A high per-base quality score indicates that the sequencing bases are likely to be called correctly and that the reads have good sequence quality.

9. Why can adapter contamination be a problem?

Adapter contamination can affect read quality and interfere with downstream analysis. Adapter sequences may also be incorrectly interpreted as biological sequences.

10. Were all RNA-seq samples in your group similar in quality? Explain.

No. The RNA-seq samples were not completely similar in quality. Some samples showed good overall quality, while others had warnings or failures in areas such as GC content, sequence composition, and sequence duplication.

11. Did any sample show a possible quality problem? What was it?

Yes. Some samples showed possible quality problems, including failures in per-base sequence content, GC content, and sequence duplication levels. Overrepresented sequences were also observed as a warning in some samples.

12. What additional steps would be needed before the researchers could compare gene expression between control and treatment samples?

The researchers would need to perform quality control and trimming, remove adapters and low-quality reads, align or quantify the reads against a reference, and normalize the data before performing differential gene-expression analysis.

## Conclusion

The RNA-seq dataset provided information about gene expression in orange-spotted grouper under acute hypoxia. The assigned sample contained 22,492,202 reads with a read length of 150 bp and a GC content of 51%. FastQC showed good per-base sequence quality, although some quality issues were observed in sequence composition, GC content, duplication, and overrepresented sequences. Overall, the analysis helped demonstrate how RNA-seq data are evaluated before comparing gene expression between different experimental conditions.
