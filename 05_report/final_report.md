**CELL AND MOLECULAR BIOLOGY LABORATORY**

**From Gene Mutation to Disease**

*Li-Fraumeni Syndrome and the TP53 R175H Mutation*

|                                                          |                                           |
|----------------------------------------------------------|-------------------------------------------|
| Name: Alama, Rhealyn F.                                  | Section: B                                |
| Date: September 18, 2026                                 | Activity 4: Gene Mutation to Disease      |
| Instructor: Sir Abner A. Bucol & Ma’am Lilibeth A. Bucol | Subject: BIO 300-Cell & Molecular Biology |

# **Part 1: Select a Human Disease and Gene**

|                          |                                                      |
|--------------------------|------------------------------------------------------|
| **Item**                 | **Answer**                                           |
| **Disease**              | Li-Fraumeni syndrome                                 |
| **Official Gene Symbol** | TP53                                                 |
| **Chromosome Location**  | 17p13.1                                              |
| **Protein**              | p53 (tumor protein p53 / cellular tumor antigen p53) |
| **Inheritance**          | Autosomal dominant                                   |

# **Part 2: A. Disease — Li-Fraumeni Syndrome**

**13. What is the disease or phenotype?**

> Li-Fraumeni syndrome (LFS), a hereditary cancer predisposition syndrome.

**14. What are its major clinical characteristics?**

> Early-onset and multiple primary cancers across the lifespan, most classically soft-tissue and bone sarcomas, premenopausal breast cancer, brain tumors, and adrenocortical carcinoma; leukemia and other cancers may also occur. Cancers often appear decades earlier than in the general population.

**15. Which cells, tissues, or organs are mainly affected?**

> It’s not tissue-specific, but breast, bone/soft tissue, brain, adrenal cortex, and blood-forming (hematopoietic) tissue are most classically involved, but virtually any tissue can be affected because TP53 normally protects all cell types.

**16. What is its genetic basis?**

> Germline (inherited) heterozygous pathogenic variants in TP53, the gene encoding the p53 tumor-suppressor protein. A single mutant allele is inherited from a parent (or arises de novo); loss/inactivation of the remaining normal allele in a cell contributes to tumor formation.

**17. What is its inheritance pattern, if applicable?**

> Autosomal dominant with high penetrance.

## **B. Gene and Normal Protein**

**18. What is the official gene symbol?**

> TP53

**19. On which human chromosome is the gene located?**

> Chromosome 17, band 17p13.1

**20. What does the gene normally encode?**

> The p53 protein, a 393-amino-acid sequence-specific DNA-binding transcription factor.

**21. What is the normal biological function of the protein?**

> p53 is the central node of the cellular DNA-damage response. In response to DNA damage, oncogene activation, or other cellular stress, p53 accumulates and binds specific DNA sequences to activate transcription of target genes that cause cell-cycle arrest (e.g., CDKN1A/p21), DNA repair, senescence, or apoptosis or halting the proliferation of cells with damaged DNA.

**22. Where in the cell is the protein normally found?**

> Primarily the nucleus, where it acts as a transcription factor; it shuttles between nucleus and cytoplasm and is normally kept at low levels by MDM2-mediated degradation until stress signals stabilize it.

**23. In what biological pathway or cellular process does it participate?**

> The DNA-damage response / cell-cycle checkpoint pathway, including the p53–MDM2 regulatory loop, apoptosis, and cellular senescence pathways.

## **C. Documented Mutation**

|                              |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Item**                     | **Answer**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Gene**                     | TP53                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Reference transcript**     | NM_000546.6                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Exact variant notation**   | NM_000546.6(TP53):c.524G\>A (p.Arg175His)                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Nucleotide change**        | G\>A substitution at coding position 524 (codon CGC → CAC)                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Predicted protein change** | Arginine to Histidine at amino acid position 175 (p.Arg175His / R175H)                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Mutation type**            | Missense                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **ClinVar accession**        | VCV000012374.13 (Variation ID 12374); dbSNP rs28934578                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Clinical interpretation**  | Pathogenic for Li-Fraumeni syndrome (classified by the ClinGen TP53 Variant Curation Expert Panel)                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Scientific support**       | One of the most frequently reported TP53 "hotspot" mutations in both germline Li-Fraumeni families and somatic tumors; R175 lies in the DNA-binding domain, in a loop region stabilized by a structural zinc ion required for proper domain folding (Cho et al., 1994). Reported in numerous families meeting Li-Fraumeni/ Chompret criteria (Birch 1994; Kyritsis 1994; Chompret 2000; Bougeard 2001; Nichols 2001) and functionally shown to abolish sequence-specific DNA binding and transactivation activity. |

