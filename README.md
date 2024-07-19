# Undergraduate Final Project
## Overveiw
For my final project I completed a systematic reveiw and meta analysis of studies looking at long term potentiation and synaptic placticity using electrophysiology in the hippocampus of APP transgenic mouse 
 odels of Alzheimers Disease. Alzheimer’s disease (AD) in a progressive neurodegenerative disorder for which there is currently no effective disease altering treatment available. Most research in this area is aimed at reducing levels of amyloid beta build-up in the brain however despite extensive research, only a single treatment has been licensed. This has lead researchers to look at other targets, such as synaptic dysfunction which occurs earlier in disease progression. AD pre-clinical research utilises transgenic animal models, but the extent to which these models show synaptic dysfunction has shown varied results. This study used systematic review and meta-analysis techniques to analyse the impact of modelling AD with mutations in amyloid precursor protein on synaptic plasticity outcomes and identify sources of heterogeneity across publications. Results were pooled from 24 papers screened from 2109 studies. Publications measuring synaptic plasticity in hippocampal slices In vitro were identified by searching the AD-SOLES database for studies published from 2018-2023. AD-SOLES is a website (https://camarades.shinyapps.io/ad-soles/) containing a living database that systematically collects and synthesises all experimental evidence in animal models of Alzheimer’s disease using an integrated series of automated tools including machine-learning approaches to continually include new evidence published. It uses regular expressions (regex), which are a sequence of characters used to define a search pattern, applied to the title and abstract and the full text to tag papers with outcome measures. Meta analysis showed synaptic plasticity outcomes were found to be reduced in animal models of AD but it was not possible to identify sources of heterogeneity in the analysis. The study established the extent of the modelling effect of APP models of AD which giving a better understanding of baseline synaptic function, which would be a highly useful tool for the drug development pipeline. 

## Contents
- data
  - pilot study data : contains the 4 data sets required to run the pilot study that was carried out as an investigative study. This is the data required to run the script found in script > pilot study called "Pilot Study.rmd"
  - data wrangling and figures data : contains the 5 data sets required to run the script found in script > data wrangling and figures called "figures_markdown.rmd"
  - mata analysis data : contains the data set required to run the script found in script > meta analysis called "diss meta analysis.rmd"
- script
   - pilot study 
   - data wrangling and figures
   - meta analysis
- mark downs
   - data wrangling and figures : contains a compiled markdown pdf with annotated code for the data wrangling and figures code
   - meta analysis : contains a compiled markdown pdf with annotated code for the meta analysis code
- Report: Contains the final document produced for the dissertation as well as the pilot study final report

## Requirements
To run the code in this repository, you will need the following software and packages:
- R (version 4.0 or higher)
- RStudio (recommended)
- R packages:
  - tidyverse
  - dplyr
  - ggplot2
  - writexl
  - kableExtra
  - rmarkdown
  - knitr
  - janitor
  - meta
  - metafor
  - readxl
  - imputeTS
  - gt
  - scales
  - stringr
  - gtExtras\

For the pilot study:\
you can install these packages in R using the following commands:\
  ```install.packages(c("tidyverse", "dplyr", "ggplot2", "writexl"))```

For the meta analysis:\
 ```install.packages(c("tidyverse", "kableExtra", "rmarkdown", "knitr", "janitor", "meta", "metafor", "metafor", "readxl", "writexl"))```

for the data wrangling and figures:\
```install.packages(c("tidyverse", "dplyr", "ggplot2", "imputeTS", "gt", "scales", "stringr", "readxl", "readxl", "writexl", "gtExtras"))```

  ## Contact
  For any questioins or issues please contact:\
  Laurel Renton\
  laurel.renton@googlemail.com
