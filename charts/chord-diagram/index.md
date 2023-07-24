---
title:  chord diagram

functions:
  - network of relationships
  - part-to-whole relationship

visualizationTechniques:
  - techniqueId: PSF
    informationType: proportion
    axisDirection: angular

  - techniqueId: CON
    informationType: relationships between entities


related:
  - sankey-chart
  - arc-diagram
  - hive-plot

tools:
  - name:   Circos
    link:   http://circos.ca/images/samples
    
  - name:   Flourish
    link:   https://flourish.studio/2018/07/25/how-to-make-a-chord-diagram/

  - name:   D3 Chord Diagram
    link:   https://beta.observablehq.com/@mbostock/d3-chord-diagram
    
  - name:   ZingChart
    link:   https://www.zingchart.com/gallery/#Chord
    
  - name:  amCharts
    link:  https://www.amcharts.com/demos/chord-diagram/
    
examples:
  - title:  Impact of Major on Career Path
    author:  Hayley Brooks, Scott Sanderson, and Kaison Tanabe
    link:   https://web.williams.edu/Mathematics/devadoss/careerpath.html
    image:  college-majors.png

  - title:  Leading Exporters and Their Trade With Each Other
    author:  Euromonitor International
    link:   https://blog.euromonitor.com/the-patterns-of-world-trade/
    image:  international-trade.png
  
  - title:  C-Suite Gigs - A Web of Mad Skills
    author:  Vallerio Pellegrini
    link:  https://www.behance.net/gallery/58023115/WIRED-US-C-Suite-Gigs
    image:  c-suite-skills.jpg

    
synonyms:
  - radial network diagram
  - network chord diagram

order: 300

---

shows the weighted connections between nodes in a network. The relationships between any two nodes appear as arcs, the width of which represents the strength of the connection.

<!--more-->

Chord diagrams show relationships between entities of the same type. These relationships are quantified, which is represented by the thickness of the arc connecting them. The arcs can also display a direction.

The nodes appear around the perimeter of the circle. They can be shown either individually or grouped into sectors, each sectors representing part of the whole, the whole being the circle, similar to a pie chart.

Clutter, also known as "hairballs" or overplotting is a known problem with chord diagrams. A way of grouping nodes into categories called hierarchical edge bundling [^holten] addresses this problem. 

A chord diagram resembles the [Sankey diagram](/sankey-chart) since both represent the strength of connections between any two nodes as the thickness of a line. Unlike the Sankey chart, chord diagrams can only show relationships between nodes at the same level of a hierarchy.

Chord diagrams are sometimes mistakenly referred to as [arc diagrams](/arc-diagram). [^kirk]

The chord diagram was first used by *The New York Times* in [this genome chart](https://archive.nytimes.com/www.nytimes.com/imagepages/2007/01/22/science/20070123_SCI_ILLO.html); however, the use of chord diagrams has since extended beyond genomics.


## Alternatives

1. [*Sankey diagram*](/sankey-diagram) represents a flow of any kind, where the width of each arrow corresponds to the quantity of the flow. Sankey diagrams represent hierarchical data.

2. [*Arc diagram*](/arc-diagram) represents connections between any two nodes on a single axis.

3. [*Network diagram*](/network-diagram) displays connections between nodes of the same level in the hierarchy without showing the numeric values representing the strengths of the connections.


## Further reading
- [Chord_diagram](https://en.wikipedia.org/wiki/Chord_diagram_(information_visualization)) article on Wikipedia.

## References
[^holten]: Holten, Danny. ["Hierarchical edge bundles: Visualization of adjacency relations in hierarchical data."](https://aviz.fr/wiki/uploads/Teaching2014/bundles_infovis.pdf) *IEEE Transactions on visualization and computer graphics* 12.5 (2006): 741-748.
[^kirk]: Kirk, Andy. [*Data visualisation: a handbook for data driven design.*](https://books.google.com/books?id=ZrCJDAAAQBAJ) Sage, 2016. p. 189. 

