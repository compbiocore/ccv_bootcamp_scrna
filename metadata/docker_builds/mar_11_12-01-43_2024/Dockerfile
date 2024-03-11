FROM ghcr.io/compbiocore/bootcamp_scrna:mar_11_11-56-32_2024

# Install R packages
RUN R -e "install.packages('BiocManager', dependencies=TRUE, repos='http://cran.rstudio.com/', ask = FALSE)"
RUN R -e "install.packages('devtools', dependencies=TRUE, repos='http://cran.rstudio.com/', ask = FALSE)"
