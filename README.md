# Data Wrangling for Visualization in `R` and `Python` 

Regardless of your programming language of preference, data visualization is paramount to understanding complex patterns in data. However, there are many steps that need to be taken *before* we can visualize the data. Therefore, this tutorial offers an illustration of the entire data visualization process in `R` and `Python`. To illustrate the process from importing to visualizing data, we will use data from the [FiveThirtyEight Presidential Endorsement Tracker](https://fivethirtyeight.com/features/were-tracking-2020-presidential-endorsements-heres-why-they-probably-still-matter/). 

Given this focus on outlining the process of visualizing data, this tutorial does not offer a comprehensive explanation of the principles underlying data visualization. Some prior knowledge of data wrangling/visualization in either language before starting this tutorial is recommended before going through the examples in this tutorial. For an overview of `tidyverse` tools in `R` that will be useful to brush up on before starting this tutorial, you can go through some of the [tidyverse primers](https://rstudio.cloud/learn/primers) from RStudio. 

Therefore, this tutorial provides a *very brief* overview of: 

* Importing and summarizing data 
* Preparing data for visualization 
* The next step: basic visualization with barplots and faceting   

This tutorial uses several packages from the `tidyverse` library in `R`, as well as the `reticulate` package which provides a comprehensive set of tools for interoperability between `Python` and `R.` The `Python` libraries utilized in this tutorial are `pandas` for importing, summarizing, and manipulating data and `plotnine` for data visualization.
