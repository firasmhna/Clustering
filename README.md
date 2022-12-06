# Clustering
please check this file before you run the R script
unsupervised hieracheal clustering using R
required packages:
ComplexHeatmap
circlize
RColorBrewer
tidyverse

make sure you have already prepared those files in the right format:
heatmap<- excel matrix with expression data as columns and patient ids as rows
ex:
Patients	      HOXB8	       HRH2	     SMYD1
TCGA-QK-A6IF	0.372930218	0.211224138	0.193991273
TCGA-CR-5248	0.011764829	0.282218294	0
TCGA-CV-7242	0.316288523	0.264670649	0.006559229

clinical<- excel file with patient ids as rows and different clinical features as columns (used to add clinical features as column annotations)
ex:
Patients	   	HPV16	     Gender	      Subsite
TCGA-QK-A6IF		NA	      Male	     Oropharynx
TCGA-CR-5248	Positive	  Male	     Oropharynx
TCGA-CV-7242	Negative	 Female       Larynx

make sure that patient ids are in the same order in both files 

$$$
