# motion-planning-roadmap
Roadmap of areas of study in motion planning

### Notes
* Admissibility of a Heuristic : Guaranteed to not overestimate to cost of least cost path from any state to the goal
* Backward search : is more benefitial if you know that the goal is stationary but robot is moving so costs can be reused for replanning if needed
* Free space assumption : Whatever you dont know assume it as free space to ensure completeness
* f value of state = total cost to reach the goal through the state ( g value +h value)
* h value is cost to goal of that state decided by the heuristic function 
* g value is cost to reach that state from the start position
* undirected graph -> actions are reversible
* Avoid collision checking by comparing distance to obstacles with radius of inner and outer circles
* Graph search : deterministic completeness based on discretisation
* Sampling based planning : probabilistic completeness based on number of samples 
* Connecting two trees in RRT connect can be quite tricky for kinodynamic planning 
