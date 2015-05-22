# Algorithm

Program to schedule the N vehicles in such a way as to maximize the revenue .We can decide to reject a passenger request (as it may not be possible to meet all the requests).

The input will be given in the following format
nN cR
n ∗ n matrix indicating the distances to nearest locations.
A sequence of N locations - indicating where the vehicle is at midnight.
A sequence of R requests.

Solution:
Dijkstra's Single Source Shortest path algorithm was used to find shortest path between two locations.
