---
title:  Venn diagram
  
tags:

related:

tools:   
  - name:   Apple Keynote
    link:   https://www.apple.com/keynote/

  - name:   PowerPoint
    link:   https://support.office.com/en-us/article/create-a-venn-diagram-d746a2ce-ed61-47a7-93fe-7c101940839d
  
  - name:   AnyChart
    link:   https://playground.anychart.com/tags/primary-diagram
  
  - name:  Interactivenn (generator) creates up to 6 sets
    link:  http://www.interactivenn.net/
  
  - name: Venny
    link: http://bioinfogp.cnb.csic.es/tools/venny/
  

examples:
  - title: What is an Infographic
    author:  Anna Vital
    link:  https://blog.adioma.com/what-is-an-infographic/
    image:  infographic-definition.png

  - title:  Two Letter Scrabble Words
    author:  FifeThirtyEight
    link:  https://fivethirtyeight.com/features/da-gi-po-te-isnt-baby-talk-its-a-key-to-scrabble-success/
    image:  scrabble-word-dna.png
 
  - title: What is an Infographic - The Components
    author:  Anna Vital
    link:  https://blog.adioma.com/what-is-an-infographic/
    image:  what-is-an-infographic.png

  - title:  Real Number Set Diagram 
    author:  Keith Enevoldsen
    link:  http://thinkzone.wlonk.com/Numbers/NumberSets.pdf
    image:  number-set-euler.png

  - title:  Ikigai
    author:  David McCandless
    link:  https://informationisbeautiful.net/visualizations/ikigai-japanese-concept-to-enhance-work-life-sense-of-worth
    image:  ikigai-diagram.png

synonyms: 
  - set diagram
  - ballantine diagram
  - primary diagram
  
---

shows all possible logical relationships between one or more sets. The sets are represented as simple shapes, usually circles or rectangles. Each area of overlap is labeled.  Unlike the Venn diagram, the [Euler diagram](/euler-diagram) shows not all but only relevant relationships.

<!--more-->
There are two types of Venn diagrams: 
1. Quantitative - representing numbers. These diagrams do not scale the circle proportionally to the number they represent but the numbers are written on the circles and their intersections[^harris]. If the shapes are proportional, the diagram is limited to 4 shapes since it is not possible to create symmetric Venn diagrams with more than four sets that are are -proportional. 
2. Qualitative - representing categories.

Venn diagrams may be built for any number of sets, however, the layout becomes increasingly difficult to both build and read beyond four sets. [^heberle]

For 3 sets, we can use circles. 

For 4 and 5 sets, we cannot use circles such that all of them intersect uniquely - we have to use *ellipses*. In the illustration below, the red and blue circles do not overlap uniquely. The same is true for the yellow and brown.
![Four sets in a Venn diagram](venn-diagram-of-four-sets.svg)

For more than 5 sets, we cannot use ellipses but other shapes, such as squares and triangles can be used.

The Venn diagram was invented in 1880 by John Venn. He did not call them "Venn diagrams" but "Eulerian circles". Euler diagrams are similar to Venn diagrams because they also use shapes to represent sets, but Euler diagrams are less restrictive since they do not require showing all the possible relationships.

## Sources
[^harris]: Harris explains the the differences between the quantitative and qualitative Venn diagrams, see *Robert L. Harris. 1999. [Information Graphics: A Comprehensive Illustrated Reference.]((https://books.google.com/books?id=LT1RXREvkGIC&printsec=frontcover)) Oxford University Press, Inc., New York, NY, USA. p. 961*
[^heberle]: Discussion of Venn diagrams of 4 and more sets *Heberle, Henry & Meirelles, Gabriela & da Silva, Felipe & P Telles, Guilherme & Minghim, Rosane. (2015). [InteractiVenn: A web-based tool for the analysis of sets through Venn diagrams.](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-015-0611-3) BMC Bioinformatics. 16.*

