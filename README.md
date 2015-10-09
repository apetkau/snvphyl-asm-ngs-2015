ASM NGS Challenge 2015: SNVPhyl Results
=======================================

This contains the results for the [ASM NGS Challenge 2015](https://github.com/katholt/NGSchallenge) for our [SNVPhyl](http://snvphyl.readthedocs.org/) whole genome phylogeny pipeline.

Listeria monocytogenes
----------------------

# Tree

[![lm-phylo][]][lm-phylo]

Generated using **232** variant sites from 87% (2.6 Mbp/3.0 Mbp) of the reference genome.  See [Listeria monocytogenes][] supplemental information for details.

# Questions

1. Do the product isolates from facility #1 match the environmental swabs from facility #1? **Yes**.  The manufacturer claims that since the positive swabs did not come from food contact surfaces the contamination must come from another source. Do the product isolates match any other food/environmental isolates currently in the NCBI/SRA database under BioProjects PRJNA212117 or PRJNA215355? **Unlikely**.

2. Do the environmental/product isolates from either facility match clinical isolates in the BioProjects listed in question 1, or any other clinical Listeria monocytogenes isolates available from other public data sources?  Can you identify the clinical cases associated with this contamination event?  **Yes, 4 isolates match facility 1 (SAMN02400164 + SRR1027093, SAMN02582713 + SRR1112204, SAMN02689015 + SRR1193825, SAMN02582710 + SRR1112195)**.

Detailed responses can be found in [results.xlsx][].

Salmonella Enteritidis
----------------------

[![se-phylo][]][se-phylo]

Generated using **237** variant sites from 72% (3.4 Mbp/4.7 Mbp) of the reference genome.  See [Salmonella Enteritidis][] supplemental information for details.

The files are as follows:

* [IRIDASNVPhylASM_NGS_2015.pdf](IRIDASNVPhylASM_NGS_2015.pdf): The presentation given at the ASM NGS conference.
* [results.xlsx](results.xlsx): The answers to each question and spreadsheet defining matches/non-matches.
* [README.docx](README.docx):  A description of the methods and further description of some of the supplementary files.

[results.xlsx]: results.xlsx
[Listeria monocytogenes]: Listeria_supplemental/results/LM_ASM-68_Cov10_RM_PHAST/
[Salmonella Enteritidis]: Salmonella_supplemental/results/SE_ASM-31_Cov10_RM_ASM-20_RM_PHAST/
[lm-phylo]: images/lm-phylo.png
[se-phylo]: images/se-phylo.png
