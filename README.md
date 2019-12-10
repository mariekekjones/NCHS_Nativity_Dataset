# NCHS Nativity Dataset

The CDC National Center Health Statistics has a dataset about births. It is in a fixed width txt file format. 

This repo houses the scripts to load and subset the data for use in workshops.

Original US Birth 2018 data file and UserGuide are from: https://www.cdc.gov/nchs/data_access/Vitalstatsonline.htm

* .txt datafile was too large to host on Github but can be downloaded directly above.

1. Start with PDF Peeler.Rmd to create codebook_decoder.csv
2. Use MakingDataset.Rmd to create Nativity2018_clean.csv