# Advanced Examples

Examples that involve more complex logic, advanced Mesa features, or non-trivial agent interactions.

---

### Ant System for Traveling Salesman Problem
An implementation of the Ant System algorithm where agents probabilistically traverse a network of cities using pheromone trails and heuristic distance to collectively discover efficient solutions to the Traveling Salesman Problem.

**Example:**  
[examples/aco_tsp](../examples/aco_tsp)

---

### Bank Reserves Model
A simplified model of a monetary economy where agents move randomly and trade probabilistically, generating deposits, withdrawals, and loans within a centralized banking system.

**Example:**  
[examples/bank_reserves](../examples/bank_reserves)

---

### Boltzmann Wealth Model (Network)
A wealth exchange model on a network where agents randomly transfer money to neighbors, producing emergent wealth inequality consistent with statistical mechanics principles.

**Example:**  
[examples/boltzmann_wealth_model_network](../examples/boltzmann_wealth_model_network)

---

### Schelling Model with Caching and Replay
An extension of the classic Schelling segregation model demonstrating how simulation runs can be cached, persisted, and replayed using the Mesa-Replay framework.

**Example:**  
[examples/caching_and_replay](../examples/caching_and_replay)

---

### Conway's Game of Life (Fast)
An optimized implementation of Conway's Game of Life using Mesa's PropertyLayer abstraction and convolution-based neighbor counting to achieve high simulation performance.

**Example:**  
[examples/conways_game_of_life_fast](../examples/conways_game_of_life_fast)

---

### Dining Philosophers
An implementation of the classic coordination problem demonstrating resource contention, deadlock, and fairness strategies in distributed systems.

**Example:**  
[examples/dining_philosophers](../examples/dining_philosophers)

---

### El Farol Bar Model
A model of bounded rational decision-making where agents decide whether to attend a bar based on past attendance and prediction strategies.

**Example:**  
[examples/el_farol](../examples/el_farol)

---

### The Emperor's Dilemma Agent-Based Model
A model of self-enforcing social norms illustrating how unpopular norms can persist through reputational pressure, compliance, and false enforcement.

**Example:**  
[examples/emperor_dilemma](../examples/emperor_dilemma)

---

### Hexagonal Ant Foraging
A swarm intelligence model where ant agents explore a hexagonal grid, depositing pheromone trails that guide collective path formation.

**Example:**  
[examples/hex_ant](../examples/hex_ant)

---

### Hotelling's Law Simulation
A spatial competition model where firms adjust location and price to maximize market share within a linear market environment.

**Example:**  
[examples/hotelling_law](../examples/hotelling_law)

---

### Humanitarian Aid Distribution Model (Needs-Based Architecture)
A humanitarian logistics model where agents with evolving needs interact with aid distribution systems under resource constraints.

**Example:**  
[examples/humanitarian_aid_distribution](../examples/humanitarian_aid_distribution)

---

### Virus-Antibody Model
A biological simulation where virus and antibody agents interact in continuous space, demonstrating mutation, adaptation, and immune response dynamics.

**Example:**  
[examples/virus_antibody](../examples/virus_antibody)

---

### Pseudo-Warehouse Model (Meta-Agent Example)
A demonstration of Mesa's meta-agent capability where robot agents are composed of coordinated sub-agents in a hierarchical architecture.

**Example:**  
[examples/warehouse](../examples/warehouse)

---

### Mesa Charts Example
A visualization-focused example demonstrating Mesa's charting capabilities including line charts, pie charts, and bar charts for model metrics.

**Example:**  
[examples/charts](../examples/charts)

---

### Agents and Networks Model
A geospatial agent-based model demonstrating agent movement across a road network using shortest-path routing between locations derived from geographic data.

**Example:**  
[gis/agents_and_networks](../gis/agents_and_networks)

---

### GeoSchelling Model (Polygons)
A geospatial adaptation of the Schelling segregation model where geographic regions act as agents that evaluate neighborhood similarity.

**Example:**  
[gis/geo_schelling](../gis/geo_schelling)

---

### GeoSchelling Model (Points & Polygons)
A geospatial Schelling model where agents reside within geographic regions and relocate when neighborhood similarity thresholds are violated.

**Example:**  
[gis/geo_schelling_points](../gis/geo_schelling_points)

---

### GeoSIR Epidemics Model
A geospatial epidemic simulation where agents move across a geographic map and infections spread through proximity-based interactions.

**Example:**  
[gis/geo_sir](../gis/geo_sir)

---

### Rainfall Model
A hydrological simulation where raindrop agents flow downhill across a digital elevation model to illustrate terrain-driven water dynamics.

**Example:**  
[gis/rainfall](../gis/rainfall)

---

### Urban Growth Model
A GIS-enabled urban expansion model simulating land-use change and development patterns across geographic space.

**Example:**  
[gis/urban_growth](../gis/urban_growth)