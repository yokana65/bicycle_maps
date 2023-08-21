# bicycle_maps

The aim of this package is to draw tour maps given a list of desired locations to visit.

It needs a shapefile with the underlying spatial information and a column the specifies the regional areas to visit.

From there it provides three functions:

## Load spatial data

This function loads a dataframe of type "sf" that contains the boundaries of the spatial area of interest and the description of the areas.
At this point this data has to be provided by the user in a shapefile and the column names as well as the specified CRS have to be known.