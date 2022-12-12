---
title: cartogram

functions:
- geospatial data


related:
  - bubble-map
  - dasymetric-map

tools:
  - name:   Mapbox
    link:   https://www.mapbox.com/cartogram
    
  - name: Tilegrams
    link: https://pitchinteractiveinc.github.io/tilegrams/

  - name:   Tableau Sample
    link:   https://www.tableau.com

examples:
  - title:  The U.S. Foreign Aid Budget Visualized
    author: The Washington Post
    link:   https://www.washingtonpost.com/graphics/world/which-countries-get-the-most-foreign-aid/
    image:  us-aid-cartogram.png

  - title:  The True Size of Africa
    author: 
    link:  
    image:  true-size-of-africa.jpg

  - title:  How Maps Lie (showing cartograms of U.S. Presidential Election 2016)
    author: Mark Newman
    link:   https://www.washingtonpost.com/graphics/politics/2016-election/how-election-maps-lie/
    image:  us-election-cartogram.png
 
  - title:  Job Popularity by State
    author: Nathan Yau
    link:  https://flowingdata.com/2019/02/27/where-your-job-is-most-popular/
    image:  job-popularity-by-state.png
 
  - title:  World Population Cartogram
    author: John Tomanio
    link:   http://johntomanio.com/new-gallery/i74g44c8agxtk2532jprj0yf7fj7gc
    image:  population-consumption.png

  - title:  World Consumption Cartogram
    author: John Tomanio
    link:   http://johntomanio.com/new-gallery/p9wjfds2pp1l63sdsm2jxe5zjikteg
    image:  consumption-cartogram.png
    

synonyms:
   - value-by-area map
   - anamorphic map

order: 380

---

is a type of map that substitutes land area with time, population or any other variable, distorting the geometry of the map. The distortion usually happens by way of resizing the map regions according to a statistical parameter, but in a way that keeps the map recognizable.

<!--more-->
There are four types of cartograms based on the method of distortion: 
1. *Contiguous cartogram* also known as *deformation cartogram*  distorts areas by pulling or pushing the boundaries between regions. 
2. *Non-contiguous cartogram*  scales each region independently to an area that reflects a data point
3. *Dorling cartogram* display each region as a circle with its area representing a data point
4. *Rectangular cartogram* represent each region in the map with a rectangle area 

Preserving accuracy in a cartogram is a known challenge. It is not possible to create a perfect cartogram free of statistics and geographic errors, but it is possible to balance the three parameters of cartogram's accuracy:

1. Statistical accuracy - how accurately the distorted area represents the statistical data. It is measured in terms of "cartographic error."
2. Geographical accuracy - resemblance of distorted geographic areas to the cartogram shapes, including their positions relative to each other
3. Topological accuracy - resemblance of adjacent regions in the cartogram to the areas in the original map.

For human perception, Dorling cartograms demand more effort than non-contiguous cartograms. Reading contiguous cartograms also leads to fewer errors than for Dorling cartograms. [^nusrat]

Cartograms are criticized for misrepresenting geography, data, and the adjacency of regions in a map. [^nusr] Since cartograms assume reader familiarity with the original map, readers unfamiliar with the actual geography of a map may not be aware of a cartogram's distortion.   It is recommended to provide at least the points along the country outlines that are proven to be the visual cues for shape identification. [^rittschof] Another option is providing an inset map showing the actual geography. [^dent]

An advantage of a cartogram is its ability to show a reader an unusual view of the world or an area that is otherwise familiar.[^tyner3]
Another advantage of cartograms is that data does not need to be classified or range graded, as can be the case with [proportional symbols maps](/bubble-map).
 
Showing data that has little to do with the actual land area is often best done with a cartogram. Information designers have noticed that representing actual geography is not always an essential feature of a map. For example, it is difficult even to see densely-populated states like New York, while large states like Wyoming have few people living there. On a demographic map, Wyoming would look too large, and New York would appear unjustifiably small.

Cartograms became popular in 1934 when cartographer Erwin Raisz published the first statistical rectangular cartograms.[^tyner]

## Combinations
New cartogram variations are possible from combinations with other charts. For example, a Dorling cartogram with a mini-chart in place of each circle, following the principle of [small multiples](/small-multiples), becomes a new variation of more data-dense and multivariate cartogram. 

Some charts that can replace circles in a Dorling cartogram include [histogram](/histogram), [pie chart](/pie-chart), [proportional area diagram](/proportional-area-diagram), [area chart](/area-chart), [sparkline](sparkline), [Chernoff faces](/chernoff-faces), [line graph](/line-graph), [slopegraph](/slopegraph).

## Alternatives
1. [*Choropleth map*](/choropleth-map) uses colored areas to represent the measurement of a variable proportional to a colored area.

2. [*Bubble map*](/bubble-map) represents data as scaled symbols overlapping a map without distorting the map features.

3. [*Dot Distribution Map*](/dot-distribution-map) uses a dot symbol to represent a data point showing the distribution of values through the scatter pattern similar to a scatter plot.


## Further reading
1. [Cartogram](https://en.wikipedia.org/wiki/Cartogram) article on Wikipedia.

## References
[^nusrat]: Nusrat, Sabrina, Md Jawaherul Alam, and Stephen Kobourov. ["Evaluating cartogram effectiveness."](https://arxiv.org/pdf/1504.02218.pdf) *IEEE transactions on visualization and computer graphics* 24.2 (2018): 1077-1090.
[^nusr]: Nusrat, Sabrina, and Stephen Kobourov. ["The state of the art in cartograms."](https://www2.cs.arizona.edu/~kobourov/star.pdf) *Computer Graphics Forum*. Vol. 35. No. 3. 2016.
[^tyner3]: Tyner, Judith A. [*Introduction to thematic cartography.*](https://www.amazon.com/Introduction-Thematic-Cartography-Judith-Tyner/dp/0134891058) Prentice Hall, 1992.
[^tyner]: Tyner, Judith A. [*Principles of map design.*](https://books.google.com/books?id=385ti0DxibcC) Guilford Publications, 2014. p. 189 
[^rittschof]: Rittschof, Kent A. ["The Use of Cartograms in Visualizing Data Associated with Familiar and Unfamiliar Areas."](https://archive.org/details/ERIC_ED384624/page/n3) (1995).
[^dent]: Dent, Borden D. ["Communication aspects of value-by-area cartograms."](https://www.tandfonline.com/doi/abs/10.1559/152304075784313278) *The American Cartographer* 2.2 (1975): 154-168.

