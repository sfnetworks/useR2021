
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sfnetworks in useR! 2021

Slides for the useR! 2021 Regular Talk on Tidy Geospatial Networks in R.

## Abstract:

Geospatial networks are graphs embedded in geographical space. That
means that both the nodes and edges in the graph can be represented as
geographic features: the nodes most commonly as points, and the edges as
linestrings. They play an important role in many different domains,
ranging from transportation planning and logistics to ecology and
epidemiology. The structure and characteristics of geospatial networks
go beyond standard graph topology, and therefore it is crucial to
explicitly take space into account when analyzing them. The sfnetworks R
package is created to facilitate such an integrated workflow. It brings
together the sf package for spatial data science and the tidygraph
package for standard graph analysis. The core of the package is a data
structure that can be provided as input to both the graph analytical
functions of tidygraph as well as the spatial analytical functions of
sf, without the need for conversion. Additionally, it offers a set of
geospatial network specific functions, such as routines for shortest
path calculation, network cleaning and topology modification. The
package is designed as a general-purpose package suitable for usage
across different application domains, and can be seamlessly integrated
in “tidy” workflows that use the tidyverse packages for data science.

Session info
[here](https://teamup.com/event/show/id/p86Mv6RwKZXVMrqE1UZSMVQjwiwA5R)
