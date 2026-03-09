# Social Science Examples

Examples that explore social dynamics, opinion formation, norms, collective behavior, and human interaction patterns.

---

### Ant System for Traveling Salesman Problem
An implementation of the Ant System algorithm where agents probabilistically traverse a network of cities using pheromone trails and heuristic distance to collectively discover efficient solutions to the Traveling Salesman Problem.

**Example:**  
[examples/aco_tsp](../examples/aco_tsp)

---

### Schelling Model with Caching and Replay
An extension of the classic Schelling segregation model demonstrating how simulation runs can be cached, stored, and replayed using the Mesa-Replay framework.

**Example:**  
[examples/caching_and_replay](../examples/caching_and_replay)

---

### Color Patches
A cellular automaton model where agents adopt the most common opinion among their neighbors, producing emergent clusters of shared opinions across a spatial grid.

**Example:**  
[examples/color_patches](../examples/color_patches)

---

### Deffuant–Weisbuch
A bounded-confidence opinion dynamics model where agents interact only if their opinions are sufficiently similar, producing outcomes such as consensus, polarization, or fragmentation.

**Example:**  
[examples/deffuant_weisbuch](../examples/deffuant_weisbuch)

---

### The Emperor's Dilemma Agent-Based Model
A model of self-enforcing social norms showing how unpopular norms can persist through reputational pressure, compliance, and false enforcement.

**Example:**  
[examples/emperor_dilemma](../examples/emperor_dilemma)

---

### Humanitarian Aid Distribution Model (Needs-Based Architecture)
A model of humanitarian logistics where beneficiary agents with evolving needs interact with aid trucks implementing a hybrid triage strategy under constrained resources.

**Example:**  
[examples/humanitarian_aid_distribution](../examples/humanitarian_aid_distribution)

---

### Rumor Mill Model
A simulation of rumor diffusion where agents transmit information to neighbors with a configurable probability, enabling exploration of stochastic information spread.

**Example:**  
[examples/rumor_mill](../examples/rumor_mill)

---

### GeoSchelling Model (Polygons)
A geospatial adaptation of the Schelling segregation model where geographic regions act as agents and relocation decisions produce emergent spatial segregation.

**Example:**  
[gis/geo_schelling](../gis/geo_schelling)

---

### GeoSchelling Model (Points & Polygons)
A geospatial Schelling model where agents reside within geographic polygons and relocate when neighborhood similarity falls below a threshold.

**Example:**  
[gis/geo_schelling_points](../gis/geo_schelling_points)