FROM ghcr.io/compbiocore/bootcamp_scrna:mar_11_01-26-37_2024
RUN R -e "install.packages(c('harmony'),repos = 'http://cran.rstudio.com/',ask = FALSE)"
RUN R -e "devtools::install_github('satijalab/seurat-data')"
