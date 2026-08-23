## **RNA-seq Sample Information**

## **Student and Group Information**

**Student Name:** 
Dave Lister F. Romano

**Group Number:**
2

## **Group Paper**

**Title:** RNA-seq and qRT-PCR analyses reveal the physiological response to acute hypoxia and reoxygenation in *Epinephelus coioides*

**Citation:** Lai, X., et al. (2022). RNA-seq and qRT-PCR analyses reveal the physiological response to acute hypoxia and reoxygenation in *Epinephelus coioides*.

**Study Link:** https://doi.org/10.3389/fphys.2022.1049776

## **Assigned RNA-seq Sample**

**RNA-seq Accession:** SRR22065105

**Condition:** Acute Hypoxia (Sensitive)

**Biological Replicate:** 3

**Biological Meaning of the Sample:**
This sample represents muscle tissue from the orange-spotted grouper, which was used for RNA sequencing (RNA-Seq). The RNA extracted from the muscle was sequenced to study the genes that are actively expressed in the muscle, helping researchers understand muscle-related biological processes and gene functions in this fish.

## **Sequencing Information**

| **Metric**              | **Result**       |
|-------------------------|------------------|
| **Sequence Type**       | Paired-end       |
| **Number of Reads**     | 24504259         |
| **Read Length**         | 150 bp           |
| **GC Content**          | 51%              |

## **FastQC Summary**

| **FastQC Module** | **Forward (R1)** | **Reverse (R2)** |
|---|---|---|
| **Per base sequence quality** | PASS | PASS |
| **Per sequence quality scores** | PASS | PASS |
| **Per base sequence content** | FAIL | FAIL |
| **Per sequence GC content** | FAIL | FAIL |
| **Per base N content** | PASS | PASS |
| **Sequence length distribution** | PASS | PASS |
| **Sequence duplication levels** | FAIL | FAIL |
| **Overrepresented sequences** | WARN | WARN |
| **Adapter content** | PASS | PASS |

## **Screenshots**

<img width="1357" height="644" alt="780031552_904303545671501_1155595656096021007_n" src="https://github.com/user-attachments/assets/461e900e-ee2b-48ea-9968-2d1025658556" />

**Figure 1:** Galaxy History Showing the Imported RNA-seq dataset

<img width="1360" height="402" alt="783012024_1962015984497387_4654361396496061958_n" src="https://github.com/user-attachments/assets/6a505036-5312-472c-b024-8e91523f903c" />

**Figure 2:** FastQC Basic Statistics Result

<img width="1356" height="641" alt="780949253_1297045155731381_8263885445133361560_n" src="https://github.com/user-attachments/assets/359a5b0a-2447-4492-88ce-907545e0b5b9" />

**Figure 3:** FastQC Per Base Sequence Quality

<img width="1359" height="643" alt="779864684_1598669428631843_8276924676283072110_n" src="https://github.com/user-attachments/assets/4403bf12-eba6-4c84-85d0-6b1595a73991" />

**Figure 4:** FastQC Adapter Content

## **Interpretation Questions**

1. What biological question was the original RNA-seq study trying to answer?

The study investigated how the muscle genes of *Epinephelus coioides* respond to sudden low-oxygen conditions and reoxygenation. It also aimed to identify the molecular processes that help the fish tolerate hypoxia and recover when oxygen levels return to normal.

2. Why did the authors use RNA-seq instead of only examining the genome?
 
The researchers used RNA-seq because it shows which genes are actively being expressed and how their activity changes during hypoxia. While the genome contains the organism's complete genetic information, RNA-seq shows how those genes are functioning under specific conditions.

3. What is the difference between genomic DNA and the RNA molecules measured by RNA-seq?

Genomic DNA contains the complete and relatively permanent genetic information of an organism. In contrast, RNA molecules reflect which genes are currently being transcribed in a particular tissue or under a particular condition. Therefore, RNA-seq provides information about active gene expression that cannot be determined from DNA alone.

4. What is a biological replicate and why is it important?

A biological replicate is an independent sample collected from separate individuals belonging to the same experimental group. Biological replicates are important because they account for natural differences between individuals and help determine whether the observed gene expression changes are reliable rather than caused by random variation.

5. What is the difference between single-end and paired-end sequencing?

Single-end sequencing reads a DNA fragment from only one direction, whereas paired-end sequencing reads the same fragment from both ends. Paired-end sequencing provides additional information about the sequence and fragment structure, which can improve read alignment and the identification of different transcript forms.

6. What is a FASTQ file?

A FASTQ file stores sequencing reads together with quality scores for every nucleotide. These quality scores indicate how confident the sequencing instrument was in identifying each base. Unlike FASTA files, FASTQ files contain both the sequence and its quality information.

7. What information does FastQC provide?

FastQC is used to evaluate the quality of sequencing data. It examines factors such as base quality, GC content, sequence composition, duplication levels, adapter contamination, and overrepresented sequences. These results help researchers determine whether the data are suitable for further analysis.

8. What does a high per-base quality score indicate?

A high per-base quality score means that the sequencing instrument had a high level of confidence when identifying the nucleotide at that position. This suggests that the reads are more accurate and can improve the reliability of later steps such as sequence alignment and gene expression analysis.

9. Why can adapter contamination be a problem?

Adapter contamination occurs when artificial adapter sequences from the library preparation remain in the sequencing reads. If these sequences are not removed, they can affect read alignment, alter quality assessments, and potentially introduce errors or bias into downstream analyses such as gene expression studies.

10. Were all RNA-seq samples in your group similar in quality? Explain.

The samples were generally of acceptable quality, but there were some differences among them. Most samples performed well in important quality checks, such as sequence quality and adapter content. However, some samples received warnings or failed in areas such as GC content, sequence duplication, and sequence composition, showing that the quality was not exactly the same across all samples.

11. Did any sample show a possible quality problem? What was it?

Yes. Some samples displayed possible quality concerns. For instance, SRR22065105 failed the per-base sequence content, per-sequence GC content, and sequence duplication checks. SRR22065111 also failed the sequence content, and duplication checks and received warnings for GC content and overrepresented sequences. These results suggest that additional quality control may be necessary before continuing with the analysis.

12. What additional steps would be needed before the researchers could compare gene expression between control and treatment samples?

Before comparing gene expression between the control and treatment groups, the sequencing data need to undergo several processing steps. These include removing low-quality reads, aligning the reads to a reference genome, counting the reads associated with each gene, and performing statistical analysis to identify significant differences in gene expression. In this study, tools such as Fastp, TopHat2, and DESeq2 were used for these processes.

## **Conclusion**

In conclusion, RNA-seq is useful for understanding how *Epinephelus coioides* responds to low-oxygen conditions at the molecular level. It shows changes in gene expression that cannot be observed by examining genomic DNA alone. Although most of the sequencing samples had good quality, some showed issues that needed further quality control. Overall, proper processing and analysis of the RNA-seq data are important for making reliable comparisons between the control and treatment groups.
