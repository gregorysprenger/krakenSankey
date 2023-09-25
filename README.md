# krakenSankey

This repository contains an R file that can be run with `Rscript` from the cli
to create sankey html plots from kraken report files.

## Basic Usage

Use conda to install R and other dependencies using the `environment.yml` file.

```
# Create environment
conda create env -f environment.yml

# Activate environment
conda activate krakenSankey

# Create sankey plot from kraken report
Rscript krakenSankey.R kraken.report sankey_plot.html
```

Functions in `krakenSankey.R` requires several packages and attempts to install them for you if they are missing. If an error occurs, please try to install the packages manually.

### References / Acknowledgments
Most of the code in this repo is 1:1 extracted from Florian Breitwieser's repo
[pavian](https://github.com/fbreitwieser/pavian).


