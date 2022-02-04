# COVID19-Substitution-Upset-Plot
R script for creating an upset plot to visualize and determine nucleotide substitutions grouping in COVID-19 genotypes

1.  Substitutions for each genotype were obtained using Nextclade output formatted using https://github.com/genizamt/GISAID-Nextstrain-DBmaker
2.  Filter for substitutions that define a genotype in GISAID - substitution must appear in at least 75% of all submitted sequences reported as a specific genotype.

Primary purpose of upset plot is to generate matrix to use in determining substitutions that may be used to identify specific genotypes when using variant calling pipelines. Files for Delta (B.1.617.2 and AY-subfamily) and Omicron (B.1.1.529 and BA-subfamily) are supplied as examples
