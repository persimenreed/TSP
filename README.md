# TSP
Solution for the Traveling Salesman Problem using local search optimization algorithm in combination with multilevel paradigm to improve quality. As this is a multilevel paradigm, there are three levels. At level 0, no cities are connected, at level 1, we have ten clusters of cities, resulting in two cities for each cluster. In level 2 there are five clusters with four cities in each cluster. After clustering, there are a certain amount of iterations used for optimization for each level. Optimization consist of swapping two cities (or two clusters at level 1 and level 2), and recalculate the distance, where the best is kept. After traversing through the levels, we end up with an (hopefully) optimized solution compared to the ramdom start.

*TSP-coordinates*: Cities are assigned a random x value and a random y value between a min and a max value, and has distance calculated through euclidian algorithm.

*TSP-distance*: All city pairs are assigned a distance between 1 and 5 between them.
