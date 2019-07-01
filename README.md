# awesome-multitrait-gwas

List of software packages for multi-trait GWAS. A
shameless copy of Sean Davis'
[awesome-single-cell](https://github.com/seandavi/awesome-single-cell)
repo and Mike Love's [awesome-multi-omics](https://github.com/mikelove/awesome-multi-omics) repo.

[Contributions welcome](https://github.com/mikelove/awesome-multi-omics/blob/master/CONTRIBUTING.md)...

For brevity, below lists only the first author of multi-trait GWAS methods.

## Software packages and methods

### Background

- [Multivariate Analysis of Variance (MANOVA)](https://en.wikipedia.org/wiki/Multivariate_analysis_of_variance)
- [Canonical Correlation Analysis (CCA)](https://en.wikipedia.org/wiki/Canonical_correlation)

### Large number of univariate tests

- 2012 - MatrixEQTL - Shabalin - [Matrix eQTL: ultra fast eQTL analysis via large matrix operations](https://academic.oup.com/bioinformatics/article/28/10/1353/213326)
- 2016 - HASE - Roshchupkin - [HASE: Framework for efficient high-dimensional association analyses](https://www.nature.com/articles/srep36076)
- 2017 - BGENIE - Bycroft - [Genome-wide genetic data on ~500,000 UK Biobank participants](https://www.biorxiv.org/content/early/2017/07/20/166298)

### Direct methods

- 2007 - MV-SNPTEST - Marchini - [A new multipoint method for genome-wide association studies by imputation of genotypes](https://www.nature.com/articles/ng2088)
- 2012 - MultiPhen - O'Reilly [MultiPhen: Joint Model of Multiple Phenotypes Can Increase Discovery in GWAS](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0034861)
- 2013 - MV-BIMBAM - Stephens - [A Unified Framework for Association Analysis with Multiple Related Phenotypes](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0065245)
- 2014 - mvLMM-GEMMA - Zhou - [Efficient Algorithms for Multivariate Linear Mixed Models in Genome-wide Association Studies](https://www.nature.com/articles/nmeth.2848)

### Indirect methods

- 2007 - PCHAT - Klei - [Pleiotropy and principal components of heritability combine to increase power for association analysis](https://onlinelibrary.wiley.com/doi/abs/10.1002/gepi.20257)
- 2009 - MV-PLINK - Ferreira - [A multivariate test of association](https://academic.oup.com/bioinformatics/article/25/1/132/301513)
- 2014 - Combined PC - Aschard - [Maximizing the Power of Principal-Component Analysis of Correlated Phenotypes in Genome-wide Association Studies](https://www.sciencedirect.com/science/article/pii/S0002929714001189?via%3Dihub)
- 2018 - PCA-based GWAS - Zhang - [PCA-Based Multiple-Trait GWAS Analysis: A Powerful Model for Exploring Pleiotropy](https://www.mdpi.com/2076-2615/8/12/239)

### Meta-analysis methods

- 2010 - METAL - Willer - [METAL: fast and efficient meta-analysis of genomewide association scans](https://academic.oup.com/bioinformatics/article/26/17/2190/198154)
- 2013 - TATES - van der Sluis - [TATES: Efficient Multivariate Genotype-Phenotype Analysis for Genome-Wide Association Studies](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1003235)
- 2015 - S<sub>Hom</sub> / S<sub>Het</sub> - Zhu - [Meta-analysis of Correlated Traits via Summary Statistics from GWASs with an Application in Hypertension](https://www.sciencedirect.com/science/article/pii/S0002929714004777)
- 2015 - MGAS - van der Sluis - [MGAS: a powerful tool for multivariate gene-based genome-wide association analysis](https://academic.oup.com/bioinformatics/article/31/7/1007/181296)
- 2016 - metaCCA - Cichonska - [metaCCA: summary statistics-based multivariate meta-analysis of genome-wide association studies using canonical correlation analysis](https://academic.oup.com/bioinformatics/article/32/13/1981/1742730)
- 2018 - MTAG - Turley - [Multi-trait analysis of genome-wide association summary statistics using MTAG](https://www.nature.com/articles/s41588-017-0009-4)

### Other methods

- 2009 - CMV - Medland - [An integrated phenomic approach to multivariate allelic association](https://www.nature.com/articles/ejhg2009133)

## Case studies

- 2019 - Fatumo - [Complimentary Methods for Multivariate Genome-Wide Association Study Identify New Susceptibility Genes for Blood Cell Traits](https://www.frontiersin.org/articles/10.3389/fgene.2019.00334/full)

## Benchmarks and reviews
- 2010 - Minica - [Genetic Association in Multivariate Phenotypic Data: Power in Five Models](https://www.cambridge.org/core/journals/twin-research-and-human-genetics/article/genetic-association-in-multivariate-phenotypic-data-power-in-five-models/A928605DBAE19EF371828BE6C77C11C0)
- 2014 - Galesloot - [A Comparison of Multivariate Genome-Wide Association Methods](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0095923)
- 2017 - Porter - [Multivariate simulation framework reveals performance of multi-trait GWAS methods](https://www.nature.com/articles/srep38837)
- 2019 - Couvy-Duchesne - [A Fast Method for Estimating Statistical Power of Multivariate GWAS in Real Case Scenarios: Examples from the Field of Imaging Genetics](https://link.springer.com/article/10.1007%2Fs10519-018-9936-9)
