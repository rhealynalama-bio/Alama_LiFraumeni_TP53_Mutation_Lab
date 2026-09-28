# From Gene Mutation to Disease: Li-Fraumeni Syndrome and the TP53 R175H Mutation

**Name:** Alama, Rhealyn F.  
**Section:** B  
**Subject:** Cell & Molecular Biology
**Activity:** 4 Gene Mutation to Disease 
**Instructors:** Sir Abner A. Bucol & Ma'am Lilibeth A. Bucol
**Date:** September 18, 2026 
**Galaxy history:** Alama_LiFraumeni_TP53_Mutation_Lab

---

## 1. Disease Background

| Item | Answer |
|---|---|
| **Disease** | Li-Fraumeni syndrome (LFS), a hereditary cancer predisposition syndrome |
| **Inheritance** | Autosomal dominant with high penetrance |

**Major clinical characteristics:** Early-onset and multiple primary cancers across the lifespan, most classically soft-tissue and bone sarcomas, premenopausal breast cancer, brain tumors, and adrenocortical carcinoma. Leukemia and other cancers may also occur. Cancers often appear decades earlier than in the general population.

**Tissues affected:** LFS is not tissue-specific. Breast, bone/soft tissue, brain, adrenal cortex, and blood-forming tissue are most classically involved, but virtually any tissue can be affected because TP53 normally protects all cell types.

**Genetic basis:** Germline (inherited) heterozygous pathogenic variants in TP53, the gene encoding the p53 tumor-suppressor protein. A single mutant allele is inherited from a parent (or arises de novo). Loss or inactivation of the remaining normal allele in a cell contributes to tumor formation.

## 2. Gene and Normal Protein Function

| Item | Answer |
|---|---|
| **Gene symbol** | TP53 |
| **Chromosome** | 17p13.1 |
| **Protein** | p53 (tumor protein p53 / cellular tumor antigen p53), 393 amino acids |
| **Reference transcript / CDS** | NM_000546.6 (CDS region 143–1324, 1,182 nt) |
| **Reference protein** | NP_000537.3 |

**Function:** p53 is a sequence-specific DNA-binding transcription factor and the central node of the cellular DNA-damage response. After DNA damage, oncogene activation, or other stress, p53 accumulates and binds specific DNA sequences to activate target genes that cause cell-cycle arrest (e.g., CDKN1A/p21), DNA repair, senescence, or apoptosis. This halts the proliferation of cells with damaged DNA.

**Location:** Primarily the nucleus, where it acts as a transcription factor. It shuttles between nucleus and cytoplasm and is kept at low levels by MDM2-mediated degradation until stress signals stabilize it.

**Pathway:** DNA-damage response and cell-cycle checkpoint, including the p53–MDM2 regulatory loop, apoptosis, and cellular senescence.

## 3. Documented Mutation

| Item | Answer |
|---|---|
| **Gene** | TP53 |
| **Reference transcript** | NM_000546.6 |
| **Variant notation** | NM_000546.6(TP53):c.524G>A (p.Arg175His) |
| **Nucleotide change** | G>A at coding position 524 (codon CGC → CAC) |
| **Protein change** | Arginine to Histidine at position 175 (R175H) |
| **Mutation type** | Missense |
| **ClinVar accession** | VCV000012374.13 (Variation ID 12374); dbSNP rs28934578 |
| **Clinical interpretation** | Pathogenic for Li-Fraumeni syndrome (ClinGen TP53 Variant Curation Expert Panel) |
| **Scientific support** | One of the most frequently reported TP53 hotspot mutations in germline LFS families and somatic tumors. R175 lies in the DNA-binding domain, in a loop region stabilized by a structural zinc ion (Cho et al., 1994). Reported in numerous families meeting Li-Fraumeni/Chompret criteria (Birch 1994; Kyritsis 1994; Chompret 2000; Bougeard 2001; Nichols 2001) and functionally shown to abolish sequence-specific DNA binding and transactivation. |

## 4. Hypothesis

Written before generating the mutant predicted protein sequence.

| Item | Prediction |
|---|---|
| **Mutation** | c.524G>A (single base substitution) |
| **Nucleotides affected** | 1 |
| **Mutation type** | Missense |
| **Reading frame** | No effect; a single substitution does not shift the frame |
| **Protein length** | No change expected; codon 175 is not a stop codon before or after the change |
| **Protein function** | Arg175 lies in the zinc-stabilized loop region of the DNA-binding domain (Cho et al., 1994). Replacing arginine with the bulkier histidine was predicted to distort the local fold and impair DNA binding, without shortening the protein. |

