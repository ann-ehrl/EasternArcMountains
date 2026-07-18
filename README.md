# EasternArcMountains
This repository was created with the purpose of sharing Google Earth Engine code developed for land designation of the Eastern Arc Mountains. 
This code determines land cover within the region of interest and produes a raster of this information. 
It conducts an investigation every ten years during the rainy season with lush vegetation, selecting imagery with low cloud cover.
Code classifies imagery into the same land cover classes by establishing thresholds trained by polygons on 2000 imagery and applies to 2010 and 2020.
0 = Natural Forest  
1 = Shrubland       
2 = Grassland        
3 = Cropland      
4 = Built-up        
5 = Bare             
7 = Water            
11 = Tree Cover 
