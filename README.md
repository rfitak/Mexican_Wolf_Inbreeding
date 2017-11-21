# Mexican_Wolf_Inbreeding
An analysis of inbreeding in Mexican wolves using a genome-wide set of SNP markers

The repository contains code for the calculation, comparison, and simulation of inbreeding coefficients in the endangered Mexican wolf.  Please follow the links below to get the code and associated descriptions for various analyses and data processing.  The results of this study have been published in Fitak et al. (in review) *Conservation Genetics*.  
Some ancillary data files and custom scripts are available in the [Data](./Data) and [Scripts](./Scripts) folders, respectively.

1. [Analyzing the initial Mexican wolf genotypes](./MW-data-processing.md)
    - Downloading and processing the MW genotypes, including data cleaning, and LD pruning
    
    
    
TBD...
2. [Merging together the Mexican wolf genotypes with 4 other canine genotyping studies](./data-prep.md)
    - an in-depth process of merging together the CanineHD genotypes from the Mexican wolves and 4 other studies of dogs and gray wolves.
3. [Global ancestry analysis in the merged dataset](./global.md)
    - LD pruning, PCA, Admixture, and treemix analysis from the merged genotyping across all datasets
4.  [Phasing](./phasing.md)
    - Phasing and imputing missing genotypes in the merged dataset using Beagle v3.3.2
5.  [Identifying local admixture in MW with domestic dogs](./Lamp-ld.md)
    - using LAMPLD to find local haplotype assignment to parental populations
6.  [Simulating admxture](./simulations.md)
    - A series of simulations to evaluate expected local haplotype structure under various migration schemes between Mexican wolves and domestic dogs.

## All code and content herein is licensed under:
## [GNU General Public License v2.0](./LICENSE)
