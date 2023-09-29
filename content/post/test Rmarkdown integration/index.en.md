---
title: "Test Rmarkdown Integration"
author: "Qiang Yang"
date: 2023-05-03
categories: ["R"]
tags: ["R Markdown", "plot", "regression"]
---



# Test R Markdown

By writing this post, I test if Rmarkdown could be integrated properly with my personal website.

# Some test codes

Here I make some figures using the iris dataset.


```r
library(tidyverse)
ggplot(data = iris, aes(x = Sepal.Length, y = Sepal.Width, color = Species, shape = Species, fill = Species)) +
  geom_point() +
  stat_smooth(alpha = 0.3, method = "lm") +
  scale_color_brewer(palette = "Dark2") +
  scale_fill_brewer(palette = "Dark2") +
  theme_bw()
```

<img src="{{< blogdown/postref >}}index.en_files/figure-html/unnamed-chunk-1-1.png" width="672" />

**During the test, I found that the Rmd could not produce a new html in the post folder. However, It works if I move the Rmd outside the website folder and produce a html and copy the html to the post folder.**