## 5. Methods

The wild-type (WT) TP53 CDS (NM_000546.6, nt 143–1324) was retrieved from NCBI RefSeq (`TP53_WT_CDS.fasta`), uploaded to a new Galaxy history (Alama_LiFraumeni_TP53_Mutation_Lab), and translated to give the predicted WT protein sequence, which was checked against NP_000537.3.

A copy of the WT CDS was manually edited to introduce c.524G>A (R175H; `TP53_R175H_CDS.fasta`). A second copy was edited to delete one nucleotide at position 100, within codon 34 (`TP53_artificial_1ntdel_CDS.fasta`). Both mutant CDSs were translated the same way as the WT, and each predicted mutant protein sequence was aligned to the WT with EMBOSS needle (gap open 10.0, gap extend 0.5). The original WT files were never modified.

## 6. Results

**WT control**

| Item | Value |
|---|---|
| CDS length | 1,182 nucleotides |
| Predicted protein length | 393 amino acids |
| Start / stop codon | ATG / TGA |
| Reading frame | Frame 1 |
| First 10 amino acids | MEEPQSDPSV |
| Last 10 amino acids | MFKTEGPDSD |

The WT CDS gave a 393-amino-acid predicted protein sequence identical to NP_000537.3.

**R175H mutant (c.524G>A)**

| Item | Value |
|---|---|
| Original / mutant codon | CGC (Arg) → CAC (His), position 524 |
| Mutant CDS length | 1,182 nucleotides (unchanged) |
| Predicted mutant protein length | 393 amino acids (unchanged) |
| Reading frame | Frame 1 (unchanged) |
| First amino-acid difference | Position 175 (Arg → His) |
| Premature stop codon | None |
| Amino acids affected | 1 |

The R175H CDS differs from WT only at position 175, with no frameshift and no premature stop (needle: 392/393 identity, 99.7%).

The 1-nt deletion shifted the reading frame after codon 34. The first 34 amino acids matched WT, and a premature stop codon gave a 42-amino-acid predicted protein sequence (needle: 37/394 identity, 9.4%). Both edits changed one nucleotide, but only the deletion altered the reading frame.

## 7. WT versus Mutant Predicted Protein Sequence Comparison (R175H)

EMBOSS needle (Galaxy) aligned `TP53_WT_protein.fasta` against `TP53_R175H_protein.fasta`. **Result:** 392/393 identity (99.7%), 0 gaps, single mismatch at position 175 (R→H).

| Question | Answer |
|---|---|
| First position of difference | 175 |
| Only one amino acid affected? | Yes |
| Multiple downstream amino acids changed? | No |
| Amino acid deleted or inserted? | No |
| Premature stop codon? | No |
| Reading frame changed? | No |
| Protein length changed? | No, 393 amino acids in both |
| Mutation type | Missense |

## 8. Artificial Mutation Experiment

| Item | Answer |
|---|---|
| **Position edited** | Nucleotide 100 of the WT CDS (within codon 34) |
| **Nucleotide deleted** | C (single base) |
| **Sequence change** | ...TGTCCCCCTTG... (WT) → ...TGTCCCCTTG... (mutant, C deleted) |
| **Files** | `TP53_artificial_1ntdel_CDS.fasta`, `TP53_artificial_1ntdel_protein.fasta` |
| **Prediction (before translating)** | A 1-nucleotide deletion is not divisible by 3, so it was predicted to shift the reading frame from the deletion point onward, scrambling downstream codons and very likely producing a premature stop codon and a shortened, nonfunctional predicted protein. |
| **Actual mutant CDS length** | 1,181 nucleotides (1 nt shorter than WT) |
| **Actual predicted protein length** | 42 amino acids (versus 393 aa WT) |
| **First amino-acid difference** | Position 35 |
| **Premature stop codon** | Yes, reached at amino acid 42 |
| **Reading frame** | Shifted from codon 34 onward |

needle alignment of the WT predicted protein sequence against the artificial mutant: 37/394 identity (9.4%). Only the first 34 residues remain identical to WT before the sequence diverges.

### Comparison of WT, documented, and artificial mutations

