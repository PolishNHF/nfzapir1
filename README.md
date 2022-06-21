Package: nfzapir1  
Type: Package  
Title: This package provides functions for fast retrieving data for Polish National Health. Part I.  
Version: 1.0  
Date: 2021-11-28   
Depends: R (>= 3.5.0), tidyverse (>= 1.3.0), httr (>= 1.4.1), rvest (>= 0.3.5), jsonlite (>= 1.6.0)  
Author: e-Health Centre, Polish Ministry of Health, (pl. Centrum e-Zdrowia, Ministerstwo Zdrowia): Mikolaj Kaminski MD, Tomasz Stachurski, Grazyna Chlebicka, Marcin Stus, Tomasz Adamus  
Description: This package provides functions for fast retrieving data for Polish National Health Fund API Part I: Hospitalization data. https://api.nfz.gov.pl/app-stat-api-jgp/.  
License: Unlimited  
LazyData: true  
Imports: 
    readxl,
    tidyr,
    purrr,
    dplyr,
    tibble,
    stringr,
    ggplot2
RoxygenNote: 7.1.1


```
devtoolts::install_github("PolishNHF/nfzapir1")
library(nfzapir1)
```

