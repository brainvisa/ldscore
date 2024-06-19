
# LDSC (LD SCore) `v2.0.1`

`ldsc` is a command line tool for estimating heritability and genetic correlation from GWAS summary statistics. `ldsc` also computes LD Scores.

## History
This repository is a (manual copy) fork of a (github) for of the repos https://github.com/bulik/ldsc.
See here the list of fork of the original https://github.com/bulik/ldsc/forks.

The originating fork of this repository fixed major issues regarding Python2 Python3 port as well as some pandas oldies. Unfortunately the originating fork is unknown.

This repos was reorganized to fit the standards of Python package generation and advanced standard to be handle by package generators like rattler. The main consequences are the apparition of the Pyproject.toml and the move of scripts file into the ldscore directory.


## Where Can I Get LD Scores?

You can download [European](https://data.broadinstitute.org/alkesgroup/LDSCORE/eur_w_ld_chr.tar.bz2) and [East Asian LD Scores](https://data.broadinstitute.org/alkesgroup/LDSCORE/eas_ldscores.tar.bz2) from 1000 Genomes [here](https://data.broadinstitute.org/alkesgroup/LDSCORE/). These LD Scores are suitable for basic LD Score analyses (the LD Score regression intercept, heritability, genetic correlation, cross-sex genetic correlation). You can download partitioned LD Scores for partitioned heritability estimation [here](http://data.broadinstitute.org/alkesgroup/LDSCORE/).


## Support

Before contacting us, please try the following:

 1. The [wiki](https://github.com/bulik/ldsc/wiki) has tutorials on [estimating LD Score](https://github.com/bulik/ldsc/wiki/LD-Score-Estimation-Tutorial), [heritability, genetic correlation and the LD Score regression intercept](https://github.com/bulik/ldsc/wiki/Heritability-and-Genetic-Correlation) and [partitioned heritability](https://github.com/bulik/ldsc/wiki/Partitioned-Heritability).
 2. Common issues are described in the [FAQ](https://github.com/bulik/ldsc/wiki/FAQ)
 2. The methods are described in the papers (citations below)

If that doesn't work, you can get in touch with us via the [google group](https://groups.google.com/forum/?hl=en#!forum/ldsc_users).

Issues with LD Hub?  Email ld-hub@bristol.ac.uk


## Citation

If you use the software or the LD Score regression intercept, please cite

 - [Bulik-Sullivan, et al. LD Score Regression Distinguishes Confounding from Polygenicity in Genome-Wide Association Studies.
Nature Genetics, 2015.](http://www.nature.com/ng/journal/vaop/ncurrent/full/ng.3211.html)

For genetic correlation, please also cite

 - [Bulik-Sullivan, B., et al. An Atlas of Genetic Correlations across Human Diseases and Traits. Nature Genetics, 2015.](https://www.nature.com/articles/ng.3406) Preprint available on bioRxiv doi: http://dx.doi.org/10.1101/014498

For partitioned heritability, please also cite

 - [Finucane, HK, et al. Partitioning heritability by functional annotation using genome-wide association summary statistics. Nature Genetics, 2015.](https://www.nature.com/articles/ng.3404) Preprint available on bioRxiv doi: http://dx.doi.org/10.1101/014241

For stratified heritability using continuous annotation, please also cite

 - [Gazal, S, et al. Linkage disequilibrium–dependent architecture of human complex traits shows action of negative selection. Nature Genetics, 2017.](https://www.nature.com/articles/ng.3954) 

If you find the fact that LD Score regression approximates HE regression to be conceptually useful, please cite

Bulik-Sullivan, Brendan. Relationship between LD Score and Haseman-Elston, bioRxiv doi: http://dx.doi.org/10.1101/018283

For LD Hub, please cite

 - [Zheng, et al. LD Hub: a centralized database and web interface to perform LD score regression that maximizes the potential of summary level GWAS data for SNP heritability and genetic correlation analysis. Bioinformatics (2016)](https://doi.org/10.1093/bioinformatics/btw613)


## License

This project is licensed under GNU GPL v3.


## Authors

Brendan Bulik-Sullivan (Broad Institute of MIT and Harvard)

Hilary Finucane (MIT Department of Mathematics)
