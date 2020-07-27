## Maps-Project
This is a maps project developed using **Java-fx** in front-end, **Java** in back-end with **Google Maps API**. My Maps project is a more primitive version of the 
very popular google maps. Using my application we can search for the shortest path between a start location and the destination location specified by the user using 
3 Algorithms : 

# **Breadth First Search Algorithm** : Searches for a path that has minimum number of road intersections between the start point and the destination point.

# **Dijkstra's Algorithm** : Searches for a minimum travel distance path between the start point and the destination point. This Algorithm is slower to discover paths
for larger distances as the algorithm has to move through all the intersections that fall between the start point and the destination point.

# **A-Star Algorithm** : Searches for a minimum travel distance path between the start point and the destination point. This Algorithm is faster than the Dijkstra's 
Algorithm as it takes two parameters while discovering a path that are: distance between start location and the current location and the distance between current 
location and the destination location. This makes our A-Star Algorithm much faster than the Dijkstra's Apporoach as it only discovers far less number of intersections. 
