---
title: flow map
  
functions:
- network of relationships
- geospatial data

related:
  - sankey-chart
  - dot-distribution-map

tools:
  - name:   Flow map in R using ggplot2
    link:   https://github.com/rafapereirabr/flow-map-in-r-ggplot

  - name:   R tutorial
    link:   https://flowingdata.com/2011/05/11/how-to-map-connections-with-great-circles/

examples:
  - title:  French Wine Exports Map
    author:  Charles Minard
    link:  https://en.wikipedia.org/wiki/File:Minard%E2%80%99s_map_of_French_wine_exports_for_1864.jpg
    image:  french-wine-exports-minard.jpg
    
  - title:  Chinese Investment in World's Largest Ports
    author: The Financial Times
    link:  https://ig.ft.com/sites/china-ports/
    image:  how-china-rules-the-waves.png

  - title:  A brief history of malaria, leprosy, and smallpox.
    author: Haisam Hussein
    link:   https://www.laphamsquarterly.org/medicine/maps/contagion
    image:  history-of-malaria-smallpox.png
  
  - title:  Internet Cables by 2021
    author: The New York Times
    link:   https://www.nytimes.com/interactive/2019/03/10/technology/internet-cables-oceans.html?mtrref=flowingdata.com
    image:  internet-cables.png

  - title:  Live Wind Map
    author: Martin Wettenberg
    link:   http://hint.fm/wind
    image:  wind-map-united-states.png
    
order: 420


---

is a combination of a map and a [flowchart](/flowchart) or a [Sankey diagram](sankey-chart) that shows the movement of objects from one location to another. 

<!--more-->
A flow map consists of ***flow lines*** overlaid over a map. The flow lines are weighted and directional.
 
Flow maps are used for showing connections between the origin of moving objects and their destinations.  The ***line weight*** shows the amount or strength of connection.  The weight refers to the width of the line. 

Flow maps with weighted connections typically show migration, trade, and data transfers between locations.[^phan] It can be either directional showing movement in a single direction or non-directional, presuming that the movement is happening in both directions. [^harris]

A known challenge in flow map design is the visual clutter made by intersecting flow lines. The solution is in routing the connecting lines such that every child connector branches out from the main flow at a point when it is the closest to its destination. [^tamassia]

The first flow maps are attributed to Henry Drury Harness who created a detailed atlas of the Irish Railways in 1837. [^tamassia]

## Sources
[^phan]: Phan, Doantam, et al. ["Flow map layout."](http://graphics.stanford.edu/papers/flow_map_layout/flow_map_layout.pdf) *IEEE Symposium on Information Visualization*, 2005. INFOVIS 2005.. IEEE, 2005.
[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?id=LT1RXREvkGIC) Oxford University Press, 2000. p.157.
[^tamassia]: Tamassia, Roberto. [*Handbook of graph drawing and visualization.*](https://books.google.com/books?id=lQBrAAAAQBAJ) Chapman and Hall/CRC, 2013. p.709. 

