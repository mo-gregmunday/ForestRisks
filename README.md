# Risk of unavoidable impacts on forests at 1.5 with and without overshoot

[![DOI](https://zenodo.org/badge/756271280.svg)](https://zenodo.org/doi/10.5281/zenodo.10653493)

Contains code for reproducing results from Munday et al., _in review_.

## Installing the conda environment

To install the conda environment, run the following on your command line:

`conda env create -f environment.yml`

## Move the data in 

To negate having to re-write data import paths in the notebooks, just drop the downloaded ForestRisks folder in the `data` directory. Then unzip it in place, along with all the gzipped NetCDF files in it.

#### Notes on the notebooks

`all_other_figures.ipynb` requires a good amount of memory to run (it runs fine on a decent spec. MacBook Pro), based on the quantity of data required for some of the plots.

Some variables have squiggly underlines - don't worry about this. The notebooks will still run, this is just a consequence of using the `%%capture` keyword in some notebook cells, which makes sure hundreds of irrelevant warnings aren't output.
