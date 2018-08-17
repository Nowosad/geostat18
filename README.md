# GeoPAT 2: analysis of spatial and temporal patterns

[GEOSTAT18](http://opengeohub.org/node/146). Prague, Czech Republic, 2018-08-23

**Slides:** https://nowosad.github.io/geostat18/geostat18_nowosad. They contain installation instructions and links to the required datasets.

**GeoPAT 2 (Geospatial Pattern Analysis Toolbox)** is a standalone suite of modules written in C. - Dedicated to the analysis of large Earth Science datasets in their entirety using spatial and/or temporal patterns.
**GeoPAT’s** core idea is to tessellate global spatial data into a grid of square blocks of original cells (pixels).
This transforms data from its original form (huge number of cells each having simple content) to a new form (much smaller number of supercells/blocks with complex content).
A complex cell contains a pattern of the original variable.
**GeoPAT 2** provides means for a succinct description of such patterns and for calculation of similarity between patterns.
This enables spatial analysis such as search, change detection, segmentation, and clustering to be performed on the grid of complex cells (local patterns).

This tutorial gives an introduction to the pattern-based analysis, describes the basic concepts, and presents applications of the pattern-based search, change detection, segmentation, and clustering. Finally, it shows how to adapt concepts from **GeoPAT 2** in your own workflows.