# **Part 3: Obtain the Normal Reference Sequence**

|                                          |                                               |
|------------------------------------------|-----------------------------------------------|
| **Item**                                 | **Answer**                                    |
| **Reference transcript / CDS accession** | NM_000546.6 (CDS region 143–1324)             |
| **Reference protein accession**          | NP_000537.3                                   |
| **Sequence used**                        | Coding sequence (CDS) only, 1,182 nucleotides |
| **Filename saved**                       | TP53_WT_CDS.fasta                             |

# **Part 4: Import the Normal Sequence into Galaxy**

The WT CDS was uploaded into a new Galaxy history named Alama_LiFraumeni_TP53_Mutation_Lab, containing all datasets for this activity: the WT CDS, WT predicted protein sequence, documented mutant (R175H) CDS and predicted protein sequence, the artificial mutant CDS and predicted protein sequence, and both needle alignment outputs.

# **Part 5: Establish the Wild-Type Control**

|                              |                   |
|------------------------------|-------------------|
| **Item**                     | **Answer**        |
| **CDS length**               | 1,182 nucleotides |
| **Predicted protein length** | 393 amino acids   |
| **Start codon**              | ATG               |
| **Stop codon**               | TGA               |
| **Reading frame**            | Frame 1           |
| **First 10 amino acids**     | MEEPQSDPSV        |
| **Last 10 amino acids**      | MFKTEGPDSD        |

The predicted WT protein sequence (TP53_WT_protein.fasta) matched the accepted reference protein NP_000537.3 in length (393 aa) and sequence, confirming the CDS and translation were correct before proceeding.

# **Part 6: Formulate a Mutation Hypothesis**

|                                          |                                                                                                                                                                                                                                                                                                                              |
|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Item**                                 | **Answer**                                                                                                                                                                                                                                                                                                                   |
| **Mutation and exact nucleotide change** | c.524G\>A (single base substitution)                                                                                                                                                                                                                                                                                         |
| **Number of nucleotide(s) affected**     | 1                                                                                                                                                                                                                                                                                                                            |
| **Predicted mutation type**              | Missense                                                                                                                                                                                                                                                                                                                     |
| **Predicted effect on reading frame**    | None — a single substitution does not shift the frame                                                                                                                                                                                                                                                                        |
| **Predicted effect on protein length**   | None expected — codon 175 is not a stop codon before or after the change                                                                                                                                                                                                                                                     |
| **Predicted effect on protein function** | Arg175 lies in the zinc-stabilized loop region of the DNA-binding domain (Cho et al., 1994). Substituting the bulky, positively charged arginine with histidine was predicted to distort the local fold of the DNA-binding domain and impair p53's ability to bind its target DNA sequences, without shortening the protein. |

# **Part 7: Create the Mutant Sequence**

|                                  |                        |
|----------------------------------|------------------------|
| **Item**                         | **Answer**             |
| **Original nucleotide position** | 524 (within codon 175) |
| **Original sequence (codon)**    | CGC (Arg)              |
| **Mutant sequence (codon)**      | CAC (His)              |
| **Number of bases substituted**  | 1                      |
| **Mutation type**                | Missense substitution  |
| **Filename saved**               | TP53_R175H_CDS.fasta   |

A copy of the WT CDS was made before editing; the single-base change was introduced only in the copy, leaving TP53_WT_CDS.fasta unaltered.

# **Part 8: Translate the Mutant Sequence**

|                                                |                               |
|------------------------------------------------|-------------------------------|
| **Item**                                       | **Answer**                    |
| **Mutant CDS length**                          | 1,182 nucleotides (unchanged) |
| **Predicted mutant protein length**            | 393 amino acids (unchanged)   |
| **Reading frame**                              | Frame 1 (unchanged)           |
| **Location of first amino-acid difference**    | Position 175 (Arg → His)      |
| **Premature stop codon**                       | None                          |
| **Approximate number of amino acids affected** | 1                             |

# **Part 9: Compare WT and Mutant Predicted Protein Sequences**

Comparison performed with EMBOSS needle (Galaxy), aligning TP53_WT_protein.fasta against TP53_R175H_protein.fasta.

**Result:** 392/393 identity (99.7%), 0 gaps, single mismatch at position 175 (R→H).

**24. At what amino-acid position do the sequences first differ?**

> Position 175

**25. Is only one amino acid affected?**

> Yes

**26. Are multiple downstream amino acids changed?**

> No

**27. Was an amino acid deleted or inserted?**

