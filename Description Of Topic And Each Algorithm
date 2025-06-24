# Collaboration Networks MST Project

##  Description of Our Network Category + Real-World Applications

### Selected Category: Network Repository Collaboration Networks

Collaboration Networks are links between people (such as researchers, authors, or performers) who have collaborated. These graphs capture connections based on **co‑authorship**, **co‑acting**, or **joint projects**, making them ideal for studying **connectedness**, **information flow**, and **collaborative dynamics**.

#### Specific Network Sizes
- **Small (~10–100 nodes):** e.g., An example of a conference's co‑author network.
- **Medium (~100–1,000 nodes):** e.g., A portion of a scholarly collaboration graph.
- **Large (~1,000–10,000 nodes):** e.g., A field‑wide collaboration network (such as in computer science).
- **Extremely Large (10,000+ nodes):** e.g., A global collaboration graph with millions of researchers.

#### Real‑World Uses
Collaboration Networks are highly relevant across disciplines:
-  **Research and Academia:** Understanding connections, team formation, and cross‑disciplinary collaboration among researchers.
-  **Business and Industry:** Analyzing relationships among employees or departments to optimize teamwork.
-  **Social Media Influencers:** Examining connections between content creators or influencers.
-  **Epidemiology & Knowledge Spread:** Identifying highly connected individuals vital for spreading ideas, best practices, or information.
-  **Policy Making:** Helping organizations comprehend and foster successful collaborations.

#### Why Use MST Algorithms?
By applying MST approaches, one can extract the **backbone** of a collaborative network — a basic structure that captures its essential connectivity. This is beneficial for:
- Identifying critical connections.
- Maximizing resource distribution and communication within a collaborative team.
- Understanding the minimal connections required for spreading information throughout the network.

---

##  Overview of Each MST Algorithm

Here’s an overview of the five MST-style algorithms implemented:

###  Kruskal’s Algorithm
- **How it Works:** Sort all edges by weight and pick the shortest one, adding it if it doesn’t form a cycle (using Union–Find).
- **Best For:** Sparse graphs common in collaboration data.
- **Complexity:** `O(E log E)`

###  Prim’s Algorithm
- **How it Works:** Begin with an arbitrary node and greedily add the shortest edge leading to a new node until all nodes are connected.
- **Best For:** Dense collaboration graphs.
- **Complexity:** `O(E + V log V)` using a priority queue.

###  Borůvka’s Algorithm
- **How it Works:** Every connected component chooses its cheapest edge to connect to another component, repeating until one component remains.
- **Best For:** Parallelization and large‑scale graphs.
- **Complexity:** `O(E log V)`

###  Reverse‑Delete Algorithm
- **How it Works:** Begin with all edges in the graph, then remove the heaviest edge if it doesn’t disconnect the graph.
- **Best For:** Understanding critical connections within dense collaboration graphs.
- **Complexity:** `O(E log E)`

###  Karger’s Algorithm (Minimum Cut)
- **How it Works:** Randomly contract edges until only two nodes remain, yielding a minimum cut. Not an MST algorithm, but related for understanding connectivity bottlenecks.
- **Best For:** Identifying the weakest connections between groups within a collaborative network.
- **Complexity:** `O(EV²)` (basic version)

---
