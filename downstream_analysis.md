# Downstream analysis

## Tools to install

For the downstream analysis of RNASeq pipeline, the most frequent
types of analyses the biologists will ask are:
1. GO annotation/enrichment analysis;
2. Gene Set Enrichment Analysis;
3. Pathway analysis.

For the **GO annotation/enrichment analysis**, there are two Galaxy tools
associate with it:

- go_enrichment
https://toolshed.g2.bx.psu.edu/repository?repository_id=c56a361234052bf9&changeset_revision=007baf9662c6

- blast2GO
https://toolshed.g2.bx.psu.edu/repository/view_repository?id=e4de88c47079d971

Go annotation with R Bioconductor packages
- http://www.bioconductor.org/packages/2.8/BiocViews.html#___GO
- http://www.bioconductor.org/packages/2.8/bioc/vignettes/goseq/inst/doc/goseq.pdf


For the **GSEA and Pathway analysis**, there is no good tools
implemented in Galaxy. We could use GSEA package developed at the
Broad Institute and a commercial package MetaCore for Pathway analysis which we have a license.

- GSEA for Gene Set Enrichment Analysis http://software.broadinstitute.org/gsea/index.jsp
- MetaCore for pathway analysis http://thomsonreuters.com/en/products-services/pharma-life-sciences/pharmaceutical-research/metacore.html
- gProfiler http://biit.cs.ut.ee/gprofiler/
