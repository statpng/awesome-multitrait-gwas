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
- 2015 - PLINK2 - Chang - [Second-generation PLINK: rising to the challenge of larger and richer datasets](https://academic.oup.com/gigascience/article/4/1/s13742-015-0047-8/2707533)
- 2016 - HASE - Roshchupkin - [HASE: Framework for efficient high-dimensional association analyses](https://www.nature.com/articles/srep36076)
- 2017 - BGENIE - Bycroft - [The UK Biobank resource with deep phenotyping and genomic data](https://www.nature.com/articles/s41586-018-0579-z)

### Direct tests

- 2007 - MV-SNPTEST - Marchini - [A new multipoint method for genome-wide association studies by imputation of genotypes](https://www.nature.com/articles/ng2088)
- 2012 - MultiPhen - O'Reilly [MultiPhen: Joint Model of Multiple Phenotypes Can Increase Discovery in GWAS](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0034861)
- 2012 - MTMM - Korte - [A mixed-model approach for genome-wide association studies of correlated traits in structured populations](https://www.nature.com/articles/ng.2376)
- 2013 - BSLMM - Zhou - [Polygenic Modeling with Bayesian Sparse Linear Mixed Models](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1003264)
- 2013 - MV-BIMBAM - Stephens - [A Unified Framework for Association Analysis with Multiple Related Phenotypes](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0065245)
- 2014 - mvLMM-GEMMA - Zhou - [Efficient Algorithms for Multivariate Linear Mixed Models in Genome-wide Association Studies](https://www.nature.com/articles/nmeth.2848)
- 2015 - Ray - USAT - [USAT: A Unified Score‐Based Association Test for Multiple Phenotype‐Genotype Analysis](https://onlinelibrary.wiley.com/doi/full/10.1002/gepi.21937)
- 2018 - SBAT - Elliot - [Genome-wide association studies of brain imaging phenotypes in UK Biobank](https://www.nature.com/articles/s41586-018-0571-7)

### Indirect tests

- 2007 - PCHAT - Klei - [Pleiotropy and principal components of heritability combine to increase power for association analysis](https://onlinelibrary.wiley.com/doi/abs/10.1002/gepi.20257)
- 2009 - MV-PLINK - Ferreira - [A multivariate test of association](https://academic.oup.com/bioinformatics/article/25/1/132/301513)
- 2014 - Combined PC - Aschard - [Maximizing the Power of Principal-Component Analysis of Correlated Phenotypes in Genome-wide Association Studies](https://www.sciencedirect.com/science/article/pii/S0002929714001189?via%3Dihub)
- 2018 - PCA-based GWAS - Zhang - [PCA-Based Multiple-Trait GWAS Analysis: A Powerful Model for Exploring Pleiotropy](https://www.mdpi.com/2076-2615/8/12/239)

### Meta-analysis tests

- 2011 - PRIMe - Huang - [PRIMe: a method for characterization and evaluation of pleiotropic regions from multiple genome-wide association studies](https://academic.oup.com/bioinformatics/article/27/9/1201/242517)
- 2012 - Extended O'Briens methods - Yang - [Analyze multivariate phenotypes in genetic association studies by combining univariate association tests](https://onlinelibrary.wiley.com/doi/abs/10.1002/gepi.20497)
- 2010 - METAL - Willer - [METAL: fast and efficient meta-analysis of genomewide association scans](https://academic.oup.com/bioinformatics/article/26/17/2190/198154)
- 2013 - TATES - van der Sluis - [TATES: Efficient Multivariate Genotype-Phenotype Analysis for Genome-Wide Association Studies](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1003235)
-  2014 - Chi-squared based - Bolormaa - [A Multi-Trait, Meta-analysis for Detecting Pleiotropic Polymorphisms for Stature, Fatness and Reproduction in Beef Cattle](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1004198)
- 2015 - S<sub>Hom</sub> / S<sub>Het</sub> - Zhu - [Meta-analysis of Correlated Traits via Summary Statistics from GWASs with an Application in Hypertension](https://www.sciencedirect.com/science/article/pii/S0002929714004777)
- 2015 - MGAS - van der Sluis - [MGAS: a powerful tool for multivariate gene-based genome-wide association analysis](https://academic.oup.com/bioinformatics/article/31/7/1007/181296)
- 2016 - metaCCA - Cichonska - [metaCCA: summary statistics-based multivariate meta-analysis of genome-wide association studies using canonical correlation analysis](https://academic.oup.com/bioinformatics/article/32/13/1981/1742730)
- 2018 - MTAG - Turley - [Multi-trait analysis of genome-wide association summary statistics using MTAG](https://www.nature.com/articles/s41588-017-0009-4)
- 2019 - metaPhat - Lin - [MetaPhat: Detecting and decomposing multivariate associations from univariate genomewide association statistics](https://www.biorxiv.org/content/10.1101/661421v1)
- 2019 - meta-MultiSKAT - Dutta - [Meta‐MultiSKAT: Multiple phenotype meta‐analysis for region‐based association test](https://onlinelibrary.wiley.com/doi/full/10.1002/gepi.22248)
- 2019 - MTAR - Guo - [Integrate multiple traits to detect novel trait–gene association using GWAS summary data with an adaptive test approach](https://academic.oup.com/bioinformatics/article/35/13/2251/5201342)
- 2019 - aMAT - Wu - [Multi-trait genome-wide analyses of the brain imaging phenotypes in UK Biobank](https://www.biorxiv.org/content/10.1101/758326v1)

### Other tests

- 2009 - CMV - Medland - [An integrated phenomic approach to multivariate allelic association](https://www.nature.com/articles/ejhg2009133)
- 2012 - PSEA - Ried - [PSEA: Phenotype Set Enrichment Analysis—A New Method for Analysis of Multiple Phenotypes](https://onlinelibrary.wiley.com/doi/full/10.1002/gepi.21617)

### Genetic correlation

- 2012 - GEMMA Variance Components - Zhou - [Genome-wide efficient mixed-model analysis for association studies](https://www.nature.com/articles/ng.2310)
- 2015 - LD score regression - Bulik-Sullivan - [An atlas of genetic correlations across human diseases and traits](https://www.nature.com/articles/ng.3406)
- 2015 - BOLT-REML - Loh - [Contrasting genetic architectures of schizophrenia and other complex diseases using fast variance-components analysis](https://www.nature.com/articles/ng.3431)

### Polygenicity

- 2019 - MiXer - Frei - [Bivariate causal mixture model quantifies polygenic overlap between complex traits beyond genetic correlation](https://www.nature.com/articles/s41467-019-10310-0)
- 2019 - Gaussian Mixture model - Frei - [Bivariate causal mixture model quantifies polygenic overlap between complex traits beyond genetic correlation](https://www.biorxiv.org/content/10.1101/133132v7)

### Imputation

- 2016 - PHENIX - Dahl - [A multiple-phenotype imputation method for genetic studies](https://www.nature.com/articles/ng.3513)

### Finemapping and colocalization

- 2014 - coloc - Giambartolomei - [Bayesian Test for Colocalisation between Pairs of Genetic Association Studies Using Summary Statistics](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1004383)
- 2014 - GPA - Chung - [GPA: A Statistical Approach to Prioritizing GWAS Results by Integrating Pleiotropy and Annotation](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1004787)
- 2017 - fastPAINTOR - Kichaev - [Improved methods for multi-trait fine mapping of pleiotropic risk loci](https://academic.oup.com/bioinformatics/article/33/2/248/2525720)

### Rare variants

- 2016 - GAMuT - Broadawy - [A Statistical Approach for Testing Cross-Phenotype Effects of Rare Variants](https://www.cell.com/ajhg/fulltext/S0002-9297(16)00052-5)
- 2017 - DKAT - Zhan - [Powerful Genetic Association Analysis for Common or Rare Variants with High-Dimensional Structured Traits](https://www.genetics.org/content/206/4/1779.long)
- 2018 - Multi-SKAT - Dutta - [Multi‐SKAT: General framework to test for rare‐variant association with multiple phenotypes](https://onlinelibrary.wiley.com/doi/10.1002/gepi.22156)

## Case studies

- 2012 - Inouye - [Novel Loci for Metabolic Networks and Multi-Tissue Expression Studies Reveal Genes for Atherosclerosis](https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1002907#s4)
- 2016 - Roshchupkin - [Heritability of the shape of subcortical brain structures in the general population](https://www.nature.com/articles/ncomms13738)
- 2018 - Elliot - [Genome-wide association studies of brain imaging phenotypes in UK Biobank](https://www.nature.com/articles/s41586-018-0571-7#Sec8)
- 2018 - Claes - [Genome-wide mapping of global-to-local genetic effects on human facial shape](https://www.nature.com/articles/s41588-018-0057-4#Sec13)
- 2019 - Fatumo - [Complimentary Methods for Multivariate Genome-Wide Association Study Identify New Susceptibility Genes for Blood Cell Traits](https://www.frontiersin.org/articles/10.3389/fgene.2019.00334/full)
- 2019 - Watanabe - [A global overview of pleiotropy and genetic architecture in complex traits](https://www.nature.com/articles/s41588-019-0481-0#Sec18)

## Benchmarks and reviews
- 2010 - Minica - [Genetic Association in Multivariate Phenotypic Data: Power in Five Models](https://www.cambridge.org/core/journals/twin-research-and-human-genetics/article/genetic-association-in-multivariate-phenotypic-data-power-in-five-models/A928605DBAE19EF371828BE6C77C11C0)
- 2012 - Shriner - [Moving toward system genetics through multiple trait analysis in genome-wide association studies](https://www.frontiersin.org/articles/10.3389/fgene.2012.00001/full)
- 2013 - Solovieff - [Pleiotropy in complex traits: challenges and strategies](https://www.nature.com/articles/nrg3461)
- 2014 - Galesloot - [A Comparison of Multivariate Genome-Wide Association Methods](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0095923)
- 2017 - Hackinger - [Statistical methods to detect pleiotropy in human complex traits](https://royalsocietypublishing.org/doi/full/10.1098/rsob.170125?url_ver=Z39.88-2003&rfr_id=ori%3Arid%3Acrossref.org&rfr_dat=cr_pub%3Dpubmed&)
- 2017 - Porter - [Multivariate simulation framework reveals performance of multi-trait GWAS methods](https://www.nature.com/articles/srep38837)
- 2019 - Couvy-Duchesne - [A Fast Method for Estimating Statistical Power of Multivariate GWAS in Real Case Scenarios: Examples from the Field of Imaging Genetics](https://link.springer.com/article/10.1007%2Fs10519-018-9936-9)
- 2019 - van Rheenen - [Genetic correlations of polygenic disease traits: from theory to practice](https://www.nature.com/articles/s41576-019-0137-z)
- 2019 - Ray - [Effect of non-normality and low count variants on cross-phenotype association tests in GWAS](https://www.nature.com/articles/s41431-019-0514-2)

## Unsorted
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6477978/
https://www.biorxiv.org/content/10.1101/758326v2.full.pdf
https://www.nature.com/articles/s41467-018-05444-6
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4738479/
https://www.ncbi.nlm.nih.gov/pubmed/30239606
