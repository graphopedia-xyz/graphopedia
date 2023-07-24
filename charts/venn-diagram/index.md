---
title:  Venn diagram
  
functions:
- part-to-whole relationship

visualizationTechniques:
  - techniqueId: BOU
    informationType: category


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
    author: Anna Vital
    note:  2 sets venn diagram
    link:  https://blog.adioma.com/what-is-an-infographic/
    image:  infographic-definition.png

  - title:  Two Letter Scrabble Words
    author:  FifeThirtyEight
    link:  https://fivethirtyeight.com/features/da-gi-po-te-isnt-baby-talk-its-a-key-to-scrabble-success/
    image:  scrabble-word-dna.png

  - title:  Shared Letters Between 3 Alphabets
    author: Mark Vital 
    link:   https://commons.wikimedia.org/wiki/File:Venn_diagram_gr_la_ru.svg  
    image:   shared-letters-between-the-alphabets.png
    
  - title: What is an Infographic - The Components
    author:  Anna Vital
    note:  This is an example of 4 sets venn diagram
    link:  https://blog.adioma.com/what-is-an-infographic/
    image:  what-is-an-infographic.png

  - title:  The Anatomy Of Determination
    image:  the-anatomy-of-determination.png
    author: Anna Vital 
    link:   https://blog.adioma.com/anatomy-of-determination-in-startups-infographic/
    note:   This 3-way Venn diagram with icons explains the qualities of determination in startups based on the eponymous essay by Paul Graham.
    
  - title:  Ikigai
    author:  David McCandless
    link:  https://informationisbeautiful.net/visualizations/ikigai-japanese-concept-to-enhance-work-life-sense-of-worth
    image:  ikigai-diagram.png


synonyms: 
  - set diagram
  - ballantine diagram
  - primary diagram

order: 290

---

[//]: # ( TODO add more euler diagram examples: )
[//]: # (   maybe this? https://www.reddit.com/r/dataisbeautiful/comments/8ld4ht/venndiagram_comparison_of_biggest_religious )
[//]: # (   find example of non-intersecting euler diagram like this:  https://visual.ly/community/infographic/humor/how-would-you-your-graphic-design )
[//]: # (   find example of proportional ven diagram, where size of circles means sets size)
[//]: # (   find example of venn diagrmans in grid/small-multiple, possibly genetic data)


shows all possible logical relationships between one or more sets. The sets appear as simple shapes, usually circles or rectangles. Each area of overlap is labeled.  Unlike the Venn diagram, the Euler diagram shows not all but only relevant relationships.

<!--more-->
There are two types of Venn diagrams: 
1. *Quantitative* - representing numbers. These diagrams typically do not scale the circle proportionally to the number they represent, but the numbers are written inside the circles and their intersections[^harris]. 
If the shapes are proportional to their values, the diagram is limited to 4 sets since it is impossible to create symmetric Venn diagrams with more than four proportional sets. 
2. *Qualitative* - representing categories. The intersections of sets form a subset that is a new category.

In theory, Venn diagrams work for any number of sets, but the layout becomes increasingly difficult to both build and read beyond just four sets. [^heberle] 

Certain shapes are unusable for Venn diagrams of more than three sets. For three sets, it is possible to use circles.  For four and five sets, it is not possible to use circles such that each one intersects each of the others separately. Ellipses have to be used for four-and five-set Venn diagram.  

The illustration below shows why circles are not possible in a four-set  Venn diagram. The red and blue circles do not overlap uniquely; the same is true for the yellow and brown.
![Four sets in a Venn diagram](venn-diagram-of-four-sets.svg)

For more than five sets, ellipses become unsuitable, but rectangles and triangles can be used.

[//]: # ( TODO: Add complexity section with illustrations for 2-sets venn, 3 sets venn, 4 sets venn, 5 sets venn, etc )

The Venn diagram appeared in 1880, created by John Venn. He did not call it "Venn diagram" but "Eulerian circles." Euler diagrams are similar to Venn diagrams because both use shapes to represent sets, but Venn diagrams are more restrictive. They require labeling all the possible intersections.

[//]: # ( TODO: Add sections with basic operations on sets: Unions, Intersections, relative complement, Absolute complement, symmetric difference. Add illustration for each interaction, from Wikipedia )


## Further reading
- [Venn diagram](https://en.wikipedia.org/wiki/Venn_diagram) article on Wikipedia.

## References
[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?id=LT1RXREvkGIC) Oxford University Press, 2000, p. 961. Harris explains the differences between the quantitative and qualitative Venn diagrams.
[^heberle]: Heberle, Henry, et al. ["InteractiVenn: a web-based tool for the analysis of sets through Venn diagrams."](https://doi.org/10.1186/s12859-015-0611-3) *BMC bioinformatics* 16.1 (2015): 169. Heberly discusses Venn diagrams of 4 and more sets. [PDF](https://bmcbioinformatics.biomedcentral.com/track/pdf/10.1186/s12859-015-0611-3)

