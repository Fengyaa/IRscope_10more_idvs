# IRscope_10more_idvs
Modified R script from IRscope to plot more than 10 individuals in one plot.

### Example usage in R studio:
```R
source("IR_functions.R")
gb_files = c('1.gb','2.gb','3.gb',
  '4.gb','5.gb','6.gb','7.gb','8.gb','9.gb','10.gb','11.gb','12.gb')
IRs(gb_files)
IRs2(gb_files)
```

If use please cite:
  Ali Amiryousefi and others, IRscope: an online program to visualize the junction sites of chloroplast genomes, Bioinformatics, Volume 34, Issue 17, September 2018, Pages 3030–3031, https://doi.org/10.1093/bioinformatics/bty220
