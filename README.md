Pivot_to_Flare
==============

Convert Solr JSON pivot facet output to the "flare" JSON format used by D3 for hierarchical visualizations. 

Requirements:
Solr 4.0 or higher.

This code is not intended for production use, since it requires direct access to the Solr index via port 8080
(or whatever port you are running Solr on). It is intended to facilitate easy exploration of D3's hierarchical 
visualizations of your Solr data before you commit the resources to creating a production-ready D3 visualization.

Detailed setup instructions are included in the comments in pivot_to_flare.html.

More information about D3: http://d3js.org/

A gallery of D3 examples for inspiration: https://github.com/mbostock/d3/wiki/Gallery
