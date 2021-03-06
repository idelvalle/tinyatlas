# tinyatlas
tinyatlas is a tiny cell atlas in an easily digestable format, useful for
marking known cell types in commonly sequenced organisms when looking at
single-cell RNA-seq data.

# rationale
We've concluded from looking at many single-cell experiments that markers for
cell types are not always useful for classifying cell types from single-cell RNA
sequencing data. Sometimes markers will not be as specific to a specific cell
type as thought or are not expressed at a high enough level to be picked up
reliably by single-cell RNA sequencing. Markers that work well for FACS sorting
may not be useful when looking at the RNA expression. This repository is a
compilation of what we think are good markers for the cell types we've
encountered, across a variety of organisms.

# contribution
If you have data of your own to contribute of any kind, please do.

# origin
These lists were originally compiled by Mike Steinbaugh here (https://docs.google.com/spreadsheets/d/1vGNU2CCxpaoTCLvzOxK1hf5gjULrf2-CpgCp9bOfGJ0)
and (https://docs.google.com/spreadsheets/d/1qA5ktYeimNGpZF1UPSQZATbpzEqgyxN6daoMOjv6YYw). We moved them here to give better access to the community so we can work together on improving them. Moving to git also lets us address specific versions by git hashes, so we can be sure which versions of the markers we have used.

# Changes

2018-10-19: Zebrafish Cell cycle and cell type genes added using homology information against Homo sapiens. 
Script found at `code` folder. It uses biomaRt and only one2one orthology type and high orthology confidence.
<<<<<<< HEAD
=======

2019-04-19: Found typo in code for `gene2Drerio.Rmd` that was saving the wrong object. Corrected and uploaded the correct file.
>>>>>>> 3d6a07d... Update README.md
