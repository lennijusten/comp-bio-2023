# comp-bio-2023
Repository for comp bio course 6.878 in Fall 2023 @ MIT

Link: https://lennijusten.github.io/comp-bio-2023/  

## 2023-09-14 | Lecuture 3

### Comparative genomes
The comparison of genomes. Can compare different genomes and look at conserved regions (protein-coding regions, regulatory sequences...)  
Alignment is powerful tool to see evolution: which parts did evolution keep? Can allign genomes. Areas that are shared accross genomes are likely important while stuff where lots of changes occured are regions on the gemnome where mutations are acceptable and don't significantly negatively impact fitness.  

Some regions of the genome will co-vary. Eg in a protein, two different amino acids might interact and if one changes the other one beter change so the two amino-acid coding regions will co-vary. Things in the same protein complex or even metabolic pathway might be co-evolving. 

The goal of alignment is to infer edits (evolutionary operations: insertion, deletion, mutation) between two genomes. Can set scoring functions for aligners to reflect liklihood of the event occuring biolofically. For example, transitions are more common than transversions. For example, penalize the first gap (indel or deltion) but subsequent gaps cost less (since polymerase can skip multiple bases).  

### Dynamic programming
Reordering computation so that the result of the sub-problems are already available in the same computation process. 