> No

**28. Was a premature stop codon produced?**

> No

**29. Did the reading frame change?**

> No

**30. Did the protein length change?**

> No — 393 amino acids in both WT and mutant

**31. Is the mutation missense, nonsense, frameshift, in-frame deletion/insertion, repeat expansion, or another type?**

> Missense

# **Part 10: Explain the Molecular Consequence**

The c.524G\>A substitution changes codon 175 from CGC (arginine) to CAC (histidine). Because this is a single-base substitution within one codon, no other codons are shifted, so the rest of the 393-amino-acid predicted protein sequence remains unchanged.

However, position 175 is not an ordinary residue: it sits in the p53 DNA-binding domain, in a loop region that a structural zinc ion helps hold in the correct three-dimensional shape for DNA contact (Cho et al., 1994). Replacing the compact, positively charged arginine side chain with the bulkier, differently charged histidine distorts this local structure.

The resulting protein is predicted to fold improperly in this region and to lose its ability to bind target DNA sequences with normal affinity. Because p53 must bind DNA to activate transcription of genes controlling cell-cycle arrest (e.g., CDKN1A/p21) and apoptosis, a p53 protein that cannot bind DNA effectively fails to halt the proliferation of cells that have sustained DNA damage. Cells carrying this defective p53 (along with loss of the remaining normal allele) can accumulate further mutations unchecked, driving the early-onset, multiple-primary-tumor phenotype characteristic of Li-Fraumeni syndrome.

Some R175H studies additionally suggest a "gain-of-function" effect, in which the misfolded mutant protein actively promotes tumor growth beyond simple loss of the normal tumor-suppressor activity.

Summary chain: TP53 gene → c.524G\>A (CGC→CAC) → p.Arg175His in the predicted protein sequence → impaired DNA binding and transactivation by p53 → failed cell-cycle arrest and apoptosis after DNA damage → early-onset, multiple cancers (Li-Fraumeni syndrome).

# **Part 11: Second Experiment — Artificial Mutation**

|                                             |                                                                                                                                                                                                                                                                   |
|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Item**                                    | **Answer**                                                                                                                                                                                                                                                        |
| **Position edited**                         | Nucleotide 100 of the WT CDS (within codon 34)                                                                                                                                                                                                                    |
| **Nucleotide deleted**                      | C (single base)                                                                                                                                                                                                                                                   |
| **Sequence change**                         | ...TGTCCCCCTTG... (WT) → ...TGTCCCCTTG... (mutant, C deleted)                                                                                                                                                                                                     |
| **Filename saved**                          | TP53_artificial_1ntdel_CDS.fasta / TP53_artificial_1ntdel_protein.fasta                                                                                                                                                                                           |
| **Prediction before translating**           | A 1-nucleotide deletion is not divisible by 3, so it was predicted to shift the reading frame from the deletion point onward, scrambling all downstream codons and very likely producing a premature stop codon and a shortened, nonfunctional predicted protein. |
| **Actual mutant CDS length**                | 1,181 nucleotides (1 nt shorter than WT)                                                                                                                                                                                                                          |
| **Actual predicted mutant protein length**  | 42 amino acids (versus 393 aa WT)                                                                                                                                                                                                                                 |
| **Location of first amino-acid difference** | Position 35                                                                                                                                                                                                                                                       |
| **Premature stop codon**                    | Yes — reached at amino acid 42                                                                                                                                                                                                                                    |
| **Reading frame**                           | Shifted from codon 34 onward                                                                                                                                                                                                                                      |

needle alignment of the WT predicted protein sequence vs. this artificial mutant predicted protein sequence: 37/394 identity (9.4%), confirming that only the first 34 residues remain identical to WT before the sequence diverges completely.

# **Part 12: Compare the Documented and Artificial Mutations**

|                                     |                     |                                                                           |                                                                                                                        |
|-------------------------------------|---------------------|---------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
|                                     | **WT**              | **R175H (documented)**                                                    | **Artificial (1-nt del)**                                                                                              |
| **CDS length**                      | 1,182 nt            | 1,182 nt                                                                  | 1,181 nt                                                                                                               |
| **Predicted protein length**        | 393 aa              | 393 aa                                                                    | 42 aa                                                                                                                  |
| **Mutation type**                   | —                   | Missense                                                                  | Frameshift                                                                                                             |
| **Reading frame changed?**          | —                   | No                                                                        | Yes                                                                                                                    |
| **Premature stop?**                 | —                   | No                                                                        | Yes (at aa 42)                                                                                                         |
| **Amino acids affected**            | —                   | 1 (position 175)                                                          | ~360 (from position 35 onward)                                                                                         |
| **Expected functional consequence** | Normal p53 function | Loss of DNA-binding / transactivation activity; protein still full-length | Severely truncated, almost certainly nonfunctional protein lacking most of the DNA-binding and tetramerization domains |

