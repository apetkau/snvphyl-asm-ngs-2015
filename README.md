ASM NGS Challenge 2015: SNVPhyl Results
=======================================

This contains the results for the [ASM NGS Challenge 2015](https://github.com/katholt/NGSchallenge) for our [SNVPhyl](http://snvphyl.readthedocs.org/) whole genome phylogeny pipeline.  The following are important files to look at:

* [IRIDASNVPhylASM_NGS_2015.pdf](IRIDASNVPhylASM_NGS_2015.pdf): The presentation given at the ASM NGS conference.
* [results.xlsx](results.xlsx): The answers to each question and spreadsheet defining matches/non-matches.
* [README.docx](README.docx):  A description of the methods and further description of some of the supplementary files.

The below summerizes the answers to each question.

Listeria monocytogenes
----------------------

### Tree

[![lm-phylo][]][lm-phylo]

Generated using **232** variant sites from **87% (2.6 Mbp/3.0 Mbp)** of the reference genome.  See [Listeria monocytogenes][] supplemental information for details.

### Questions

1. Do the product isolates from facility #1 match the environmental swabs from facility #1? **Yes**.  The manufacturer claims that since the positive swabs did not come from food contact surfaces the contamination must come from another source. Do the product isolates match any other food/environmental isolates currently in the NCBI/SRA database under BioProjects PRJNA212117 or PRJNA215355? **Unlikely**.

2. Do the environmental/product isolates from either facility match clinical isolates in the BioProjects listed in question 1, or any other clinical Listeria monocytogenes isolates available from other public data sources?  Can you identify the clinical cases associated with this contamination event?  **Yes, 4 isolates match facility 1 (SAMN02400164 + SRR1027093, SAMN02582713 + SRR1112204, SAMN02689015 + SRR1193825, SAMN02582710 + SRR1112195)**.

   [![lm-additional][]][lm-additional]

   Generated using **361** sites from **84% (2.5 Mbp/3.0 Mbp)** of the reference genome.  See [Listeria monocytogenes other sources][] for more information.

Detailed responses can be found in [results.xlsx][].

Salmonella Enteritidis
----------------------

## Tree

[![se-phylo][]][se-phylo]

Generated using **237** variant sites from **72% (3.4 Mbp/4.7 Mbp)** of the reference genome.  See [Salmonella Enteritidis][] supplemental information for details.

### Questions

1. Do the 4 clinical isolates (ASM_26, ASM_31, ASM_49, and ASM_50) that are epidemiologically linked to eggs from state #2 match any of the environmental or food swabs collected at those facilities? **Yes.  Three of the 4 clinical cases (ASM_49 + SRR2352233, ASM_50 + SRR2352234, ASM_26 + SRR2352210) are a match to isolates from state 2.  One of the 4 cases (ASM_31 + SRR2352215) is an uncertain match to isolates from state 2.**

2. Do any of the remaining 19 clinical isolates match clinical isolates from question #1? **Yes, 14 of the 19 clinical isolates**. Do they match any of the food or environmental isolates? **Yes, 8 clinical isolates match food or environmental**.  Are there additional clinical clusters?  **Possible (ASM_41 + SRR2352225, ASM_42 + SRR2352226), (ASM_44 + SRR2352228, ASM_45 + SRR2352229).  Possible but less likely (ASM_41 + SRR2352225, ASM_44 + SRR2352228), (ASM_41 + SRR2352225, ASM_45 + SRR2352229).**

3. Are there other clinical Salmonella isolates in public databases (including, but not limited to, samples from BioProjects PRJNA237212, PRJNA227458, PRJNA252015, and PRJNA230403) that match food or environmental isolates collected at these facilities in these two states? **Did not have the chance to complete.**

Detailed responses can be found in [results.xlsx][].

[results.xlsx]: results.xlsx
[Listeria monocytogenes]: Listeria_supplemental/results/LM_ASM-68_Cov10_RM_PHAST/
[Salmonella Enteritidis]: Salmonella_supplemental/results/SE_ASM-31_Cov10_RM_ASM-20_RM_PHAST/
[lm-phylo]: images/lm-phylo.png
[se-phylo]: images/se-phylo.png
[lm-additional]: images/lm-additional.png
[Listeria monocytogenes other sources]: Listeria_supplemental/results/LM_ASM-68_Cov10_RM_PHAST_NCBI_Datasets/
