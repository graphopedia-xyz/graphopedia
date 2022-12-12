---
title:  error bars
  
functions:
- uncertainty



tools:
  - name:   Microsoft Office
    link:   https://support.office.com/en-us/article/add-change-or-remove-error-bars-in-a-chart-e6d12c87-8533-4cd6-a3f5-864049a145f0

  - name:   ggplot2 in R (code)
    link:   http://www.cookbook-r.com/Graphs/Plotting_means_and_error_bars_(ggplot2)/

examples:

  - title:  Litter Carbon Stocks in Different Forests
    author: Chao Zhang, Beicheng Xia, Junyu Lin
    note: Different letters indicate significant differences across forest types (S-N-K test, p < 0.05). Error bars denote standard errors.
    link:  https://www.mdpi.com/1999-4907/7/12/299/htm
    image: litter-carbon-stocks-in-forests.jpg

synonyms:
- error-bar chart

---
show variability and uncertainty. In a chart, the error bars may represent the standard deviation (SD) of the data,
the standard error of the mean (SE), a confidence interval, the data range, or percentiles.
<!--more-->
Error bars consist of a line, the length of which represents the uncertainty or variability and tick marks that make the ends of the line more apparent. The error bars can appear in different types of charts, most commonly appearing in bar charts.
Charts with error bars provide information describing the data or information about the conclusions, or inferences that were made based on the data. [^cumming]

Error bars are commonly misinterpreted by readers and researchers [^belia] when reflecting the *confidence interval*. The confidence interval account for the fact that few studies measure an entire population but rather a small subset of it. If we measure something in a population of 100 people in order to make generalizations about that same quality in all people in the world, we would have to re-measure other random sets of 100 people multiple times.  The true mean all people in the world will still be unknowable, but if we do this 100 times and 95 times we come up with the same mean, we can say that we achieved 95 percent confidence interval around our mean for the 100 people we happened to test. This means that if we continued studying different random samples of 100 people, 95 percent of the time, the true mean for all people would fall within the confidence interval.


## Further reading
1. [Error bar](https://en.wikipedia.org/wiki/Error_bar) article on Wikipedia.

## References
[^cumming]: Cumming, Geoff, Fiona Fidler, and David L. Vaux. ["Error bars in experimental biology."](https://dx.doi.org/10.1083%2Fjcb.200611141) The Journal of cell biology 177.1 (2007): 7-11.
[^belia]: Belia, Sarah, et al. ["Researchers misunderstand confidence intervals and standard error bars."](https://doi.org/10.1037/1082-989X.10.4.389) Psychological methods 10.4 (2005): 389. [PDF](https://pdfs.semanticscholar.org/1102/df06d8372cdceaa98ad835c72efcf6748f36.pdf?_ga=2.165963518.1548441697.1595549721-2010748498.1595549721)

