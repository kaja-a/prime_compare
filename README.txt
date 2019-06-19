################################################################################
1) unwpp_mortality = FALSE, disability.weights = "gbd_2001", canc.inc = "2012"
2) unwpp_mortality = TRUE,  disability.weights = "gbd_2001", canc.inc = "2012"
3) unwpp_mortality = FALSE, disability.weights = "gbd_2016", canc.inc = "2012"
4) unwpp_mortality = FALSE, disability.weights = "gbd_2001", canc.inc = "2018"
5) unwpp_mortality = TRUE,  disability.weights = "gbd_2016", canc.inc = "2018"
################################################################################

This folder contains files for PRIME comparison of the following scenarios:

# 1. Base: lifetable (who), disability weight (gbd_2001), globocan (2012)

1..._lifetab-who_dw-gbd2001-who_globocan-2012

# 2. <<lifetable (unwpp)>>, disability weight (gbd_2001), globocan (2012)
2..._lifetab-unwpp_dw-gbd2001_globocan-2012


# 3. lifetable (who), <<disability weight (gbd_2016)>>, globocan (2012)

3..._lifetab-who_dw-gbd2016_globocan-2012

# 4. lifetable (who), disability weight (gbd_2001), <<globocan (2018)>>

4..._lifetab-who_dw-gbd2001_globocan-2018

# 5. <<lifetable (unwpp)>>, <<disability weight (gbd_2016)>>, <<globocan (2018)>>
5..._lifetab-unwpp_dw-gbd2001_globocan-2018


<<xyz>> is changed from the base scenario

Files:
- batchrun-compare.R 
  Main R program to conduct this comparative analysis.

Folders:
- input
  Input files (vaccine coverage & disease burden template)
- results
  Output files of disease burden estimates
- plots
  Plots to visualise results

