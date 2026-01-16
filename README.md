# patagona_bioacoustics
Repo associated with Robinson et al. 2026, JFO

## Robinson et al. 2026, Vocalizations distinguish the cryptic giant hummingbird species and clarify range limits, *Journal of Field Ornithology* (DOI: [INSERT ZENODO DATA DOI LINK])

Last updated: 2026-01-15

**Other places data are archived:**
*All original data were obtained from the open databases, the Macaulay Library (ML) and Xeno-Canto (XC) 
*Code and scripts are in this GitHub repository (DOI: [INSERT ZENODO DATA DOI LINK]). 
*Raw data are archived on FigShare: [LINK]. 

This repository contains code and scripts used in a study of vocal differences between Northern Giant Hummingbirds (*Patagona peruviana*) and Southern Giant Hummingbirds (*Patagona gigas*) across their respective South American ranges. This README.md provides a description of files. Many .Rmd files include code to make plots; please note that most final plots were originally produced in R (many as multi-panels) but edited in Adobe Illustrator. 

If you use something here, please cite us (Robinson et al. 2026, Journal of Field Ornithology; and repository DOI), or contact Jessie about who/what is best to cite. 


## FILES

`Patagona_Bioacoustics_DataWrangling_GitHub.rmd`: Script to read in raw data, organize, and wrangle for downstream paper analyses (conducted in Patagona_Bioacoustics_Analysis_GitHub.Rmd). 

`Patagona_Bioacoustics_Analysis_GitHub.Rmd`: Script to analyze data processed in Patagona_Bioacoustics_DataWrangling_GitHub.Rmd. Script includes statistical comparisons of vocal parameters, PCA analyses, LDA analyses, comparisons with morphological analyses, main paper plots, supplement plots, and calculations for Table 1. 

'Patagona_bioacoustics_map_GitHub.Rmd': Code to make map in Figure 1A. Patagona distribution shapefile is freely available from BirdLife. Raster layers and GADM data are freely downloadable with the raster package in R.


-------

Questions? Contact me at jessie.williamson [at] uwyo.edu. 
