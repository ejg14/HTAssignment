# HTAssignment

This repository contains an analysis of climate data from Melbourne and Oxford to visualise rainfall patterns in the cities between 1995-2015.

Descriptions of the data are available in `data`.

To run this analysis there are two scripts. Use `combine-data.R` to combine the datasets and then `make-plot.R` to anaylse the data and create a plot to visualise the average rainfall through time. Run the scripts using the two commands below:

1.  
```
Rscript src/combine-data.R
```
The input data is in `data` and the results are in `out`.

2.
```
Rscript src/make-plot.R
```
The input data is in `out` (as it is an output of command 1 above) and the results are in `out`.
