# Planned revisions to reproduction of Reproduction of Malcomb et al. 2014 

Author: Isaiah, Bennett

## Analysis

1. Fix and clarify the titles of figures showing the rasters of Adaptive Capacity, Drought Exposure, Drought Risk, and Flood Risk
2. Change the Livelihood Sensitivity map from using ggplot2 to using Tmaps and fix the legend so that it is sequential instead of continuous. 
3. Visualize the original Figure 5. before it is compared with the reproduction figure. 
4. Changed the color ramp of the differences of figure 5. map to be divergent. 
5. Implement an additional geometric aggregation with a figure 6 showing the new vulnerability map with the alternatively aggregated data. 
6. Add a brief discussion/conclusion section

## Results

1. Adding or changing a names() function before plotting will enable me to capitalize the titles, changing the expression and remove underscores so that it looks more neat
 

2. Map visually looks the sam, however, the transition to a sequential color ramp in the legend will show each value more clearly.

3. This will look similar to the reproduction figure 5 just with the data from the original figure: georef_bg.gpkg

4. Color of the map min and max values will be changed from pink and purple to orange and purple.

5. Instead of adding each weight together, they will be multiplied and subsequently visualized. 

6. Rmarkdown text disucssing study results 


## Discussion

1. Improves readibility of the reproduction study.

2. Improves interpretation of the values of the map.  

3. Provides additional context for the comparison of the original vs reproduction study figures just as was done for Figure 4.

4. Eliminates visual confusion by creating a contrast between colors of opposite ends of the limits

5. Adds an entire new dimension to the study in order to see how an alternative decision in the research design could have affected the final results.

6. Adds some closure to the study summarizing key points about the successes and failures of the reproduction. 
