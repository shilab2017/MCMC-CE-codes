# MCMC-CE algorithm for calculating small p-values
This repository contains R programs that implement the MCMC-CE algorithm for the calculation small p-values and generate the results in our paper for introducing the algorithm titled "Accurate and Efficient Calculation of Small P-Values with the Cross-Entropy Method: Applications in Genomic Data Analysis" by Shi et al (2018+). For utilization and distribution of the programs, please contact shiyang@scu.edu.cn.

The "R_programs.zip" file contains all the programs. After unzip the file, there are 5 folders:
1. The "simulation1_quadratic_function_of_MVN" folder contains R programs generating the simulation results based on the chi-squared distribution reported in the paper.
2. The "simulation2_linear_function_of_MVN" folder contains R programs generating the simulation results based on the Cauchy distribution reported in the paper.
3. The "Example1" folder contains R programs for generating the results of "Example 1: Gene set/pathway enrichment analysis" reported in the paper. The RNA-Seq gene expression data and the clinical data for the melanoma patients are obtained from the TCGA data portal: https://portal.gdc.cancer.gov/ . Note that we used the data from the "Legacy Archive".
4. The "Example2" folder contains R programs for generating the results of "Example 2: GWAS – joint testing a group of genetic markers in a genomic region" reported in the paper. The mouse GWAS data are available from: https://wp.cs.ucl.ac.uk/outbredmice/heterogeneous-stock-mice/
5. The "Example3" folder contains R programs for generating the results of "Example 3: Ratio statistic in differential gene expression analysis" reported in the paper. The leukemia gene expression data is available from the bioconductor R package golubEstes: http://bioconductor.org/packages/release/data/experiment/html/golubEsets.html

The programs were run and tested with R version 3.4.2 on Intel Xeon CPU E5-2640/2.6 GHZ with Scientific Linux operating system.