Both mutations start from a single-nucleotide change, yet their consequences differ enormously. The documented R175H substitution replaces exactly one amino acid because it does not alter how the ribosome groups the remaining nucleotides into codons, the reading frame is preserved.

The artificial 1-nucleotide deletion removes one base whose position is not a multiple of three, so every codon downstream of the deletion is regrouped incorrectly, producing a completely different, garbled amino-acid sequence until a new stop codon happens to appear by chance, here, only 8 codons later. This comparison illustrates why the type and size of a mutation, not just its presence, determines the severity of its effect: a substitution can leave a protein nearly intact, while a small frameshifting deletion can destroy most of the protein.

# **Part 13: Interpretation Questions**

**32. Why does the exact location of a mutation matter?**

> The consequence of a mutation depends on which codon and which functional domain it falls in. A change at a structurally or catalytically critical residue (like Arg175, in the zinc-stabilized loop region of the DNA-binding domain) can cripple protein function, while a change at a non-critical or redundant position may have little effect. Location also determines whether a frameshift or premature stop removes essential downstream domains.

**33. Why can deleting three nucleotides produce a different result from deleting one or two nucleotides?**

> The genetic code is read in non-overlapping triplets. Deleting a multiple of three nucleotides removes whole codons and keeps every codon after the deletion in its original grouping (in-frame deletion), removing one or more amino acids but leaving the rest of the sequence correct. Deleting one or two nucleotides is not a multiple of three, so it shifts how all subsequent nucleotides are grouped into codons, scrambling the entire downstream sequence (frameshift).

**34. Does every mutation change the amino-acid sequence? Explain.**

> No. Because the genetic code is degenerate (redundant), some nucleotide substitutions change a codon to a different codon that still specifies the same amino acid (a synonymous or silent mutation), leaving the protein sequence unchanged.

**35. Does every amino-acid substitution destroy protein function? Explain.**

> No. If the substituted amino acid has similar chemical properties and occurs at a non-critical position, the protein may fold and function normally (a "tolerated" or benign missense variant). Function is more likely to be destroyed when the substitution occurs at an active site, a structurally critical residue (as with Arg175), or introduces a very different type of side chain.

**36. Why can a frameshift affect many amino acids even if only one nucleotide was deleted?**

> Deleting one nucleotide shifts the triplet reading frame for every codon downstream of the deletion site, so the ribosome reads an entirely new, incorrect series of codons from that point until a new stop codon is reached, altering potentially hundreds of amino acids even though only one base was physically removed.

**37. Why might a premature stop codon produce a nonfunctional protein?**

> A premature stop codon truncates translation, so the protein is missing some or all of its downstream functional domains (such as domains needed for DNA binding, oligomerization, or catalysis). The truncated protein may also misfold or be degraded by cellular quality-control systems.

**38. Could a mutation affect protein function without greatly changing protein length?**

> Yes. A missense substitution, as in R175H, keeps the protein the same length but can still destroy function if it disrupts a critical structural or functional residue.

**39. Could a mutation cause disease without changing the protein sequence? Give a possible molecular mechanism.**

> Yes. A mutation in a non-coding regulatory region (such as a promoter or splice site) or a synonymous coding change that affects mRNA splicing or stability could reduce the amount of normal protein produced, causing disease through insufficient dosage rather than an altered protein sequence.

**40. What evidence from your analysis supports the proposed molecular mechanism of your disease?**

> The needle alignment directly confirms that R175H changes exactly one residue (position 175) without altering predicted protein length or reading frame, consistent with a missense mechanism. The known structural role of Arg175 in the zinc-stabilized loop region of the DNA-binding domain (Cho et al., 1994) supports the prediction that this single substitution disrupts DNA binding rather than removing large portions of the protein.

**41. Which conclusions are supported directly by your computational results, and which require evidence from published experimental studies?**

> Directly supported by this analysis: the exact nucleotide and amino-acid change, the position of the substitution, and the fact that predicted protein length and reading frame are unaffected. Requiring outside experimental evidence: that this substitution actually disrupts DNA binding in a living cell, that this leads to loss of transcriptional activation of p53 target genes, and that this ultimately causes the clinical cancer predisposition seen in Li-Fraumeni families — these functional and clinical claims come from published biochemical and clinical studies, not from sequence translation alone.

