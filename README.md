# Correlation-with-immune-signatures

This code will help you investigate the correlation of specific phenotype (disease, tissue type,....etc) with enrichment of scpecific immune signatures.
You will need to prepare the following:

1. Your datasets containing normalized gene expression values of the samples

2. A class file containing two columns: sample column and class column (explaining the sample class, e.g. cancer or normal tissue, disease or control,....etc)

3.A list of the genes of immune signatures you like to compare their enrichment between the different classess


You will need to perform the following steps to complete the analysis:

a.Calculate the immune scores of each immune signature for each sample (you can calculate mean expression or use GSVA)

b.Compare the immune signatures enrichment between each two classs using Student’s t test
c.Investigate the correlation of the each immune signature with the expression of specific genes
