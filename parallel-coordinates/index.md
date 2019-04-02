---
layout: post

title:  Parallel Coordinates

image:
  featured: parallel-coordinates.png
  main: change-this.png
  anatomy: change-this.png
  
tags:
  - lorem
  - dolor
  - sit-amet

related:
  - title: Alluvial diagram
    link: alluvial-diagram
    image: alluvial-diagram.png

tools:
  - name:   D3
    link:   https://syntagmatic.github.io/parallel-coordinates/

  - name:   Plotly
    link:   https://plot.ly/r/parallel-coordinates-plot/

examples:
  - title:  <cite>Womens Heptathlon Rio 2016</cite> by The Guardian
    link:   https://www.theguardian.com/sport/ng-interactive/2016/aug/14/how-nafissatou-thiam-beat-the-odds-to-claim-the-heptathlon-gold-in-rio

  - title:  <cite>The Most Valuable Brands</cite> by Valerio Pellegrini
    link:   https://www.behance.net/gallery/27306035/100-MOST-VALUABLE-BRANDS-201015-Corriere-della-Sera

---

Parallel coordinates is type of graph for visualizing many variables while tracing the relationship between them. The fundamental idea of parallel coordinates is to place coordinate axes in parallel, and to present a data point as a connection line between coordinate values<sup>1</sup>. In the parallel coordinates plot, each variable has its own axis and all the axes are parallel to each other. Each axis may have a different scale. Values are displayed as a series of lines that are connected between all the axes.

<!--more-->

### Origin
Parallel coordinates plot was first used by American geographer Henry Gannetts in 1880 when he ranked the U.S. states by economic performance such as manufacturing, taxation, and education.<sup>2</sup>

### Variations
1. **Radar chart** is in principle a parallel coordinates chart plotted in polar coordinates.
2. **Andrews plot** is a smoothened version of a parallel coordinate plot.
3. **Alluvial diagram** is a variant of a parallel coordinates plot for categorical variables that are represented as clusters linked with flow fields of different thickness. They represent changes in the composition of these clusters over time.

Source:
1.[Parallel Coordinates for Visualizing Multi-Dimensional Geometry](https://link.springer.com/chapter/10.1007/978-4-431-68057-4_3)

2.["General Summary, Showing the Rank of States, by Ratios, 1880" by Henry Gannetts](https://www.davidrumsey.com/luna/servlet/detail/RUMSEY~8~1~32803~1152181:General-summary,-showing-the-rank-o?sort=Pub_Date%2CPub_List_No_InitialSort&qvq=q:List_No%3D%274521.152%27%22%2B;sort:Pub_Date%2CPub_List_No_InitialSort;lc:RUMSEY~8~1&mi=0&trs=1)
