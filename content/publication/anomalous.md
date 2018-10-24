+++
abstract = "It is becoming increasingly common for organizations to collect very large amounts of data over time, and to need to detect unusual or anomalous time series. For example, Yahoo has banks of mail servers that are monitored over time. Many measurements on server performance are collected every hour for each of thousands of servers. We wish to identify servers that are behaving unusually. We compute a vector of features on each time series, measuring characteristics of the series. The features may include lag correlation, strength of seasonality, spectral entropy, etc. Then we use a principal component decomposition on the features, and use various bivariate outlier detection methods applied to the first two principal components. This enables the most unusual series, based on their feature vectors, to be identified. The bivariate outlier detection methods used are based on highest density regions and alpha-hulls."
abstract_short = ""
authors = ["Rob J Hyndman", "Earo Wang", "Nikolay Laptev"]
date = "2015-11-14"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In: *Data Mining Workshop (ICDMW)*, IEEE."
publication_short = "ICDMW"
selected = true
title = "Large-scale unusual time series detection"
url_code = "https://github.com/robjhyndman/anomalous"
url_doi = "https://doi.org/10.1109/ICDMW.2015.104"
url_pdf = "http://pub.earo.me/icdm2015.pdf"

+++

```{txt}
@InProceedings{cikm,
  title = {Large-scale unusual time series detection},
  author = {Rob J Hyndman and Earo Wang and Nikolay Laptev},
  booktitle = {Proceedings of the IEEE International Conference on Data Mining},
  year = {2015},
  publisher = {Atlantic City, NJ, USA. 14--17 November 2015},
  doi = {10.1109/ICDMW.2015.104},
}
```
