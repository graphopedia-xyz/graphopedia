# Graphopedia
The Graphopedia is a compilation of chart, diagram, and visualization model types used in information graphics. The list includes general-purpose visualization types. Each type is given a definition, its anatomy, examples, tools for creating the visualization, and the sources.

The current catalog contains about 200 entries of charts and their variations and is constantly expanding.

[![INTRO VIDEO](https://img.youtube.com/vi/Pqia9PjWy2M/0.jpg)](https://www.youtube.com/watch?v=Pqia9PjWy2M)


# How To Contribute
There are several ways one can contribute to the project:

 - Submit new chart type or its variation.
 - Expand existing chart articles and link to the sources.
 - Help with classification, organizing, and grouping similar charts.
 - Fix grammar or obvious logical mistakes.
 - Add missing tools and code for each chart and variation.
 - Find relevant examples for each graph.
 - Help to design icons and cover images for each graph, making them more uniform.
 - Explain how the particular chart type works and illustrate where applicable.
 - Suggest new features.

To be able to propose new changes, the contributor should have basic knowledge of Markdown and GitHub.


## Submitting changes to each graph
To submit changes for each graph, you can use the edit link below each article:

Alternatively, you can locate the specific chart folder in this repository.
After editing the chart article, a new pull request has to be opened. In the pull request, the contributor can add images relevant to a particular chart.
After the pull request is submitted, the reviewer will look at it and approve or reject the changes. The reviewer might propose some changes.
After all the changes are resolved and the pull request is approved, it will be merged with the main repository, and the changes will appear on the main website.

More than one chart could be edited in one pull request. We encourage submitting similar changes that are relevant to many charts in one pull request, rather than creating many pull requests. For example, classifying, reordering, or adding new tools that cover multiple charts could be done in one pull request.


## Structure
Each main chart folder has the following structure:
```
[chart-name]
 |->examples
 |->set
 |->varitations
 |->index..md
```

Where ```index.md``` is the file that contains chart article and metadata, the ```set``` folder contains icons and cover images, and the ```examples``` folder contain relevan examples..
If the chart has variations, they will be in the ```variations``` sub-folder.

Each variation has the sructure identical to the main chart, except no *variations* folder.

