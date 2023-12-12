# Simple Plant Location using Hueristic method

The project's goal is to provide an analysis of the number of deposits
required to meet the demand of the aforementioned population, as well as the
locations of the deposits on the national territory.


Heuristic methods are primarily used for their ability to search an area 
quickly, particularly in real-world problems with many variables and options 
to deal with. Despite their speed and ease of use, they find a good feasible 
solution rather than an optimal one. As a result, an easy and simple 
constructive method of acting greedy and attempting to find three cheapest 
with the lowest cost (sum of fixed and variable costs) is used. 
In this manner, it first determines the three cheapest facilities to activate 
and then selects one of those three at random.

## Download cities locations

Here is a sample of locations of [cities in Spain](https://simplemaps.com/data/es-cities)




## Install

For the code to run istall the following
```
pip install pulp
pip install haversine
pip install geopandas
```





 
