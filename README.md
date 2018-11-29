# STAT-405-Final

Make sure to change working directory to the directory where the yelp_academic_dataset_business.csv file is located in line 58

setwd("/Users/ericazhong/Documents/Rice 2018-2019/STAT 405")
businesses <- read.csv("yelp_academic_dataset_business.csv", header = TRUE)
head(businesses)
nrow(businesses)
ncol(businesses)
att <- head(businesses$attributes)
