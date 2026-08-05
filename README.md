# Phylogenetic Analysis of Order Chiroptera Using COI Gene

**Course:** BIO 300 — Cell & Molecular Biology Laboratory
**Group:** 4
**Members:** Batigulao, Jehiah; Obiñeta, Inah Marie; Oficiar, Francis Kyle; Pasculado, Mark; Suan, Jade Angela
**Date:** August 2026
**Instructor:** Dr. Lilibeth A. Bucol

## Project Overview
Mitochondrial COI gene sequences from selected bat species were retrieved from NCBI, aligned using MAFFT in Galaxy, and used to construct a phylogenetic tree via FastTree. *Mus musculus* was included as the outgroup to root the tree.

## Taxonomic Coverage
- **Order:** Chiroptera (6 focal species)
- **Outgroup:** *Mus musculus* (House mouse, Order Rodentia)

## Species & Accession Numbers
| Scientific Name | Common Name | Accession No. | Length |
|---|---|---|---|
| *Mus musculus* | House mouse | AB444046.1 | 702 bp |
| *Hipposideros diadema* | Diadem leaf-nosed bat | HM914927.1 | 658 bp |
| *Rhinolophus arcuatus* | Arcuate horseshoe bat | MH014038.1 | 658 bp |
| *Pteropus vampyrus* | Large flying fox | MK415810.1 | 627 bp |
| *Rousettus amplexicaudatus* | Geoffroy's rousette | MK585723.1 | 658 bp |
| *Miniopterus schreibersii* | Common bent-wing bat | MT407283.1 | 658 bp |
| *Cynopterus brachyotis* | Lesser short-nosed fruit bat | MK585802.1 | 616 bp |

## Workflow
1. Retrieve COI sequences from NCBI → save as FASTA
2. Upload sequences to Galaxy
3. Multiple sequence alignment using **MAFFT**
4. Generate consensus sequence
5. Build phylogenetic tree using **FastTree**
6. Compare tree topology with published studies

## Repository Structure
- `sequences/` — Raw FASTA & consensus sequences
- `alignment/` — MAFFT alignment file
- `tree/` — Newick tree file & image
- `accession_table.md` — Full metadata table
- `literature_comparison.md` — Comparison with published work
- `final_report.md` — Complete report + references

