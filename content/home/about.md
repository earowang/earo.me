+++
# About/Biography widget.

date = "2016-04-20T00:00:00"
draft = false

widget = "about"

# Order that this section will appear in.
weight = 1

# List your academic interests.
[interests]
  interests = [
    "Data Visualisation",
    "Computational Statistics",
    "Time Series Analysis",
    "Web Technology"
  ]

# List your qualifications (such as academic degrees).
[[education.courses]]
  course = "PhD"
  institution = "Monash University"
  year = "Present"

[[education.courses]]
  course = "BComm (Hons) in Econometrics"
  institution = "Monash University"
  year = ""
 
+++

Hi, I'm Earo. I'm currently doing my Ph.D. on statistical visualisation of temporal-context data at Monash University. I'm also [#rstats](https://cran.r-project.org) user and developer. I love lightweight and elegant tools, for example, rmarkdown just works as a swiss army knife that powers my posts, slides & research papers.

```{r}
wang::earo %>%
  glimpse()
#> Observations: 3
#> Variables: 2
#> $ advocates <chr> "open data", "open source", "reproducible research"
#> $ uses      <chr> "rstats", "markdown", "neovim"
```
