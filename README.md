# bicycle_maps

The aim of this package is to draw tour maps given a list of desired locations to visit.

It needs a shapefile with the underlying spatial information and a column that lists the regional areas to visit.

The package can be build from the directory by running:

```R
fusen::inflate(flat_file = "dev/flat_bicycle_pkg.Rmd",
               vignette_name = "dev-flat_bicycle_pkg",
               overwrite = T)
```

This builds the package with documentation and code from the specified Markdown File.

From there it provides the following functions:

## Load spatial data

This function loads a dataframe of type "sf" that contains the boundaries of the spatial area of interest and the description of the areas.
At this point this data has to be provided by the user in a shapefile and the column names as well as the specified CRS have to be known.