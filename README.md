# Continuous-Data-Visualizations
The two code (.Rmd) documents were created to explore continuous and discrete data collected to determine if high pH values in the Casterly Rock Watershed were natural or due to the already identified nutrient impairment.  Open the two associated .html files to see the graphs.

The data_graphing_AquaticRTools.Rmd includes graphing functions and uses ggarrange to print the graphs. There are daily summaries calculated with the tidyquant::transmute function. I made several loops to run plotting functions for each site's data.  Intially I saved each plot in it's own variable name, but then I learned to create a list to save the plots in.  You can open the data_graphing_AquaticRTools.html to see the graphs and then hopefully find the associated code in the Rmd. 

Graphs include:
- Continuous data plot (value vs time) with calibration date labeled on associated vertical lines
- Tile plot (heat map) of exceedances over time, all sites in one graph
- CDF curve for each site
- Hourly pH plots
- Facet plots of continuous pH data by watershed
- Box plots of discrete nutrient/water chemistry sampling results
- A set of 4 plots by site: all pH data on record, zoomed in on max pH value, continuous daily pH flux, and site nutrient data box plots
- Facet Site Plots of DO
- Plots of the magnitude, durations, and frequencies of exposures above 8.5 by site
- An interactive datatable of summary pH data
- An interactive pH dygraph

The Calibrationplotting_AquaticRTools.Rmd takes a large pH dataset and plots data every 3 months with calibration lines plotted by color of calibration (Successful, No calibration, Low Flow).
