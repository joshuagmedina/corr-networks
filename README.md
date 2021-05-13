# Correlation Analysis

Files within this repository are a result of a study that aimed to understand the genetic profile of 1 and 3 day regenerative intestine of the sea cucumber.

The files descriptions are as follow:

* expr_table_final.gct - count table of different tissues assessed normal (non-regenerative tissue), 1 day regeneration, and 3 day regeneration. We have 3 biological replicates from each tissue type.
* fc_table.gct - fold change differential expression results of 1 and 3 day regeneration compared to normal tissue, respectively.
* coregulatoy-table-tf.txt - results from CoReg analysis using specific transcription factors. Access the package page [here](https://www.bioconductor.org/packages/release/bioc/html/CoRegNet.html). To generate this we utilized the fold change table above.
* eData.txt - similar to the expr_table_final.gct file but without the Description column.

I am currently running the script fastgcn.R acquired from (https://github.com/DrLiang/FastGCN) to be able to generate gene-gene correlation results.

In the meantime hopefully we can get some sort of interesting results from the transcription factor coregulatory analysis.
