---
layout: post

title:  Arc Diagram

image:
  featured: arc-diagram.png
  main: arc-diagram.svg

related:
  - title: Hive Plot
    link: hive-plot
    image: hive-plot.png

  - title: Chord Chart
    link: chord-chart
    image: chord-chart.png
    
  - title: Sankey Chart
    link: sankey-chart
    image: sankey-chart.png

tools:
  - name:   D3.js
    link:   https://d3js.org/
    
  - name:   D3 code example by Robert Gove
    link:   https://bl.ocks.org/rpgove/53bb49d6ed762139f33bdaea1f3a9e1c


examples:
  - title:  <cite>Codebases millions of lines of code</cite> by InformationisBeautiful 
    link:   https://informationisbeautiful.net/visualizations/million-lines-of-code/
    note:   This is a tape diagram that uses an arc diagram to show connections between two versions of software where the thinkness of the arc shows the amount of re-used code


  - title:  <cite>Bible Cross-References</cite> by Chris Harrison
    link:   http://www.chrisharrison.net/index.php/Visualizations/BibleViz
    note:   An arc diagram showing 63,000 cross references with a bar chart inverted at bottom to show the number of connected in each node.
     
---

An arc diagram shows connections between any two nodes out multiple nodes positioned on a single axis.<sup>1</sup> The number of arc connection that come out of a single node is usually represented as a bubble that is sized relative to the number of connections, as in as bubble chart.<sup>2</sup> In practice, an arc diagram usually does not show all possible connected pairs because of the resulting clutter, but rather it shows a subset of connections.
In visualizations made for the web, showing more than about a hundred nodes is impractical.

### Origin
In 1964, mathematician Thomas Saaty proposed the first version of the arc diagram for the purpose of showing intersecting numbers.<sup>3</sup> In 2001 the arc diagram was popularized by Martin Wattenberg who diagrammed pieces of music in his project *The Shape of Song*.<sup>4</sup>

Sources:
1. ["Arc Diagrams: Visualizing Structure in Strings", IBM Research](http://ieg.ifs.tuwien.ac.at/~aigner/teaching/ws06/infovis_ue/papers/arcdiagram_01173155.pdf)
2. ["Arc Diagrams in R: Les Miserables" by Gaston Sanchez](http://www.gastonsanchez.com/visually-enforced/got-plot/how-to/2013/02/02/Arc-Diagrams-in-R-Les-Miserables/)
3. [The Minimum Number of Intersections in Complete Graphs](https://www.pnas.org/content/52/3/688)
4. ["The Shape of Song" by Martin Wattenburg"](http://turbulence.org/Works/song/gallery/gallery.html)