---
title: Sankey chart
  
tags:
- network of relationships
- change over time
- part-to-whole relationship

related:
  - alluvial-diagram

tools:

examples:
  - title:  Why Breakups Happen
    author:  Lee Byron
    link:  https://leebyron.com/what/breakups/breakup-sankey.png
    image:  why-breakups-happen.jpg
    
  - title:  The Race To Save The River Ganges
    author: Simon Scarr, Weiyi Cai, Vinod Kumar, and Alasdair Pal
    link:   https://graphics.reuters.com/INDIA-RIVER/010081TW39P/index.html
    image:  ganges-river-pollution.png
    
  - title:  Power Grid
    author:  Adolfo Arranz
    link:   https://www.scmp.com/infographics/article/1538887/power-grid#&gid=1&pid=1
    image:  power-grid.png

  - title:  Map of Russian campaign of 1812 of Napoleon
    author:  Charles Minard
    link:   https://en.wikipedia.org/wiki/Charles_Joseph_Minard#/media/File:Minard.png
    image:  minard-napoleon-russian-campaign.png
  
  - title:  Wiring The City
    author:  Simon Scarr
    link:  http://www.simonscarr.com/electricity
    image:  wiring-the-city.jpg

  - title:  Top Ten Fresh Water Consumers
    author:  Jen Christiansen
    link:  https://www.scientificamerican.com/article/water-in-water-out/
    image:  water-in-water-out.jpg
  
  - title:  Income Statement
    author:  Nadieh Bremer
    link:  https://twitter.com/NadiehBremer/status/1100791165769502720
    image:  income-statement.jpg

order: 330

---
is a type of graph that represents change over time or distance as the width of a flowing line that is proportional to a quantity. Sankey diagrams emphasize the transfers in a system by splitting the flow line. [^schmidt] 
<!--more-->
Sankey diagram flow lines branch out, but they do not re-cluster as they do in the [alluvial-diagram](/alluvial-diagram). 

Sankey diagrams use the metaphor of a river with tributaries which follows the principle that the width of the main stream is equal to the sum of its downstream branches. 

Sankey diagrams are often used to show energy flow, migrant flow, and money flow. Any other system where the amount of items at the start equals the end amount after redistribution fits the use case of Sankey diagrams.

A famous example of a Sankey diagram, cited by Edward Tufte as one of the greatest information graphics ever made, is Charles Minard's *Map of Napoleon's Russian Campaign of 1812* created in 1869. It is a Sankey diagram overlaid onto a map which makes it a [flow map](/flow-map). Sankey chart received its name from the Irish engineer Riall Sankey. In 1898, he created a diagram of steam engine efficiency that used arrows with widths proportional to heat loss. [^schmidt2]

## Alternatives
1. [*Alluvial diagram*](/alluvial-diagram) uses the width of a line to represent the amount of flow between categories, as in [parallel coordinates plot](/parallel-coordinates). Unlike the Sankey diagram, it allows flow lines to re-cluster.

2. [*Flow map*](/flow-map) is essentially a Sankey diagram overlaid onto a map.

3. *Grassmann diagram* is a special case of Sankey diagrams for visualizing energy transformations in thermodynamics.

## Sources
[^schmidt]: [M. Schmidt, The Sankey Diagram in Energy and Material Flow Management: Part I: History, J. Ind. Ecol. 12 (2008)](doi:10.1111/j.1530-9290.2008.00004.x.) 
[^schmidt2]: [M. Schmidt, Energy use in a passenger car](https://www.Ifu.Com/En/e-Sankey/Sankey-Diagram)
[^soundararajan]: [K. Soundararajan, H.K. Ho, B. Su, Sankey diagram framework for energy and exergy flows, Appl. Energy. 136 (2014)](doi:10.1016/j.apenergy.2014.08.070)
