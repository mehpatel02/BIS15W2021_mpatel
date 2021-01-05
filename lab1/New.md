---
title: "Untitled"
output: 
  html_document: 
    keep_md: yes
---



# This is my first Markdown file
## This is my first Markdown file
### This is my first Markdown file

```r
4*2
```

```
## [1] 8
```

## This is my [email](mailto: mehpatel@ucdavis.edu)

## This is [Google](http://www.google.com)

# Practice 1

```r
4+4
```

```
## [1] 8
```

```r
4-4
```

```
## [1] 0
```

```r
4*4
```

```
## [1] 16
```

```r
4/4
```

```
## [1] 1
```

# Practice 2
title: "Practice 2"

This is some text for Practice 2
*This is some text for Practice 2*

# Practice 3


```r
#install.packages("tidyverse")
library("tidyverse")
```


```r
ggplot(mtcars, aes(x = factor(cyl))) +
    geom_bar()
```

![](New_files/figure-html/unnamed-chunk-4-1.png)<!-- -->
