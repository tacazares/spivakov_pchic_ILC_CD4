# Human Tonsil ILC3 pcHi-C Analysis with RNA-seq

___

## Overview

This repo will walk through the analysis of pcHi-C data generated by Mikhail Spivakov's group for Human Tonsil ILC3. We will also analyze Human Venous Blood CD4+ alpha/beta T-cells as a positive control sample.

This data analysis uses the most recent files generated by Valerya Malysheva. The data includes ABC model interactions in addition to interactions generated by pcHi-C.

 All data were aligned to the hg38 reference genome. For analysis with RELI, data were lifted over to hg19 for compatibility.

The analysis for each data type is describe below:

1. [`ChIP-seq Analysis`](docs/chipseq.md)
2. [`ATAC-seq Analysis`](docs/atacseq.md)
3. [`RNA-seq Analysis`](docs/rnaseq.md)
4. [`pcHi-C Analysis`](docs/pchic.md)
5. [`pcHi-C integrated with RNA-seq`](docs/expression_analysis.md)

## Directory Description

### [`./data`](./data)

The `./data` diretory contains the input and output data produced with this repository. See the [data directry readme](./data/readme.md) for detailed description of files.


### [`./notebooks`](./notebooks)

The notebooks directory contains the jupyter notebooks used to perform the analysis. These notebooks are used interactively to generate the data.

### [`./python`](./python)

The python notebook has all of the python code used to generate the feature files.

### [`./r`](./r)

The `r` directory has the code for performing DESEQ2 analysis and plotting some data.

### [`./docs`](./docs)

The `./docs directory has the markdown files.