| | WT | R175H (documented) | Artificial (1-nt del) |
|---|---|---|---|
| **CDS length** | 1,182 nt | 1,182 nt | 1,181 nt |
| **Predicted protein length** | 393 aa | 393 aa | 42 aa |
| **Mutation type** | n/a | Missense | Frameshift |
| **Reading frame changed?** | n/a | No | Yes |
| **Premature stop?** | n/a | No | Yes (at aa 42) |
| **Amino acids affected** | n/a | 1 (position 175) | ~360 (from position 35 onward) |
| **Expected functional consequence** | Normal p53 function | Loss of DNA-binding/transactivation activity; protein still full-length | Severely truncated, almost certainly nonfunctional protein lacking most of the DNA-binding and tetramerization domains |

Both mutations start from a single-nucleotide change, yet their consequences differ greatly. The R175H substitution replaces exactly one amino acid because it does not alter how the ribosome groups the remaining nucleotides into codons; the reading frame is preserved.

The 1-nucleotide deletion removes one base that is not a multiple of three, so every codon downstream is regrouped incorrectly. This gives a garbled amino-acid sequence until a new stop codon appears by chance, here only 8 codons later. The type and size of a mutation, not just its presence, determine the severity of its effect.

## 9. Molecular Interpretation

The c.524G>A substitution changes codon 175 from CGC (arginine) to CAC (histidine). Because this is a single-base substitution within one codon, no other codons are shifted, and the rest of the 393-amino-acid predicted protein sequence remains unchanged.

However, position 175 sits in the p53 DNA-binding domain, in a loop region that a structural zinc ion helps hold in the correct three-dimensional shape for DNA contact (Cho et al., 1994). Replacing the compact, positively charged arginine side chain with the bulkier, differently charged histidine distorts this local structure.

The resulting protein is predicted to fold improperly in this region and lose its ability to bind target DNA with normal affinity. Because p53 must bind DNA to activate genes controlling cell-cycle arrest (e.g., CDKN1A/p21) and apoptosis, a p53 protein that cannot bind DNA effectively fails to halt the proliferation of cells with DNA damage. Cells carrying this defective p53 (along with loss of the remaining normal allele) can accumulate further mutations unchecked, driving the early-onset, multiple-primary-tumor phenotype of Li-Fraumeni syndrome.

Some R175H studies also suggest a gain-of-function effect, in which the misfolded mutant protein actively promotes tumor growth beyond loss of the normal tumor-suppressor activity.

**Summary chain:** TP53 gene → c.524G>A (CGC→CAC) → p.Arg175His in the predicted protein sequence → impaired DNA binding and transactivation by p53 → failed cell-cycle arrest and apoptosis after DNA damage → early-onset, multiple cancers (Li-Fraumeni syndrome).

### Interpretation questions

**Why does the exact location of a mutation matter?**
The consequence depends on which codon and functional domain the mutation falls in. A change at a structurally critical residue (like Arg175) can cripple function, while a change at a non-critical position may have little effect. Location also determines whether a frameshift or premature stop removes essential downstream domains.

**Why can deleting three nucleotides produce a different result from deleting one or two?**
The genetic code is read in non-overlapping triplets. Deleting a multiple of three removes whole codons and keeps the downstream codons in frame, removing amino acids but leaving the rest correct. Deleting one or two nucleotides shifts the grouping of all subsequent nucleotides, scrambling the downstream sequence (frameshift).

**Does every mutation change the amino-acid sequence?**
No. The genetic code is degenerate, so some substitutions change a codon to another codon for the same amino acid (synonymous or silent mutation), leaving the protein sequence unchanged.

**Does every amino-acid substitution destroy protein function?**
No. If the new amino acid is chemically similar and at a non-critical position, the protein may fold and function normally (a tolerated missense variant). Function is more likely lost at an active site or a structurally critical residue (as with Arg175), or when the side chain is very different.

**Why can a frameshift affect many amino acids even if only one nucleotide was deleted?**
Deleting one nucleotide shifts the reading frame for every downstream codon, so the ribosome reads an entirely new series of codons until a new stop codon is reached, altering potentially hundreds of amino acids.

**Why might a premature stop codon produce a nonfunctional protein?**
Translation is truncated, so the protein lacks some or all downstream functional domains (such as those for DNA binding or oligomerization). The truncated protein may also misfold or be degraded by quality-control systems.

