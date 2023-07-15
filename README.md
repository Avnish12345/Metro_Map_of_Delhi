# Metro_Map_of_Delhi
The given C++ program implements a metro navigation system for Delhi Metro. It allows users to input the source station and destination station, and then calculates the fare and displays the shortest metro route between the two stations. The program utilizes graph and heap data structures to represent the metro network and find the optimal path.

In the program, each metro station is represented as a node in the graph. The nodes store information such as the station name, metro corridor, and the lines it connects. The connections between stations are represented as edges, which hold the distance between two stations.

To find the shortest path between the source and destination stations, the program uses algorithms like Dijkstra's algorithm, breadth-first search, or depth-first search. These algorithms traverse the graph, considering the distance between stations as the cost of each edge. By finding the optimal path, the program calculates the fare based on the total distance traveled.

The metro route, along with the corresponding fare, is then displayed to the user. This helps commuters navigate through the metro network efficiently and plan their journeys accordingly.

Overall, the program provides a convenient way for users to determine the shortest route and fare between any two metro stations in Delhi, enabling them to travel easily and effectively in the city's metro system.
