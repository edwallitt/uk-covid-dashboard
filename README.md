# UK Coronavirus Dashboard

This dashboard is built with R using the R Makrdown framework and was adapted from this [dashboard](https://ramikrispin.github.io/coronavirus_dashboard/) by Rami Krispin.

**Data**

The input data for this dashboard is the dataset available from the [`{coronavirus}`](https://github.com/RamiKrispin/coronavirus){target="_blank"} R package. Make sure to download the development version of the package to have the latest data:

```
install.packages("devtools")
devtools::install_github("RamiKrispin/coronavirus")
```

The data and dashboard are refreshed on a daily basis.

The raw data is pulled from the Johns Hopkins University Center for Systems Science and Engineering (JHU CCSE) Coronavirus [repository](https://github.com/RamiKrispin/coronavirus-csv).
