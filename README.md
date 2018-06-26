# user2018

Slides and code for the 2018 useR! tutorial "Recipes for Data Processing" on Tuesday July 10th at 1:30:

> R has an excellent framework for specifying models using formulas. While elegant and useful, it was designed in a time when models had small numbers of terms and complex preprocessing of data was not commonplace. As such, it has some limitations. In this tutorial, a new package called `recipes` is shown where the specification of model terms and preprocessing steps can be enumerated sequentially. The recipe can be estimated and applied to any dataset. Current options include simple transformations (log, Box-Cox, interactions, dummy variables, ...), signal extraction (PCA, PLS, ICA, MDS, ...), basis functions (splines, polynomials, ...), imputation methods, and others. An example is used to demonstrate the functionality.

The audience should include people who do feature engineering or need to include preprocessing with their models. From a technical standpoint, some experience in modeling and R is a good idea. Basic [`tidyverse`](https://www.tidyverse.org) syntax will be reviewed. 

The materials will be added a few days before the tutorial. To install the required packages:

```r
install.packages(
  c('AmesHousing', 'broom', 'recipes', 'rsample', 'tidyverse', 'yardstick'), 
  repos = "http://cran.r-project.org"
)

# and optionally

install.packages('caret', repos = "http://cran.r-project.org")
```

If you have trouble with any of these, email me at `max@rstudio.com`. We _may_ also have Rstudio Server instances available for those who can't install the above to their computers. 
