# Multi-HCC

This repository contains code to reproduce the results presented in the paper 

> **Norman J, Mehta N, Kim WR, Liang JW, Biggins SW, Asrani SK, Heimbach J, Charu V, Kwong AJ. Multi-HCC: A practical model to prioritize patients with hepatocellular carcinoma on the liver transplant waiting list. 2024.**
  
## R package dependencies
- Data wrangling and visualization: [`tidyverse`](https://cran.r-project.org/web/packages/tidyverse/index.html), [`haven`](https://cran.r-project.org/web/packages/haven/index.html), [`survminer`](https://cran.r-project.org/web/packages/survminer/index.html), [`gridExtra`](https://cran.r-project.org/web/packages/gridExtra/index.html), and [`tableone`](https://cran.r-project.org/web/packages/tableone/index.html)
- Model fitting and evaluation: [`survival`](https://cran.r-project.org/web/packages/survival/index.html), [`randomForestSRC`](https://cran.r-project.org/web/packages/randomForestSRC/index.html), [`gbm`](https://cran.r-project.org/web/packages/gbm/index.html), [`survivalmodels`](https://cran.r-project.org/web/packages/survivalmodels/index.html), [`pec`](https://cran.r-project.org/web/packages/pec/index.html), [`mgcv`](https://cran.r-project.org/web/packages/mgcv/index.html), and [`compareC`](https://cran.r-project.org/web/packages/compareC/index.html)
- Parellelization: [`foreach`](https://cran.r-project.org/web/packages/foreach/index.html) and [`doParallel`](https://cran.r-project.org/web/packages/doParallel/index.html)

## Data
- Adult patients listed for liver transplant who received an initial approved HCC exception from October 8, 2015 to December 31, 2022, in the Organ Procurement and Transplantation Network (OPTN) database. 