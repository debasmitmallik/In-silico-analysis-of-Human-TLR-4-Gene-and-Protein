#   Human TLR4 In-Silico Analysis

![TLR4 Project Banner](images/TLR4_project_banner.png)
A comprehensive computational study of the human TLR4 gene and protein, integrating sequence and structural characterization with evolutionary conservation, protein–protein interactions, functional and pathway enrichment, genetic variation, disease associations, and cancer prognostic analysis.
##  Project Overview

Toll-like receptor 4 (**TLR4**) is a pattern-recognition receptor that plays a central role in the innate immune response, particularly in the recognition of bacterial lipopolysaccharide (LPS). Activation of TLR4 initiates downstream signaling cascades involving adaptor proteins such as MYD88 and TICAM1 (TRIF), ultimately regulating inflammatory and immune-response genes.

This project presents an integrated **in-silico analysis of the human TLR4 gene and protein**, beginning with gene annotation and sequence retrieval and progressing through structural characterization, evolutionary conservation, protein–protein interaction analysis, functional and pathway enrichment, genomic variation, disease association, and pan-cancer survival analysis.

---
##  Objectives

- Annotate and characterize the human TLR4 gene.
- Retrieve and analyze TLR4 nucleotide and protein sequences.
- Identify and validate the coding region using ORF analysis.
- Characterize the physicochemical properties of TLR4 protein.
- Investigate evolutionary conservation using multiple sequence alignment.
- Identify conserved domains and functional regions.
- Analyze the secondary and three-dimensional structure of TLR4.
- Construct a TLR4 protein-protein interaction network.
- Perform Gene Ontology enrichment analysis.
- Identify enriched biological pathways.
- Investigate clinically relevant TLR4 genetic variants.
- Explore TLR4 expression and prognostic significance across cancers.

---
##  Workflow

1. Gene Annotation
2. Sequence Retrieval
3. ORF Analysis
4. Physicochemical Characterization
5. Multiple Sequence Alignment
6. Conserved Domain Architecture Profiling
7. Secondary Structure Assignment
8. Protein-Protein Interaction Network Construction
9. Gene Ontology Functional Enrichment
10. Pathway Enrichment & Visualization
11. Genomic Variation & Disease Association Mapping
12. Pan-Cancer Survival & Biomarker Profiling

---
##  Tools & Databases

| Analysis | Tool / Database |
|---|---|
| Gene Annotation | NCBI Gene, Ensembl, UniProtKB |
| Sequence Retrieval | NCBI Nucleotide, NCBI Protein, UniProtKB |
| ORF Analysis | NCBI ORFfinder |
| Physicochemical Analysis | ExPASy ProtParam |
| Multiple Sequence Alignment | Clustal Omega |
| Domain Analysis | NCBI CDD, Pfam |
| Structural Analysis | RCSB PDB |
| Protein Interaction | STRING |
| GO Enrichment | STRING, g:Profiler |
| Pathway Analysis | Reactome, KEGG, ShinyGO |
| Variant Analysis | ClinVar, OMIM, NCBI Variation Viewer |
| Cancer Analysis | GEPIA3 |

---

#  Analysis Results

## 1. Gene Annotation

Gene annotation was performed using NCBI Gene, Ensembl, and UniProtKB to determine the identity, chromosomal location, transcript information, protein information, and database cross-references of the human TLR4 gene.

### Target Gene Information

| Parameter | Information |
|---|---|
| Gene Symbol | TLR4 |
| Full Name | Toll-like receptor 4 |
| Organism | *Homo sapiens* |
| Chromosome | 9 |
| Chromosomal Locus | 9q33.1 |
| NCBI Gene ID | 7099 |
| RefSeq Transcript | NM_138554.5 |
| RefSeq Protein | NP_612564.1 |
| UniProt ID | O00206 |
| Protein Length | 839 amino acids |

---
## 2. Sequence Retrieval

The human TLR4 transcript and protein sequences were retrieved from NCBI and UniProtKB in FASTA format.

The retrieved sequences were subsequently used for ORF analysis, physicochemical characterization, evolutionary analysis, and structural investigation.
### Sequence Files

- [TLR4 mRNA sequence](data/TLR4_mRNA.fasta)
- [TLR4 protein sequence](data/TLR4_protein.fasta)
## 3. Open Reading Frame (ORF) Analysis

The TLR4 mRNA sequence was analyzed using NCBI ORFfinder across all six possible reading frames to identify and verify the protein-coding region.

The analysis identified the coding region corresponding to the full-length TLR4 precursor protein.

### ORF Analysis Result

- ORF: 4
- Reading Frame: +1
- Coding Sequence: approximately 2,520 bp
- Protein Length: 839 amino acids

![TLR4 ORF Analysis](images/TLR4_ORF_analysis.png)

---
## 4. Physicochemical Characterization

The TLR4 protein sequence was analyzed using ExPASy ProtParam to determine its fundamental physicochemical properties.

The following parameters were investigated:

- Molecular weight- 95,680.13 Da (95.7 kDa)
- Theoretical isoelectric point (pI)- 5.88 (Slightly acidic)
- Highest Amino Acid: Leucine (L) at 15.5% (130 residues)
- Instability index- 43.05
- Aliphatic index- 101.86

- GRAVY hydropathicity score- 0.033

-Total number of negatively charged residues (Asp + Glu): 83

-Total number of positively charged residues (Arg + Lys): 68

### Total amino acid composition

-[TLR4 amino acid composition](data/TLR4_amino_acid_composition.csv)


