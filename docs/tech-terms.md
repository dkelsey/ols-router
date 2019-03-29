# BC Route Planner
# Technical Terms
Term | Definition
----: | -----------
<a name="Bidirectional Search">Bidirectional Search</a> | Searching a road graph to find the shortest path by performing two simultaneous searches. The first search forward from the starting point, and the second search backwards from the target location/node.
<a name="Customizable Contraction Hierarchies">Customizable Contraction Hierarchies</a> | A technique to extend Contraction hierarchies to support changing road conditions and user preferences. Preprocessing is divided into three phases. In the first expensive phase, short cuts are computed based solely on the topology of the road network. In the second, much less expensive phase, short cuts are computed based on updated road conditions (e.g., road or lane closures, traffic congestion). In the third phase, short cuts are computed based on user preferences.
<a name="Contraction Hierarchies">Contraction Hierarchies</a> | A preprocessing technique to speed up shortest route calculation over large road networks. During preprocessing, short cuts are added to the road network and nodes are ordered to reflect the depth of the shortcuts. Edge weights are static when computing short-cut weights. 
<a name="Dijkstra's Algorithm">Dijkstra's Algorithm</a> | A shortest path algorithm to find the shortest route between nodes in a graph. Quick to implement and relatively quick to solve, no pre-processing. Uses a priority queue typically sorted by edge weight / cost.
<a name="Earliest Arrival Problems">Earliest Arrival Problems</a> | .
<a name="Edge">Edge</a> | A terms used for a routing arc that connects nodes. In reality this could be a road, pathway, bike lane etc.
<a name="Edge weight">Edge weight</a> | Travel time a vehicle needs to traverse the edge (road).
<a name="Heuristic Algorithm">Heuristic Algorithm</a> | .
<a name="Heuristic - Freeflow">Heuristic - Freeflow</a> | .
<a name="Heuristic - Predicted path">Heuristic - Predicted path</a> | .
<a name="Predicted congestions">Predicted congestions</a> | Use functions as edge weights.
<a name="Realtime congestions">Realtime congestions</a> | Use realtime travel time.
<a name="Road graph data">Road graph data</a> | .
<a name="Time-dependent routing">Time-dependent routing</a> | The earliest arrival problem in road networks with time-dependent functions as edge weights.
<a name="Time-independent routing">Time-independent routing</a> |
<a name="Time dependent sampling">Time dependent sampling</a> | .
<a name="Time dependent routing (Dynamic)">Time dependent routing (Dynamic)</a> | Takes into account both predicted congestions using historic data as well as realtime congestions.
<a name="Time-dependent scalars">Time-dependent scalars</a> | .
<a name="Time-independent scalars">Time-independent scalars</a> | .
<a name=""></a> | .
<a name=""></a> | .
<a name=""></a> | .
<a name=""></a> | .
<a name=""></a> | .
