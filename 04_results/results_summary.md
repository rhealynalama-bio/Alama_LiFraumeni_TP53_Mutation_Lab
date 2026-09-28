# Results Summary: TP53 (Li-Fraumeni Syndrome)

**Galaxy history:** Alama_LiFraumeni_TP53_Mutation_Lab
**Reference:** NM_000546.6 (CDS 143–1324), NP_000537.3
**Documented variant:** c.524G>A (p.Arg175His), ClinVar VCV000012374.13

## Key Results

| | WT | R175H (documented) | Artificial (1-nt deletion) |
|---|---|---|---|
| **Edit** | none | G>A at nt 524 (CGC→CAC) | C deleted at nt 100 (codon 34) |
| **CDS length** | 1,182 nt | 1,182 nt | 1,181 nt |
| **Predicted protein length** | 393 aa | 393 aa | 42 aa |
| **Mutation type** | n/a | Missense | Frameshift |
| **Reading frame changed** | n/a | No | Yes |
| **Premature stop codon** | n/a | No | Yes (after aa 42) |
| **First difference from WT** | n/a | Position 175 (Arg→His) | Position 35 |
| **needle identity vs WT** | n/a | 392/393 (99.7%) | 37/394 (9.4%) |

## Findings

- The predicted WT protein sequence (393 aa) is identical to reference NP_000537.3, so the CDS and translation are valid.
- R175H changes exactly one amino acid with no change in length or reading frame. Its effect on function is predicted from the known structural role of Arg175 in the zinc-stabilized DNA-binding region (Cho et al., 1994), not shown by this analysis.
- The 1-nt deletion shifted the reading frame after codon 34 and produced a 42-aa predicted protein (about 11% of WT length).
- Both edits changed one nucleotide, but only the deletion changed the reading frame. Mutation type, location, and reading-frame effect determine severity, not the number of nucleotides changed.

## Caution

All protein sequences are predicted from translation. Expression, folding, and DNA-binding activity were not tested, and the link to Li-Fraumeni syndrome comes from published studies.

## Data Files

| Folder | Files |
|---|---|
| `01_reference/` | `TP53_WT_CDS.fasta`, `TP53_WT_protein.fasta` |
| `02_documented_mutation/` | `TP53_R175H_CDS.fasta`, `TP53_R175H_protein.fasta` |
| `03_artificial_mutation/` | `TP53_artificial_1ntdel_CDS.fasta`, `TP53_artificial_1ntdel_protein.fasta` |
| `04_results/` | `WT_vs_mutant_alignment.txt`, `WT_vs_artificial_alignment.txt` |
| `05_report/` | `final_report.md` |
