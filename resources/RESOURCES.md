# Resources

The Pattern of Longitudinal Change in Serum Creatinine and Ninety-Day Mortality After Major Surgery
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4829495/

https://stats.stackexchange.com/questions/193054/time-series-analysis-for-predicting-a-binary-outcome
https://stats.stackexchange.com/questions/263715/binary-classification-on-time-series-data
https://stats.stackexchange.com/questions/197084/binary-time-series
https://stats.stackexchange.com/questions/263715/binary-classification-on-time-series-data/264117

https://datascience.stackexchange.com/questions/45684/multivariate-time-series-binary-classification
https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/

https://stats.stackexchange.com/questions/193054/time-series-analysis-for-predicting-a-binary-outcome

https://cran.r-project.org/web/packages/data.tree/vignettes/data.tree.html
https://www.r-graph-gallery.com/334-basic-dendrogram-with-ggraph.html
https://stackoverflow.com/questions/4722689/creating-tree-diagram-for-showing-case-count-using-r

https://stackoverflow.com/questions/26194298/unlist-data-frame-column-preserving-information-from-other-column

case_when instead of nested ifelse statements
read_table2 to quickly and easily make a dataframe e.g.
    tbl <- read_table2(
    "iso    year
    ALB     2003
    ALB     2004")

https://reprex.tidyverse.org/

https://stackoverflow.com/questions/45556169/pass-a-column-name-to-a-function-using-dplyr-mutate-without-using-the-depreciate e.g.
    test = "hi"
    df %>% mutate(!!test = 1)

https://monashdatafluency.github.io/r-rep-res/

citation(package = "base", lib.loc = NULL, auto = NULL)
readCitationFile(file, meta = NULL)
e.g.
    citation("tidyverse")

glimpse() instead of str()

https://stackoverflow.com/questions/13672720/r-command-for-setting-working-directory-to-source-file-location-in-rstudio

    sys.frame(1)$ofile
    parent.frame(2)$ofile

http://www.sthda.com/english/articles/24-ggpubr-publication-ready-plots/81-ggplot2-easy-way-to-mix-multiple-graphs-on-the-same-page/

http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html
