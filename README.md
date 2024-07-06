# DESeq2
This is a DESeq script for my  CRC_Concept
This script will help me filter counts data from the UHR_HBR tutorial using a defined threshold
It will then create a DESeq_Counts matrix from the HTSeq counts data frame that I had initially made. You can request for this from me.
I will eventually create the required objects for the DESeq data matrix that will be called into the DESeq function
Further we will perform a log-fold shrinkage to reduce the variability of gene reads accross samples.
Note that DESeq uses unnormalised count data because it can normalise the data on its own by estimating a size factor
