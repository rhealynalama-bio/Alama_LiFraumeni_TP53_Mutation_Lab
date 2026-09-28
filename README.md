[README.md](https://github.com/user-attachments/files/32733962/README.md)
# From Gene Mutation to Disease: TP53 and Li-Fraumeni Syndrome

## Project Information

| Item | Details |
|---|---|
| **Name** | Alama, Rhealyn F. |
| **Section** | B |
| **Subject** | Cell & Molecular Biology |
| **Instructors** | Abner A. Bucol & Mrs. Lilibeth A. Bucol |
| **Disease** | Li-Fraumeni syndrome |
| **Gene** | TP53 (chromosome 17p13.1) |
| **Reference transcript / CDS** | NM_000546.6 (CDS region 143–1324, 1,182 nt) |
| **Reference protein** | NP_000537.3 (393 aa) |
| **Documented variant** | NM_000546.6(TP53):c.524G>A (p.Arg175His, R175H), missense |
| **ClinVar accession** | VCV000012374.13 (Variation ID 12374) |
| **Galaxy history** | Alama_LiFraumeni_TP53_Mutation_Lab |
| **Date of analysis** | September 16–18, 2026 |

## Summary

The wild-type (WT) TP53 CDS was translated in Galaxy to give a predicted protein sequence identical to NP_000537.3. Two edited copies of the CDS were then translated and aligned to the WT with EMBOSS needle (gap open 10.0, gap extend 0.5):

| Sequence | CDS length | Predicted protein length | Mutation type | Frame changed | Premature stop | needle identity |
|---|---|---|---|---|---|---|
| WT | 1,182 nt | 393 aa | n/a | n/a | n/a | n/a |
| R175H (c.524G>A) | 1,182 nt | 393 aa | Missense | No | No | 392/393 (99.7%) |
| Artificial 1-nt deletion (position 100, codon 34) | 1,181 nt | 42 aa | Frameshift | Yes | Yes | 37/394 (9.4%) |

R175H changes one amino acid in the DNA-binding domain without changing predicted protein length. The artificial deletion shifts the reading frame and produces a truncated predicted protein. All protein sequences here are predicted from translation; expression and function were not tested.


## Workflow

1. Retrieved the WT TP53 CDS (NM_000546.6, nt 143–1324) from NCBI RefSeq.
2. Uploaded it to a new Galaxy history and translated it; checked the result against NP_000537.3.
3. Copied the WT CDS and manually introduced c.524G>A (codon 175, CGC→CAC) to make the R175H CDS, then translated it.
4. Copied the WT CDS again and deleted one nucleotide at position 100 (within codon 34) as the artificial mutation, then translated it.
5. Aligned each mutant predicted protein sequence to the WT with EMBOSS needle.
6. Wrote the interpretation and final report.

The original WT files were never modified; every edit was made on a copy.

## References

- NCBI RefSeq: NM_000546.6, NP_000537.3
- ClinVar VCV000012374.13: NM_000546.6(TP53):c.524G>A (p.Arg175His)
- Cho Y, et al. Crystal structure of a p53 tumor suppressor-DNA complex. *Science*. 1994;265(5170):346–355.
