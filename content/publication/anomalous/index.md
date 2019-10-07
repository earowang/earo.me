---
title: "Large-scale unusual time series detection"
authors:
- Rob J Hyndman
- admin
- Nikolay Laptev
date: "2015-11-14t00:00:00z"
doi: "https://doi.org/10.1109/ICDMW.2015.104"

# Schedule page publish date (NOT publication's date).
publishDate: "2015-11-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In: *Data Mining Workshop (ICDMW)*, IEEE."
publication_short: "ICDMW"

abstract: It is becoming increasingly common for organizations to collect very large amounts of data over time, and to need to detect unusual or anomalous time series. For example, Yahoo has banks of mail servers that are monitored over time. Many measurements on server performance are collected every hour for each of thousands of servers. We wish to identify servers that are behaving unusually. We compute a vector of features on each time series, measuring characteristics of the series. The features may include lag correlation, strength of seasonality, spectral entropy, etc. Then we use a principal component decomposition on the features, and use various bivariate outlier detection methods applied to the first two principal components. This enables the most unusual series, based on their feature vectors, to be identified. The bivariate outlier detection methods used are based on highest density regions and alpha-hulls.

# Summary. An optional shortened abstract.
summary: []

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://pdf.earo.me/icdm2015.pdf
url_code: 'https://github.com/robjhyndman/anomalous'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: []
---
