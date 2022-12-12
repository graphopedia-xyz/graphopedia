---
title: stem and leaf plot
  
functions:
- distribution

tools:
  - name:   Octave Forge (code)
    link:   https://octave.sourceforge.io/octave/function/stemleaf.html

  - name:   R (code)
    link:   https://octave.sourceforge.io/octave/function/stemleaf.html

  - name:   CalculatorSoup
    link:   https://www.calculatorsoup.com/calculators/statistics/stemleaf.php

examples:
  - title:  Train Schedule
    author:  Oran Viriyincy
    link:  https://www.flickr.com/photos/viriyincy/5040255373
    image:  train-schedule-stem-leaf-plot.png

  - title:  Volcanos Ordered by Height (from "The Visual Display of Quantitative Information" by E. Tufte)
    author:  John Tukey
    link: 
    image: volcano-height-stem-and-leaf-john-tukey-by-edward-tufte.png
 
  - title:  Timetable at Minato Mirai train station in Yokohama, Japan
    author:  Eliazar
    link:  https://commons.wikimedia.org/wiki/File:Stem-and-leaf_time_tables_in_Japanese_train_stations.jpg
    image: Stem-and-leaf_time_tables_in_Japanese_train_stations.jpg
 
synonyms:
  - stem-leaf display
  - stemplot

---
is a type of table that shows the frequency of elements occurring in relation to certain numbers. The stem is a single number or number range that defines a class, and the leaves are the multiples numbers that occur in that class.


<!--more-->
A stem-and-leaf plot consists of two columns, usually separated by a vertical line. The left column contains the stems and the right column contains the leaves. 
The principle behind the stem-and-leaf plot is the ordering of the values from lowest to highest. The digits that all values share in common form the *stem*. The last significant digit of the values becomes the *leaves*.

Leaves are displayed in a single line opposite its stem. For this reason, large data sets are not suitable for using with the stemplot. [^hilfiger] The leaf values are sorted from lowest to highest. [^leblanc] The use of the numbers themselves to construct the shape of the graph has the benefit of packing more information into the graph then would be presented in a comparable histogram. 

The stem-and-leaf plot was introduced by John Tukey with the intention of showing not only the shape but also the content of a distribution. [^tufte]


Stemplots are an alternative way of showing a frequency distribution table or a histogram. The distinguishing feature of a stem-and-leaf plot is that it shows the actual number values. 

## Further reading
1. [Stem-and-leaf plot](https://en.wikipedia.org/wiki/Stem-and-leaf_display) article on Wikipedia.

## References
[^hilfiger]: Hilfiger, John Jay. [Graphing Data with R: An Introduction.](https://www.amazon.com/dp/1491922613/) O'Reilly Media, Inc., 2015,  pp. 81-81.
[^leblanc]: LeBlanc, David C. [Statistics: concepts and applications for science.](https://books.google.ca/books?id=gtawVU0oZFMC&redir_esc=y) Jones & Bartlett Learning, 2004, pp. 39-40.
[^tufte]: Tufte, Edward R. [The visual display of quantitative information.](https://www.edwardtufte.com/tufte/books_vdqi) Vol. 2. Cheshire, CT: Graphics press, 2001, p.140.
