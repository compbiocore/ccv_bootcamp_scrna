## To use this notebook

1.  Go to `ood.ccv.brown.edu` (you will need an Oscar account).
2.  Go to 'Clusters' in the blue menu bar at the top and click the drop-down that says '\>\_OSCAR Shell Access'
3.  Go to your home folder (`cd ~`)
4.  Git clone the repo (\``git clone https://github.com/compbiocore/ccv_bootcamp_scrna.git`\`)
5.  Go back to `ood.ccv.brown.edu` and look under `Interactive Apps` in the blue menu bar and click on `RStudio on Singularity` under `Expert GUIs`.

Fill in the fields as follows:

-   `Account`: leave blank

-   `Partition`: leave blank

-   `Number of hours`: 24

-   `Num Cores`: 4

-   `Memory`: 15

-   `Singularity Container Path`:/oscar/data/shared/databases/workshops/bootcamp_2024/ngs_count/bootcamp_ngs_counts.sif

-   `Package install Path`: leave blank

-   `Path for R Executable`: This should be the full path to the `ccv_bootcamp_scrna` repository you made in step 4.

-   `R Module`: leave blank

-   `Additional Data Path`: leave blank

-   `Reservation`: bootcamp

Once your job starts, click the button to connect to session. At the top of the screen you'll see a menu bar that starts with 'file', click on 'file' and 'open file' and open the index.qmd file in the repo you cloned.
