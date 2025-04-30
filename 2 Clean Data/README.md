# This folder contains all the cleaned data used in the data exploration and analysis.

There is one file: the stork_AMR_clean.rds contains all the clean data. 

The 2021 data will be used for modeling, as no landfill use data was collected in 2020 due to COVID-19 restrictions

Variables:
"cisa" = Unique Laboratory Sample ID
"yr" = Sampling Year
"id" = Unique Sample ID
"nes" = Nest Number (Will be repeatedly sampled)
"samp" = Sampling Period (will have 3, Factoral)
"ad" = Adult ID
"age" = Adult Age
"fledged" = # of hatchling fledged
"hatched" = # of eggs hatched
"eggs" = # of eggs laid
"nsuccess" = fledged/hatched
"mean_lui" = the number of observations of one bird within the total number of visits to landfill for 2021