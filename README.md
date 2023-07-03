# AirNav
This project is provided solely for the submission of the CSC111 Course Project and to be
used by instructors and TAs while marking and assessing this project. This file is Copyright (c) 2023 Arjun Menon, Azlan Naeem, Hadi Naqvi, and Rohan Regi.

This project models all international airports as a weighted graph in order to use [Djikstra's Algorithm](https://en.wikipedia.org/wiki/Dijkstra's_algorithm) to find the shortest path between airports. It does this by transforming a large dataset of airports and airport routes using the Python pandas library into an easily accessible dataframe. Additionally, in order to compute the distances between airports, it uses the [Haversine formula](https://en.wikipedia.org/wiki/Haversine_formula) which only requires the latitude/longitude of the airports.
