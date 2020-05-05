# CRISPR/Cas9: Overview
CRISPR/Cas9 is a versatile gene editing system that can be used for a variety of different purposes. Based on your experimental goal, you can tailor the CRISPR/Cas9 system to suite your needs. The protocols described here use Cas9 nuclease

## The basic components of all CRISPR/Cas9 systems:
**1. guideRNA (gRNA)**
- The guideRNA is a short synthetic RNA composed of a scaffold sequence that facilitates Cas9-binding and a user-defined spacer sequence (~20nt) that targets the Cas9 protein to your specific genomic location of interest.

**2. Cas9 protein**
- Cas9 nuclease: Contains 2 catalytically active nuclease domains (RuvC cleaves the non-target strand, HNH cleaves the target strand), creating a blunt dsDNA break. This can be used for gene knockouts, indels, and knock-ins via HDR. 
- Cas9 nickase: Contains 1 catalytically active and 1 catalytically inactive domain, creating a ssDNA break. Instead of using Cas9 nuclease, you can use 2 Cas9 nickases in combination with 2 adjacent gRNAs to lower the probably of off-target editing in full gene knockouts, indels, and knock-ins via HDR
- Deactivated Cas9 (dCas9): Contains 2 catalytically inactive nuclease domains. dCas9 is used for CRISPRa and CRISPRi, instances in which you want to target the promotor of your gene of interest but do not wish to introduce permanent changes to the genome.

**3. Homology Directed Repair (HDR) template**
- Only needed for knock-ins!

## CRISPR/Cas9 experimental goals and experiment specific components:
-	**Full gene knockouts**: Design 2 gRNAs flanking region you wish to excise. Express both gRNAs in cells at the same time to create 2 double stranded breaks. No HDR template is necessary.
-	**Insertion of small indels (often to introduce frameshift mutations)**: Design 1 gRNA just after the start codon to introduce a frameshift mutation at the beginning of your protein of interest. No HDR template is necessary.
-	**Knock-in of foreign genetic material (epitope tags) via homology directed repair (HDR)**: Design 1 gRNA near the site where you wish you insert foreign DNA. Design 1 HDR template that contains the insert flanked by homology arms. 
-	**Gene activation (CRISPRa) to increase gene expression**: Design 1 gRNA near the promotor or TSS of the gene you wish to activate. Use a specialized dCas9 fused to a transcriptional activation domain to activate expression.
-	**Gene interference (CRISPRi) to repress gene expression**: Design 1 gRNA near the promotor or TSS of the gene you wish you repress. Use a specialized dCas9 fused to a transcriptional repressor domain to repress transcription.
