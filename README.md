# traveling_politician

## Objective and Problem Description
The traveling politician problem is a variation of the traveling salesman problem. A politician hopes to become the president of the United States. Their campaign starts with the presidential primaries in the capital of Iowa. The politician then wants to visit the capital of every U.S. state to campaign before ending in the White House in the nation’s capital of Washington, D.C. The politician does not want to visit any capital more than once. They would like to campaign in every capital one and only once. To be efficient and save on time and money, they would like to do this in as short a path as possible. The Traveling Politician Problem aims to find this shortest path. The map can be thought of as a graph with 51 points (the capitals of all 50 U.S. states, plus Washington, D.C.) and a set of distances between each of them. The starting point and ending point are already set (the capital of Iowa and Washington, D.C., respectively). This leaves 49 points to be visited in between the starting and ending points, this does not include the start and end points.

## Methodology
For the traveling politician problem with any subset of all 50 states, a brute-force approach is used to find the shortest route among all possible paths. Google Maps is selected as the standard method to measure and compute any geographical information. For a given n-state problem without explicit specification of the states, all states beside Iowa (the starting state) are choosed at random.

## Contents
* Modules
* Loading data
* Computing Distances
* Shortest route of n-states
* Example n-state solutions

## Module Prerequisites
* pandas - loading and processing data
* googlemaps / geopy - geographical data functions associated with Google Map
* numpy - array and matrix data processing
* itertools - efficient tools for iterable objects
