# ERU

Equivalency Residential Unit determination procedure

1.  Determine # of Single Family zoned parcels  
2.  Spatial Join with subdivisions to determine year of construction for each parcel  
3.  Get count of parcels constructed for each year  
4.  Determine percentage of parcels built each year  
5.  multiply by 250 to scale for sample size  
6.  Combine resulting numbers by decade and pre-1950  
7.  Create subsets of Single Family zoned parcels for each decade  
  -pre-1950s  
  -1950s  
  -1960s  
  -1970s  
  -1980s  
  -1990s  
  -2000s  
  -2010s  
8.  Use QGIS to generate random selections for each subset limiting selection to number derived from percentages.  
9.  Merge random selections into single file  
10.  Digitize each impervious footprint (home, driveway, any concrete surface)  
11.  Calculate square footage for each impervious area and average.
