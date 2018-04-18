# Datasets

The data consists of a number of tissue samples corresponding to four distinct types of small round blue cell tumors. For each tissue sample, 2308 gene expression measurements are available.

`xtrain.csv` --- contains 2308 gene expressions for 63 subjects

`ytrain.csv` --- contains corresponding tumor type for the 63 subjects in `xtrain.csv`

`xtest.csv` --- contains 2308 gene expressions for 20 more subjects

`ytest.csv` --- contains corresponding tumor type for the 20 subjects in `xtest.csv`

# Source

This data were originally reported in:

Khan J, Wei J, Ringner M, Saal L, Ladanyi M, Westermann F, Berthold F, Schwab M, Antonescu C, Peterson C, and Meltzer P. Classification and diagnostic prediction of cancers using gene expression profiling and artificial neural networks. Nature Medicine, v.7, pp.673-679, 2001.

Exported from the `Khan` object in `ILSR` package in R.