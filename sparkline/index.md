---
title: sparkline
  
tags:
- change over time
- correlation

related:
  - small-multiples

tools:
  - name:   Adobe Illustrator
    link:   https://helpx.adobe.com/illustrator/using/graphs.html

examples:
  - title:  Four Decades of State Unemployment Rates in Small Multiples
    author: Matt Stiles
    link:   http://thedailyviz.com/2016/12/14/four-decades-of-state-unemployment-rates-in-small-multiples-part-2/
    image:  the-state-of-us-jobs.png

  - title:  Life expectancy at birth
    author: Nathan Yau
    link:   https://flowingdata.com/2017/01/24/one-dataset-visualized-25-ways/02-time-series-sparklines-2/
    image:  life-expectancy-at-birth.png

synonyms:
  - inline chart

order: 440

---

is a small chart without axes or coordinates, usually intended to be shown inline with text, in a data table, or a [small multiples](/small-multiples) matrix. The purpose of a sparkline is to quickly communicate the shape of the graph without communicating its specific values. 
<!--more-->
The concept of a sparkline comes from American statistician Edward Tufte. He calls sparklines *data-words* and describes them as "data-intense, design-simple, word-sized graphics" that are "embedded in a context of words, numbers, images."[^tufte]

Tufte explains that sparklines are readable despite their small size because the human eye is already trained to see differences in typefaces.

Most commonly, sparklines are line charts. However, the term "sparkline" can also mean any inline embedded contextual information graphic, such as a [histogram](/histogram), without scale and axes, for example. The end data point appears as a number following the sparkline.

Sparklines are common in visualizations of financial data. The use of sparklines has been proposed in medical reports to increase accuracy in medical diagnosis.[^radecki]

## Sources
[^tufte]: Tufte, Edward R. [*Beautiful evidence.*](https://books.google.com/books/about/Beautiful_Evidence.html?id=v302PAAACAAJ) Vol. 1. Cheshire, CT: Graphics Press, 2006. p. 47.
[^radecki]:  Radecki, Ryan P., and Mitchell A. Medow. "Cognitive debiasing through sparklines in clinical data displays." *AMIA Annu Symp Proc.* Vol. 11. 2007. [PDF](https://pdfs.semanticscholar.org/bb6a/af662ea8a9503f15eb01882002a4a637926c.pdf)
