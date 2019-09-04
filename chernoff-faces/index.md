---
title:  Chernoff faces

tags:
- comparison


tools:
  - name:   R package
    link:   https://rdrr.io/cran/DescTools/src/R/SpecialPlots.r

  - name:   R tutorial
    link:   https://flowingdata.com/2010/08/31/how-to-visualize-data-with-cartoonish-faces/

examples:
  - title:  The Face of Crime in the United States
    author: Nathan Yau
    link:   https://flowingdata.com/2010/08/31/how-to-visualize-data-with-cartoonish-faces/#jp-carousel-20488
    image: united-states-crime.png

  - title:  The Emoji States of America
    author: Lazaro Gamio
    link:  https://www.axios.com/the-emoji-states-of-america-1513302318-0ca61705-de75-4c8f-8521-5cbab12a45f2.html
    image:  united-states.png
 
  - title:  Average Personal Well-Being by Borough
    author:  James Cheshire and Oliver Uberti
    link:  http://www.oliveruberti.com/the-information-capital
    image:  average-personal-wellbeing-london.jpeg

order: 480

---
show multiple variables using features of a human face that vary in size and shape, reflecting a value. Chernoff faces rely on the feature of human psychology to recognize even small differences in facial features.

<!--more-->

Chernoff faces allow for a fast comparison across many variables. For that reason, they draw attention to how data sets or data series compare to each other in a generalized way. Since Chernoff faces do not communicate exact values, they are not suitable for visualizations where the reading of precise values is essential.

Making the faces recognizable and yet unique is one of the main challenges of using this method in information graphics. 


Chernoff faces have been criticized for misunderstanding how the perception of faces happens: that people do not perceive separate facial features but the entire face in a holistic way. [^kosara]

Using the width and length of faces to encode variables is also problematic. Some faces become too large and some too small. One solution to this problem is normalizing face size,  which in turn leads to facial feature distortion. [^raciborski]

Chernoff faces are named after their inventor American statistician Herman Chernoff who proposed this technique in 1973 to visualize geological data. [^chernoff] In his proposal, Chernoff suggests visualizing up to 18 data variables using faces.

## Sources
[^kosara]: Kosara, Robert. ["A Critique of Chernoff Faces."](https://eagereyes.org/criticism/chernoff-faces) Retrieved October 29 (2007): 2017.
[^raciborski]: Raciborski, Rafal. ["Graphical representation of multivariate data using Chernoff faces."](https://ageconsearch.umn.edu/record/142994/files/sjart_gr0038.pdf) The Stata Journal 9.3 (2009): 374-387, p. 374.
[^chernoff]: Chernoff, Herman. ["The use of faces to represent points in k-dimensional space graphically."](http://www.apprendre-en-ligne.net/mathematica/3.3/chernoff.pdf) *Journal of the American Statistical Association* 68.342 (1973): 361-368. p. 361.
