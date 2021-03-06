# Harry-Potter-Sentiment-Analysis

Author: Georgianna James

## Summary

In this repo, I conduct a sentiment analysis on the Harry Potter series by J.K. Rowling, guided by an in-class exercise that can be found in the resources linked below. 

To view the analysis:

* [HP Sentiment Analysis MD File](./hp_sentiment_analysis.md)

To view the code:

* [HP Sentiment Analysis RMD File](hp_sentiment_analysis.Rmd)

## Required Packages

```
library(harrypotter)
library(tidyverse)
library(tidytext)
library(textdata)
```

## Data

Run the following code in your console to retrieve the Harry Potter package used in this repo:

```devtools::install_github("bradleyboehmke/harrypotter")```

Once you have this package installed, you can load the "harrypotter" library as you normally would:

```library(harrypotter)```

The details of this package can be found on the associated [github repository](https://github.com/bradleyboehmke/harrypotter). 

## Resources

This sentiment analysis was derived from an [in-class exercise](https://cfss.uchicago.edu/notes/harry-potter-exercise/) for the course [MACS 30500](https://cfss.uchicago.edu/). 