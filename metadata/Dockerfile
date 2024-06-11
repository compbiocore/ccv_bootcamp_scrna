FROM ghcr.io/compbiocore/bootcamp_scrna:mar_25_10-42-25_2024
RUN R -e "install.packages('igraph', dependencies=TRUE, repos='http://cran.rstudio.com/', ask = FALSE)"
RUN R -e "BiocManager::install('clusterProfiler')"