**Could a mutation affect protein function without greatly changing protein length?**
Yes. A missense substitution, as in R175H, keeps the length the same but can destroy function if it disrupts a critical structural or functional residue.

**Could a mutation cause disease without changing the protein sequence?**
Yes. A mutation in a non-coding regulatory region (promoter or splice site), or a synonymous coding change that affects mRNA splicing or stability, could reduce the amount of normal protein, causing disease through insufficient dosage.

**What evidence from your analysis supports the proposed molecular mechanism?**
The needle alignment confirms that R175H changes exactly one residue (position 175) without altering predicted protein length or reading frame, consistent with a missense mechanism. The known structural role of Arg175 in the zinc-stabilized loop region of the DNA-binding domain (Cho et al., 1994) supports the prediction that this substitution disrupts DNA binding rather than removing large portions of the protein.

**Which conclusions are supported directly by the computational results, and which require published experimental evidence?**
Directly supported: the exact nucleotide and amino-acid change, the position of the substitution, and the unchanged predicted protein length and reading frame. Requiring outside experimental evidence: that the substitution disrupts DNA binding in a living cell, that this causes loss of transcriptional activation of p53 target genes, and that this causes the cancer predisposition seen in Li-Fraumeni families. These claims come from published biochemical and clinical studies, not from sequence translation alone.

## 10. Limitations

This lab is computational only. The protein sequences are predicted; expression, folding, localization, and stability were not tested, and no structural modeling was done. The effect of R175H on the DNA-binding domain's structure and on DNA binding, and its link to Li-Fraumeni syndrome, come from published studies (ClinVar, ClinGen, family and functional studies), not from this analysis. The artificial deletion was placed arbitrarily, so it illustrates frameshift principles rather than a disease mechanism.

## 11. Conclusion

The documented TP53 variant c.524G>A (p.Arg175His) changes one amino acid in the DNA-binding domain without changing predicted protein length. Based on the known role of Arg175 in the zinc-stabilized DNA-binding region (Cho et al., 1994), it is predicted to impair DNA binding, consistent with its association with Li-Fraumeni syndrome. The artificial 1-nt deletion shifted the reading frame and produced a 42-amino-acid predicted protein, about 11% of the WT length. Together, the results show that a mutation's type, location, and effect on the reading frame, not the number of nucleotides changed, determine its consequence for the protein.

## 12. References

1. NCBI RefSeq: NM_000546.6, NP_000537.3 (TP53 reference transcript and protein).
2. ClinVar Variation ID 12374 (VCV000012374.13): NM_000546.6(TP53):c.524G>A (p.Arg175His).
3. ClinGen TP53 Variant Curation Expert Panel classification of c.524G>A (p.Arg175His) as Pathogenic for Li-Fraumeni syndrome.
4. Birch JM, Hartley AL, Tricker KJ, et al. Prevalence and diversity of constitutional mutations in the p53 gene among 21 Li-Fraumeni families. *Cancer Res*. 1994;54(5):1298–1304.
5. Kyritsis AP, Bondy ML, Xiao M, et al. Germline p53 gene mutations in subsets of glioma patients. *J Natl Cancer Inst*. 1994;86(5):344–349.
6. Chompret A, Brugières L, Ronsin M, et al. P53 germline mutations in childhood cancers and cancer risk for carrier individuals. *Br J Cancer*. 2000;82(12):1932–1937.
7. Bougeard G, Limacher JM, Martin C, et al. Detection of 11 germline inactivating TP53 mutations and absence of TP63 and HCHK2 mutations in 17 French families with Li-Fraumeni or Li-Fraumeni-like syndrome. *J Med Genet*. 2001;38(4):253–257.
8. Nichols KE, Malkin D, Garber JE, Fraumeni JF Jr, Li FP. Germ-line p53 mutations predispose to a wide spectrum of early-onset cancers. *Cancer Epidemiol Biomarkers Prev*. 2001;10(2):83–87.
9. Cho Y, Gorina S, Jeffrey PD, Pavletich NP. Crystal structure of a p53 tumor suppressor-DNA complex: understanding tumorigenic mutations. *Science*. 1994;265(5170):346–355.
10. Galaxy EMBOSS needle pairwise alignment outputs generated in this laboratory (history: Alama_LiFraumeni_TP53_Mutation_Lab).
report.md…]()
