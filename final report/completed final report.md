# Cell & Molecular Biology
Lab Activity: Characterization of a Plastid Genome

Cell and Molecular Biology
Name: Francis Kyle A. Oficiar
Date Completed: October 4, 2026
Chosen Genus: Lilium

# Purpose
In this activity, a complete plastid genome was selected from a public database, downloaded, uploaded to Galaxy, and characterized using sequence statistics and published plastome information. 
The selected organism was Lilium lancifolium, and the analysis focused on genome size, GC content, genome organization, gene content, and notable plastid features.

# Choosing and Recording a Plant Genus
| **ITEM**  | **ANSWER**                                                                                     |
| --------- | ---------------------------------------------------------------------------------------------- |
| Genus     | *Lilium*                                                                                       |
| Species   | *Lilium lancifolium*                                                                           |
| Accession | OR400160.1                                                                                     |
| URL       | [https://www.ncbi.nlm.nih.gov/nuccore/OR400160](https://www.ncbi.nlm.nih.gov/nuccore/OR400160) |

<img width="781" height="636" alt="image" src="https://github.com/user-attachments/assets/34ab6822-5a24-4fb4-8bc3-572ededeef38" />
_Figure 1._ Retrieval of _Lilium lancifolium_ in NCBI (OR400160.1).

# Data Source and Genome Selection
| **ITEM**        | **ANSWER**                                                     |
| --------------- | -------------------------------------------------------------- |
| Accession       | OR400160.1                                                     |
| Organism        | *Lilium lancifolium*                                           |
| Family          | Liliaceae                                                      |
| Genome length   | 152,575 bp                                                     |
| GC content      | 37.03%                                                         |
| Topology        | Circular plastome                                              |
| Database source | NCBI Nucleotide / GenBank                                      |
| Date retrieved  | October 4, 2026                                                |
| Source          | [NCBI OR400160](https://www.ncbi.nlm.nih.gov/nuccore/OR400160) |

<img width="672" height="400" alt="image" src="https://github.com/user-attachments/assets/948a218a-357b-498d-9db4-f5d621c0111d" />
Figure 2. Complete plastid genome of Lilium lancifolium (OR400160.1) in NCBI.

# Galaxy Workflow - Use Your Own Account
| **STEP**                                  | **ANSWER**                             |
| ----------------------------------------- | -------------------------------------- |
| Sign in to own account                    |https://usegalaxy.org/u/franciskyle/h/plastid-lilium-oficiar|          
| History name                              | plastid-lilium-oficiar                 |
| Upload FASTA                              | Uploaded OR400160.1 FASTA              |
| FASTA filename                            | `Lilium_lancifolium.fasta`             |
| Tool used                                 | FASTA Statistics                       |
| Genome length                             | 152,575 bp                             |
| Number of sequence records                | 1                                      |
| Number of scaffolds                       | 1                                      |
| Number of contigs                         | 1                                      |
| GC content                                | 37.03%                                 |
| Ambiguous bases (N)                       | 0                                      |
| Gaps                                      | 0                                      |
| Complete plastome in one sequence record? | Yes                                    |

<img width="672" height="318" alt="image" src="https://github.com/user-attachments/assets/2e8a477a-3de1-480d-b2fc-39b1ae1b7a63" />
Figure 3. Galaxy workflow analyzing Lilium lancifolium using FASTA Statistics

# Plastid Genome Terms to Understand
| **Term**                  | **Meaning**                                                                                        |
| ------------------------- | -------------------------------------------------------------------------------------------------- |
| Plastid genome / plastome | The DNA genome found in a plastid; in green plants this commonly refers to the chloroplast genome. |
| LSC                       | Large Single-Copy region.                                                                          |
| SSC                       | Small Single-Copy region.                                                                          |
| IR                        | Inverted Repeat region; plastomes commonly contain two IR copies.                                  |
| CDS                       | Protein-coding sequence.                                                                           |
| tRNA gene                 | Gene encoding transfer RNA used during translation.                                                |
| rRNA gene                 | Gene encoding ribosomal RNA that forms part of plastid ribosomes.                                  |
| Intron                    | A non-coding region removed from an RNA transcript during RNA processing.                          |
| Pseudogene                | A gene-like sequence that has lost or may have lost normal function.                               |
| GC content                | Percentage of guanine and cytosine bases in the sequence.                                          |
| Accession                 | Database identifier assigned to a sequence record.                                                 |
| Annotation                | Information describing genes and other biological features in a genome sequence.                   |

<img width="672" height="547" alt="image" src="https://github.com/user-attachments/assets/6e73ac8a-4be9-4e81-adaa-8c45368d9e7a" />
Figure 4. Plastid genome characterization

# Required Plastid Genome Characterization
| **Item**               | **Answer**                                                                                                                          |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Genus and species      | *Lilium lancifolium*                                                                                                                |
| Family                 | Liliaceae                                                                                                                           |
| NCBI accession         | OR400160.1                                                                                                                          |
| Complete genome size   | 152,575 bp                                                                                                                          |
| GC content             | 37.03%                                                                                                                              |
| Topology               | Circular                                                                                                                            |
| Genome organization    | Typical LSC–IR–SSC–IR quadripartite organization                                                                                    |
| LSC                    | Approximately 82 kb in published *L. lancifolium* plastomes                                                                         |
| SSC                    | Approximately 17.5–17.6 kb in published *L. lancifolium* plastomes                                                                  |
| IR                     | Approximately 26.5 kb each in published *L. lancifolium* plastomes                                                                  |
| Total annotated genes  | About 112 unique genes in well-characterized *L. lancifolium* plastomes; higher totals result when duplicated IR copies are counted |
| Protein-coding genes   | About 79 unique protein-coding genes in published *L. lancifolium* plastomes                                                        |
| tRNA genes             | About 30 unique tRNA genes                                                                                                          |
| rRNA genes             | 4 unique rRNA genes, usually duplicated in the IRs                                                                                  |
| Introns                | Multiple plastid genes contain introns, including *atpF, ndhA, ndhB, rpoC1, rpl16, rps12, rps16, petB,* and *petD*                  |
| Pseudogenes            | *infA* and *cemA* pseudogenization have been reported in some *L. lancifolium* plastomes                                            |
| Gene duplications      | Genes located within the two IR regions occur in duplicated copies                                                                  |
| Other notable features | *rps12* is trans-spliced; extensive RNA editing has been reported; plastome structure and gene order are highly conserved           |

| **Gene group**           | **Genes reported in *Lilium lancifolium* plastomes**                                     |
| ------------------------ | ---------------------------------------------------------------------------------------- |
| Photosystem I (psa)      | psaA, psaB, psaC, psaI, psaJ                                                             |
| Photosystem II (psb)     | psbA, psbB, psbC, psbD, psbE, psbF, psbH, psbI, psbJ, psbK, psbL, psbM, psbN, psbT, psbZ |
| ATP synthase (atp)       | atpA, atpB, atpE, atpF, atpH, atpI                                                       |
| Cytochrome b6f (pet)     | petA, petB, petD, petG, petL, petN                                                       |
| Rubisco large subunit    | rbcL                                                                                     |
| RNA polymerase (rpo)     | rpoA, rpoB, rpoC1, rpoC2                                                                 |
| Ribosomal proteins (rpl) | rpl2, rpl14, rpl16, rpl20, rpl22, rpl23, rpl32, rpl33, rpl36                             |
| Ribosomal proteins (rps) | rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19            |
| rRNA (rrn)               | rrn16, rrn23, rrn4.5, rrn5                                                               |
| tRNA (trn)               | Multiple *trn* genes distributed throughout the plastome                                 |
| Other conserved genes    | matK, clpP, accD, cemA, ycf1, ycf2, ycf3, ycf4                                           |

# Questions for the Student Report
1. _Lilium lancifolium_, commonly called tiger lily, belongs to the family Liliaceae. The selected genome is NCBI accession OR400160.1, obtained from the NCBI Nucleotide/GenBank database. The complete FASTA sequence analyzed in Galaxy is 152,575 bp long and has a GC content of 37.03%.
2. The sequence is consistent with a complete plastid genome because it consists of a single sequence record of 152,575 bp with no gaps and no ambiguous N bases. This size is typical for Lilium plastomes, which generally fall near 152 kb. It is also much larger than single plastid barcode markers such as rbcL or matK. Published Lilium plastomes contain the typical plastid gene complement, including photosystem genes, ATP synthase genes, cytochrome b6f genes, rbcL, ribosomal genes, rRNAs, and tRNAs, and they possess the characteristic quadripartite chloroplast structure.
3. The _Lilium lancifolium_ plastome follows the common quadripartite arrangement consisting of one large single-copy region, one small single-copy region, and two inverted repeats. Published L. lancifolium plastomes are approximately 82 kb in the LSC, 17.5–17.6 kb in the SSC, and 26.5 kb in each IR. For example, accession KY748297 was reported as 152,574 bp with an LSC of 82,007 bp, SSC of 17,583 bp, and IRs of 26,492 bp each.
4. The Lilium lancifolium plastome follows the common quadripartite arrangement consisting of one large single-copy region, one small single-copy region, and two inverted repeats. Published _L. lancifolium_ plastomes are approximately 82 kb in the LSC, 17.5–17.6 kb in the SSC, and 26.5 kb in each IR. For example, accession KY748297 was reported as 152,574 bp with an LSC of 82,007 bp, SSC of 17,583 bp, and IRs of 26,492 bp each.

# Eight protein-coding genes
| **Gene** | **Functional group** | **Function**                                                                                     |
| -------- | -------------------- | ------------------------------------------------------------------------------------------------ |
| psaA     | Photosystem I        | Encodes a core Photosystem I reaction-center protein involved in light-driven electron transfer. |
| psbA     | Photosystem II       | Encodes the D1 reaction-center protein of Photosystem II.                                        |
| petB     | Cytochrome b6f       | Encodes cytochrome b6, which transfers electrons between the photosystems.                       |
| atpA     | ATP synthase         | Encodes an ATP synthase subunit involved in ATP production.                                      |
| rbcL     | Carbon fixation      | Encodes the large subunit of Rubisco, the enzyme responsible for carbon fixation.                |
| rpoB     | RNA polymerase       | Encodes a subunit of plastid-encoded RNA polymerase.                                             |
| rpl2     | Ribosomal protein    | Encodes a large ribosomal subunit protein required for plastid translation.                      |
| clpP     | Protease             | Encodes part of the Clp protease complex involved in protein degradation.                        |

5. The major plastid rRNA genes are rrn16, rrn23, rrn4.5, and rrn5, which are commonly located in the inverted repeats and therefore occur in two copies. Examples of tRNA genes include trnK-UUU, trnL-UAA, trnI-GAU, trnA-UGC, and trnV-UAC. Published L. lancifolium plastomes contain several intron-bearing genes, including atpF, ndhA, ndhB, rpoC1, rpl16, rps12, rps16, petB, and petD. The rps12 gene is particularly notable because it is trans-spliced. RNA-editing events have also been reported in _L. lancifolium_, especially in ndh genes.
6. Several unusual or notable features have been reported in _Lilium lancifolium_. The infA gene was predicted as a pseudogene in one accession because of internal stop codons, and cemA pseudogenization has also been reported in another L. lancifolium plastome. Genes located within the inverted repeats are naturally duplicated. Comparative analyses show that Lilium plastomes have very conserved gene order and generally lack major structural rearrangements. One transcriptome study also identified 90 RNA-editing sites, most of which were C-to-U changes, with ndh genes containing many of the editing sites.
7. The GC content of the analyzed plastome is 37.03%. Two additional notable observations from Galaxy are that the sequence consists of only one contig/scaffold and that it contains zero ambiguous bases and zero gaps, supporting a continuous assembly. The genome is also AT-rich, because approximately 63% of the sequence consists of adenine and thymine. Its size and GC content closely match the general pattern reported across Lilium, where plastomes are approximately 152 kb and have about 37.0–37.1% GC content.

# Plastid vs mitochondrial genomes
Similarities
Both plastid and mitochondrial genomes are organellar genomes located outside the nucleus. Both originated from bacterial ancestors through endosymbiosis, possess their own DNA, contain rRNA and tRNA genes, and encode only part of the proteins required for organelle function because many ancestral organellar genes have been transferred to the nucleus. Both can also show uniparental inheritance, although the exact inheritance pattern varies among plant lineages.
**Differences**
| **Feature**            | **Plastid genome**                                                                   | **Mitochondrial genome**                                                          |
| ---------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------- |
| Location               | Plastids/chloroplasts                                                                | Mitochondria                                                                      |
| Main role              | Photosynthesis, carbon fixation, plastid gene expression                             | Respiration and oxidative phosphorylation                                         |
| Typical organization   | Relatively conserved LSC–IR–SSC–IR arrangement                                       | Highly variable and structurally dynamic                                          |
| Typical size in plants | Usually around 120–170 kb                                                            | Usually much larger and highly variable                                           |
| Gene content           | Photosynthesis, ATP synthase, ribosomal, rRNA, tRNA, and plastid transcription genes | Mainly respiration-related genes, rRNA, tRNA, and mitochondrial translation genes |
| Gene order             | Relatively conserved                                                                 | Frequently rearranged                                                             |
| Recombination          | Generally limited                                                                    | Extensive repeat-mediated recombination is common                                 |
| Structural evolution   | Relatively slow                                                                      | Rapid structural change despite often slow nucleotide substitution                |
| RNA editing            | Present                                                                              | Often more extensive in plant mitochondria                                        |
| Common applications    | Phylogenetics, barcoding, maternal lineage studies, plastid evolution                | Cytoplasmic male sterility, mitochondrial evolution, respiration studies          |

# Practical value of plastid genomes

Plastid genomes are useful because they are relatively small, compact, and easy to compare among species. Their high copy number can make them easier to recover from limited or degraded plant material, and their conserved gene order simplifies genome assembly and comparative analysis. Complete plastomes are particularly useful for plant phylogenetics, species identification, DNA barcoding, phylogeography, and studies of plastid genome evolution. In Lilium, complete plastome data have provided strong phylogenetic information and helped identify mutation hotspots among closely related taxa.
The main limitation is that the plastome behaves largely as a single linked organellar genome and often reflects only one parental lineage. It therefore does not capture the full biparental evolutionary history, nuclear recombination, sex-linked inheritance, or most genes responsible for complex traits. Nuclear genomic data are more appropriate for questions involving genome-wide population structure, hybridization, quantitative traits, or genes controlling characteristics such as flower color or metabolism.
A suitable plastid-genome research question would be: Do populations of Lilium lancifolium from different geographic regions contain distinct plastid lineages? A suitable nuclear-genome question would be: Which nuclear genes control flower pigmentation or other complex traits in Lilium lancifolium?

| **Feature**                       | **Plastid genome**                                                                                         | **Mitochondrial genome**                                                                      |
| --------------------------------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Cellular location                 | Plastids, especially chloroplasts                                                                          | Mitochondria                                                                                  |
| Main biological functions         | Photosynthesis, carbon fixation, plastid transcription and translation                                     | Respiration, oxidative phosphorylation, mitochondrial transcription and translation           |
| Typical genome organization       | Usually a conserved quadripartite plastome with LSC, SSC, and two IR regions                               | Highly variable; repeat-mediated recombination can generate multiple molecular configurations |
| Relative genome size              | Small, usually about 120–170 kb; 152,575 bp in this analysis                                               | Generally larger and much more variable in land plants                                        |
| Gene content                      | Photosystem, ATP synthase, cytochrome b6f, *rbcL*, RNA polymerase, ribosomal proteins, rRNA and tRNA genes | Primarily genes associated with respiration plus rRNA, tRNA, and mitochondrial translation    |
| Copy number                       | High; many plastome copies can occur within a cell                                                         | Variable among tissues and developmental stages                                               |
| Inheritance                       | Often maternal in angiosperms, although paternal and biparental inheritance occur in some lineages         | Often maternal, although exceptions occur                                                     |
| Recombination / structural change | Usually structurally conserved; IR expansion or contraction can occur                                      | Extensive recombination and structural rearrangement are common                               |
| Mutation / substitution pattern   | Generally conserved, with lineage- and gene-specific variation                                             | Plant mitochondrial nucleotide substitution can be slow despite extensive structural change   |
| Common research application       | Phylogenetics, DNA barcoding, species identification, phylogeography, plastid evolution                    | Cytoplasmic male sterility, mitochondrial evolution, respiration, organelle inheritance       |

# REFERENCE LINKS

| **Reference**                                                                                                  | **Link / Information**                                                                                                           |
| -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| NCBI Nucleotide — OR400160                                                                                     | [https://www.ncbi.nlm.nih.gov/nuccore/OR400160](https://www.ncbi.nlm.nih.gov/nuccore/OR400160)                                   |
| Galaxy                                                                                                         | [https://usegalaxy.org](https://usegalaxy.org)                                                                                   |
| Kim et al. — Chloroplast genomes of *Lilium lancifolium*, *L. amabile*, *L. callosum*, and *L. philadelphicum* | Detailed characterization of *Lilium* plastomes, including gene content, structure, and pseudogenes. ([PubMed Central (PMC)][1]) |
| Du et al. — Complete chloroplast genome sequences of *Lilium*                                                  | Comparative analysis of *Lilium* plastome size, LSC, SSC, IR regions, gene numbers, and phylogeny. ([PubMed Central (PMC)][2])   |
| Choi et al. — Plastid transcriptome analysis of *Lilium lancifolium*                                           | Reports plastome organization, pseudogene variation, and RNA-editing patterns. ([PubMed Central (PMC)][3])                       |
| Yishui Lily 140 complete chloroplast genome                                                                    | Reports a 152,643-bp *L. lancifolium* plastome with 132 genes and detailed intron information. ([PubMed Central (PMC)][4])       |

[1]: https://pmc.ncbi.nlm.nih.gov/articles/PMC5655457/?utm_source=chatgpt.com "Chloroplast genomes of Lilium lancifolium, L. amabile, L. callosum, and L. philadelphicum: Molecular characterization and their use in phylogenetic analysis in the genus Lilium and other allied genera in the order Liliales - PMC"
[2]: https://pmc.ncbi.nlm.nih.gov/articles/PMC5515919/?utm_source=chatgpt.com "Complete chloroplast genome sequences of Lilium: insights into evolutionary dynamics and phylogenetic analyses - PMC"
[3]: https://pmc.ncbi.nlm.nih.gov/articles/PMC6491592/?utm_source=chatgpt.com "The implication of plastid transcriptome analysis in petaloid monocotyledons: A case study of Lilium lancifolium (Liliaceae, Liliales) - PMC"
[4]: https://pmc.ncbi.nlm.nih.gov/articles/PMC8567886/?utm_source=chatgpt.com "The complete chloroplast genome of Yishui Lily 140 (Liliaceae Lilium lancifolium) yielded by next-generation sequencing - PMC"
