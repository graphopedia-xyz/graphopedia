---
title: tree map
  
tags:

related:
  - sunburst-chart

tools:
  - name:   Microsoft Excel
    link:   https://support.office.com/en-us/article/create-a-treemap-chart-in-office-dfe86d28-a610-4ef5-9b30-362d5c624b68

  - name:   RawGraphs
    link:   https://rawgraphs.io/learning/how-to-make-a-treemap/
  
  - name:  FoamTree
    link:  https://carrotsearch.com/foamtree

examples:
  - title:  Causes of Untimely Death
    author:  Thomas Porostocky for Wired
    link:  https://www.wired.com/2013/11/infoporn-causes-of-death/
    image:  causes-of-death.jpg
  
  - title:  Who Finances China's Belt and Road Initiative?
    author:  the Financial Times
    link:  https://www.ft.com/__origami/service/image/v2/images/raw/http://prod-upp-image-read.ft.com/f7d83f06-667a-11e9-a79d-04f350474d62?source=next&fit=scale-down&width=690&format=auto&quality=medium&dpr=1
    image:  belt-and-road-financing.png
    
  - title:  A World of Languages
    author:  Alberto Lucas López   
    link:  https://www.scmp.com/infographics/article/1810040/infographic-world-languages
    image:  a-world-of-languages.png

  - title:  Jobs Charted by State and Salary
    author:  Nathan Yau
    link:  https://flowingdata.com/2014/07/02/jobs-charted-by-state-and-salary
    image:  jobs-by-state-and-salary.png

  - title:  The Billion Dollar-o-Gram
    author:  David McCandless
    link:  https://informationisbeautiful.net/visualizations/the-billion-dollar-o-gram-2009
    image:  billion-dollar-o-gram.png

synonyms:
  - treemap chart
---

is a type of chart that displays hierarchical data using nested figures, usually rectangles, proportional to the data they represent. The area of each figure represents a data point. Any tree map can also be represented as a [tree diagram](/tree-diagram). 

<!--more-->
Each *parent node* on a tree diagram is represented as a larger rectangle that contains a smaller rectangle that is a *child node*. This recursive construction allows the tree map to visualize hierarchical data with any number of levels.

The tree-map is a space-filling type of data visualization allowing for a compact representation of a large dataset.
The tree map was invented by professor Ben Shneiderman at in the early 1990s as a solution to visualizain of disk space usage. He explained that "Tree structured node-link diagrams grew too large to be useful, so I explored ways to show a tree in a space-constrained layout." [^schneiderman]

Rectangle-based treemaps have two legibility and layout problems:
1. The overlapping rectangles make it difficult to see the rectangles at the lower layers.
2. The aspect ratio of rectangles that are made to fit certain space can be make them difficult to see.

Solutions to this problem offer using other figures such as polygons as in Voronoi tree map and circles as in circle tree map. However, even at low data densities reders are able to compare the areas of rectangles faster than the bars of [bar charts](/bar-chart). [^kong]

## Variations

### Voronoi Treemap
Voronoi treemaps represent hierarchical data by recursively partitioning polygons using weighted centroidal Voronoi diagrams. The polygon areas represent data the same wey as in the rectangle-based tree map.

###Jigsaw Treemap
Jigsaw treemap is based on the geometry of space-filling curves. They assume that the weights are integers and that their sum is a square number. The regions of the map are rectilinear polygons and highly non-ortho-convex. Their aspect ratio is guaranteed to be at most 4.
### Gosper Maps
 Based on the geometry of Gosper curves. It is ordered and stable, but has a very high aspect ratio.

### Circle Tree Map
Also called *circle packing*, the circle tree map is functionally the same as the rectangle-based tree map except the human perception fof circles is limited in its ability to judge the area. That is why circle packing is recommended only for communicating the general idea of how the parts of the tree diagram relate to each other.

## Alternative charts
1. [*Marimekko chart*](/marimekko-chart) uses the area of rectangles positioned along the X and Y axes to represent three variables.
2. [*Tree diagram*](/tree-diagram) uses nodes and links to show a hierarchical structure.

## Sources
[^kong]: N. Kong, J. Heer and M. Agrawala, ["Perceptual Guidelines for Creating Rectangular Treemaps"](https://ieeexplore.ieee.org/document/5613436) in IEEE Transactions on Visualization and Computer Graphics, vol. 16, no. 6, pp. 990-998, Nov.-Dec. 2010. doi: 10.1109/TVCG.2010.186s
[^schneiderman]: Shneiderman, Ben. [“Treemaps for space-constrained visualization of hierarchies.”](http://www.cs.umd.edu/hcil/treemap-history/index.shtml) (2005).
