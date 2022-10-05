---
title: Sankey chart
  
functions:
- network of relationships
- change over time
- part-to-whole relationship

synonyms:
  - Sankey diagram
  
tools:
  - name:   SankeyMatic (generator)
    link:   http://sankeymatic.com/build/

  - name:   RAWGraphs (generator)
    link:   https://rawgraphs.io/learning/how-to-make-an-alluvial-diagram/
  
  - name:   Sankey Diagram Generator (allows for adding links)
    link:   https://sankey.csaladen.es
 
  - name:   Google Developers (code)
    link:   https://developers.google.com/chart/interactive/docs/gallery/sankey
 
  - name:   Flourish (code, interactive)
    link:   https://app.flourish.studio/@flourish/sankey

  - name:   Charticulator (generator)
    link:   https://charticulator.com/gallery/world_greenhouse_gas_emissions.html

  - name:   Plotly
    link:   https://plot.ly/javascript/sankey-diagram/
 
  - name:   Matplotlib
    link:   https://matplotlib.org/api/sankey_api.html

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
The ***sum of flow lines*** in a Sankey diagram equals one hundred percent of flow. The width of each ***flow line*** represents a value. The ***direction of flow*** is represented with arrows or gradient.

Sankey diagrams use the metaphor of a river with tributaries which follows the principle that the width of the main stream is equal to the sum of its downstream branches. 

Sankey diagrams are often used to show energy flow, migrant flow, and money flow. Any other system where the amount of items at the start equals the end amount after redistribution fits the use case of Sankey diagrams.

A famous example of a Sankey diagram, cited by Edward Tufte as one of the greatest information graphics ever made, is Charles Minard's *Map of Napoleon's Russian Campaign of 1812* created in 1869. It is a Sankey diagram overlaid onto a map which makes it a [flow map](/flow-map). Sankey chart received its name from the Irish engineer Riall Sankey. In 1898, he created a diagram of steam engine efficiency that used arrows with widths proportional to heat loss.

Sankey diagram flow lines branch out, but they do not re-cluster as they do in the [alluvial-diagram](/alluvial-diagram).

## Alternatives
1. [*Alluvial diagram*](/alluvial-diagram) uses the width of a line to represent the amount of flow between categories, as in [parallel coordinates plot](/parallel-coordinates). Unlike the Sankey diagram, it allows flow lines to re-cluster.

2. [*Flow map*](/flow-map) is essentially a Sankey diagram overlaid onto a map.

3. *Grassmann diagram* is a special case of Sankey diagrams for visualizing energy transformations in thermodynamics.


## Sources

### Further reading
1. [Sankey diagram](https://en.wikipedia.org/wiki/Sankey_diagram) article on Wikipedia.

### References
[^schmidt]: Schmidt, Mario. ["The Sankey diagram in energy and material flow management: Part I: History."](doi:10.1111/j.1530-9290.2008.00004.x.) *Journal of industrial ecology* 12.1 (2008): 82-94.
[^soundararajan]: Soundararajan, Kamal, Hiang Kwee Ho, and Bin Su. ["Sankey diagram framework for energy and exergy flows."](https://doi.org/10.1016/j.apenergy.2014.08.070) *Applied energy* 136 (2014): 1035-1042.
