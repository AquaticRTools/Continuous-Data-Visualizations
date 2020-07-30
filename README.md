# Continuous-Data-Visualizations
The two code (.Rmd) documents were created to explore continuous and discrete data collected to determine if high pH values in the Casterly Rock Watershed were natural or due to the already identified nutrient impairment.  

The data_graphing_AquaticRTools.Rmd includes graphing functions and uses ggarrange to print the graphs.  Open the data_graphing_AquaticRTools.html to see the graphs and then you can find the associated code in the Rmd. 
Graphs include:
- Continuous data plot with calibration date labeled on vertical lines
- Tile plot (heat map) of exceedances over time
- CDF curve for each site
- Hourly pH plots
- Facet plots of continuous pH data by watershed
- Box plots of discrete nutrient/water chemistry sampling results
- A set of 4 plots by site: all pH data on record, zoomed in on max pH value, continuous daily pH flux, and site nutrient data box plots
- Facet Site Plots of DO
- Plots of the magnitude, durations, and frequencies of exposures above 8.5 by site
- An interactive datatable of summary pH data
- An interactive pH dygraph

The Calibrationplotting_AquaticRTools.Rmd takes a large pH dataset and creates 3 months plots with calibration lines plotted by color of calibration (Successful, No calibration, Low Flow).