# **Methods**

The wild-type (WT) TP53 CDS (NM_000546.6, nt 143–1324) was retrieved from NCBI RefSeq (TP53_WT_CDS.fasta), uploaded to a new Galaxy history (Alama_LiFraumeni_TP53_Mutation_Lab), and translated to give the predicted WT protein sequence, which was checked against NP_000537.3.

A copy of the WT CDS was manually edited to introduce c.524G\>A (R175H; TP53_R175H_CDS.fasta). A second copy was edited to delete one nucleotide at position 100, within codon 34 (TP53_artificial_1ntdel_CDS.fasta). Both mutant CDSs were translated the same way as the WT, and each predicted mutant protein was aligned to the WT with EMBOSS needle (gap open 10.0, gap extend 0.5). The original WT files were never modified.

# **Results**

The WT CDS gave a 393-amino-acid predicted protein identical to NP_000537.3. The R175H CDS gave a 393-amino-acid predicted protein that differs from WT only at position 175 (Arg→His), with no frameshift and no premature stop (needle: 392/393 identity, 99.7%).

The 1-nt deletion shifted the reading frame after codon 34. The first 34 amino acids matched WT, and a premature stop codon gave a 42-amino-acid predicted protein (needle: 37/394 identity, 9.4%). Both edits changed one nucleotide, but only the deletion altered the reading frame.

# **Limitations**

This lab is computational only. The protein sequences are predicted; expression, folding, localization, and stability were not tested, and no structural modeling was done. The effect of R175H on the DNA-binding domain's structure and on DNA binding, and its link to Li-Fraumeni syndrome, come from published studies (ClinVar, ClinGen, family and functional studies), not from this analysis. The artificial deletion was placed arbitrarily, so it illustrates frameshift principles rather than a disease mechanism.

# **Conclusion**

The documented TP53 variant c.524G\>A (p.Arg175His) changes one amino acid in the DNA-binding domain without changing predicted protein length. Based on the known role of Arg175 in the zinc-stabilized DNA-binding region (Cho et al., 1994), it is predicted to impair DNA binding, consistent with its association with Li-Fraumeni syndrome. The artificial 1-nt deletion shifted the reading frame and produced a 42-amino-acid predicted protein, about 11% of the WT length. Together, the results show that a mutation's type, location, and effect on the reading frame, not the number of nucleotides changed, determine its consequence for the protein.

**Galaxy History Link:**

<https://usegalaxy.org/u/alama_rhealyn_/h/alama-lifraumeni-tp53-mutation-lab>

**GitHub Repository Link:**

<https://github.com/rhealynalama-bio/Alama_LiFraumeni_TP53_Mutation_Lab/tree/main>

# **References**

NCBI RefSeq: NM_000546.6, NP_000537.3 (TP53 reference transcript and protein).

ClinVar Variation ID 12374 (VCV000012374.13): NM_000546.6(TP53):c.524G\>A (p.Arg175His).

ClinGen TP53 Variant Curation Expert Panel classification of c.524G\>A (p.Arg175His) as Pathogenic for Li-Fraumeni syndrome.

Birch JM, Hartley AL, Tricker KJ, et al. Prevalence and diversity of constitutional mutations in the p53 gene among 21 Li-Fraumeni families. Cancer Res. 1994;54(5):1298–1304.

Kyritsis AP, Bondy ML, Xiao M, et al. Germline p53 gene mutations in subsets of glioma patients. J Natl Cancer Inst. 1994;86(5):344–349.

Chompret A, Brugières L, Ronsin M, et al. P53 germline mutations in childhood cancers and cancer risk for carrier individuals. Br J Cancer. 2000;82(12):1932–1937.

Bougeard G, Limacher JM, Martin C, et al. Detection of 11 germline inactivating TP53 mutations and absence of TP63 and HCHK2 mutations in 17 French families with Li-Fraumeni or Li-Fraumeni-like syndrome. J Med Genet. 2001;38(4):253–257.

Nichols KE, Malkin D, Garber JE, Fraumeni JF Jr, Li FP. Germ-line p53 mutations predispose to a wide spectrum of early-onset cancers. Cancer Epidemiol Biomarkers Prev. 2001;10(2):83–87.

Cho Y, Gorina S, Jeffrey PD, Pavletich NP. Crystal structure of a p53 tumor suppressor-DNA complex: understanding tumorigenic mutations. Science. 1994;265(5170):346–355.

Galaxy needle (EMBOSS) pairwise alignment outputs generated in this laboratory (history: Alama_LiFraumeni_TP53_Mutation_Lab).
