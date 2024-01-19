# BST 270 Individual Project

This repo contains all necessary information for my reproduction of figures 1 and 2 from the [Why Many Americans Don't Vote](https://projects.fivethirtyeight.com/non-voters-poll-2020-election/) article from FiveThirtyEight.

## Packages/R environment

The figure reproduction utilizes the dplyr, ggplot2, and reshape2 packages in R.

Versions for the associated packages are found at the end of the knitted R notebook (PDF file), however these packages are standard and I would still expect the figures and data cleaning to be reproducible with slightly different package versions than the ones listed.

## Project Structure

The project folder is broken up into a **data** folder and a **notebooks** folder.

Within the **notebooks** folder, there are two files:

- Why-Americans-Dont-Vote.Rmd
- Why-Americans-Dont-Vote.pdf

The Rmd is R notebook which can be opened in R and the individual chunks can be run sequentially to reproduce the two figures from the article.
The PDF file is the final knitted document with inline figures.

Within the **data** folder, there are two files:

- nonvoters_cookbook.pdf
- nonvoters_data.csv

The PDF file contains an explanation of all of the variables in the CSV file and the associated meaning of coded variable values.
The CSV file contains the actual data used for reproduction and this is what is loaded in the R notebook.
