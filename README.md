# urban-feature-analysis
Python script about creating geographic attributes for each location on the street in Seattle @2020.  
The urban attributes are included:  
1. distance to nearest parks  
  -- define a new function: nearest(df,df,column_name)
  -- calculating the nearest distance between two dataframe with geometry attributes  
2. Speed limit  
  -- what is the spped limit of the street which each location data (POINT) is located on ?  
3. Trees in buffer zones  
  -- How many trees are within the selected buffer zone for each location data (POINT) ?  
4. Crime incidents in buffer zones  
  -- How many crime incidents are within the selected buffer zone for each location data (POINT) ?  

Python Packages are included:  
1. geopandas, pandas  
2. shapely

