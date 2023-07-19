---
title: icicle plot

functions:

tools:

examples:
  - title:  Mike Bostock's version of Icicle Plot
    author: Mike Bostock
    link:   http://www.cs.middlebury.edu/~candrews/showcase/infovis_techniques_s16/icicle_plots/
    image:  mike-bostok-icicle-plot.png

  - title:  Icicle Plot from clustering of 48 objects
    link:   http://www.cs.middlebury.edu/~candrews/showcase/infovis_techniques_s16/icicle_plots/
    image:  original-icicle-plot.png
	  note:   Icicle plot from original paper


synonyms:
  - icicle chart
  - partition chart

---

is a graphical representation of hierarchical data that is used to visualize the relationships between different levels of a hierarchy

<!--more-->
Introduced by Kruskal and Landwehr in their paper[^krushal-landwehr], it is particularly useful for displaying the proportions of different categories within a hierarchy and for comparing the sizes of different categories within the same level of the hierarchy.

In an icicle plot, the hierarchy is represented by a set of rings, with the innermost ring representing the top level of the hierarchy and the outer rings representing lower levels. Each ring is divided into segments, which represent the different categories within each level of the hierarchy. The length of each segment corresponds to the size of the category it represents.

The icicle plot is an effective visualization tool for hierarchical data because it allows the viewer to see the proportions of different categories within the hierarchy and to compare the sizes of different categories within the same level of the hierarchy. It is often used in business, economics, and other fields to represent data such as market share, budget breakdowns, and organizational structures.

[//]: # (Generated with GPT-3. @Todo rewrite)

## Further reading
- ["What are Icicle Plots?"](https://www.cs.middlebury.edu/~candrews/showcase/infovis_techniques_s16/icicle_plots/icicleplots.html), www.cs.middlebury.edu

## References
[^krushal-landwehr]: J. B. Kruskal and J. M. Landwehr, ["Icicle Plots: Better Displays for Hierarchical Clustering"](https://doi.org/10.2307/2685881), *The American Statistician*, May 1983, Vol. 37, No. 2, pp. 162-168
