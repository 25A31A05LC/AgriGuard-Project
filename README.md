🌾 AgriGuard – Crop Disease Quarantine Zone Management System

Analyze Connections. Identify Critical Farms. Plan Smarter Quarantine Zones.

AgriGuard is a console-based C++ mini-project developed using Advanced Data Structures and Algorithm Analysis (ADS & AA) concepts. It models farms as vertices and possible disease-transmission or vector-contact pathways as edges in an undirected graph.

The system analyzes farm connectivity, identifies critical farms, and helps determine potential quarantine zones using graph traversal and connectivity algorithms.

---

👥 Team Members

S. No.| Name| Role
1| G. Malleswari| Team Leader
2| P. Bhuvana Sri| Team Member
3| S. L. S. Venkаt Reddy| Team Member

---

🎯 Project Objectives

- Represent farms and their possible contact pathways using graph data structures.
- Identify connected groups of farms using BFS and DFS.
- Detect critical farms whose removal can disconnect the network.
- Identify biconnected components to understand network vulnerability.
- Rank farms based on their impact on network connectivity.
- Simulate quarantine by temporarily removing a selected farm.
- Support dynamic addition and removal of connections.

✨ Key Features

1. Graph Representation: Farms are represented as vertices, and contact pathways are represented as undirected edges.
2. Dynamic Network Management: Add or remove connections between farms.
3. BFS Traversal: Identify connected components and potential quarantine zones.
4. DFS Traversal: Explore the farm network and identify connected groups.
5. Articulation Point Detection: Find critical farms whose removal increases the number of connected components.
6. Biconnected Components: Identify groups of farms that remain connected through alternative paths.
7. Critical Farm Ranking: Rank farms according to their impact on network connectivity.
8. Quarantine Simulation: Analyze the network after excluding a selected farm.
9. Sample Network Testing: Test chain, star, and cyclic network structures.
10. Complexity Analysis: Demonstrate the time and space complexity of the implemented graph algorithms.

🧠 Data Structures and Algorithms Used

Concept| Application
Graph| Represents the farm network
Adjacency List| Stores connections between farms
Vector| Stores graph-related information
Set| Maintains unique farm connections
Queue| Used in BFS traversal
Stack| Used in Biconnected Components
BFS| Finds connected components
DFS| Explores graph connectivity
Tarjan's Algorithm| Detects articulation points
Biconnected Components| Identifies network blocks

🛠️ Technology Stack

- Programming Language: C++
- Standard: C++11 or later
- IDE: Dev-C++, Code::Blocks, or Visual Studio Code
- Compiler: GCC / MinGW
- External Libraries: None

⚙️ Installation and Execution

Step 1: Clone the Repository

git clone https://github.com/YOUR-USERNAME/AgriGuard.git

Step 2: Open the Project

Open the "AgriGuard.cpp" file using Dev-C++, Code::Blocks, or Visual Studio Code.

Step 3: Compile the Program

Using GCC:

g++ -std=c++11 AgriGuard.cpp -o AgriGuard

Step 4: Run the Program

On Windows:

AgriGuard.exe

On Linux:

./AgriGuard

🧪 Test Scenarios

The project supports three sample graph structures:

Test Network| Structure| Expected Analysis
Chain Network| Farms connected in a sequence| Identifies intermediate critical farms
Star Network| One central farm connected to multiple farms| Identifies the central farm as critical
Cyclic Network| Farms connected in a closed loop| Demonstrates alternative connection paths

📊 Algorithm Complexity

Algorithm| Time Complexity| Space Complexity
BFS| O(V + E)| O(V)
DFS| O(V + E)| O(V)
Articulation Point Detection| O(V + E)| O(V)
Biconnected Components| O(V + E)| O(V + E)
Critical Farm Ranking| O(V(V + E) + V log V)| O(V)
Quarantine Simulation| O(V + E)| O(V)

Here:

- V = Number of farms (vertices).
- E = Number of contact pathways (edges).

🌱 Real-World Application

AgriGuard demonstrates how graph algorithms can support agricultural network analysis.

For example, when a disease is reported on a farm, the system can:

- Identify other farms connected through possible contact pathways.
- Divide the network into connected groups.
- Identify farms that act as critical connection points.
- Simulate the effect of isolating a selected farm.
- Help prioritize farms for further investigation and preventive planning.

Note: AgriGuard is an educational graph-analysis prototype. It identifies structural connectivity and potential quarantine zones; it does not predict disease infection, transmission probability, or actual outbreak risk.

📁 Project Structure

AgriGuard/
│
├── AgriGuard.cpp
├── README.md
├── IDEOLOGY.md
├── ALGORITHM.md
├── REQUIREMENTS.md
│
├── screenshots/
│
└── test_cases/
    └── network_test_cases.md

🚀 Future Enhancements

- Weighted connections based on geographical distance.
- Risk-based farm prioritization.
- File handling for saving and loading farm networks.
- Graph visualization using a graphical interface.
- Integration with geographical mapping systems.
- Advanced agricultural disease-spread models.

🎓 Academic Relevance

This project demonstrates practical implementation of concepts from Advanced Data Structures and Algorithm Analysis (ADS & AA), including:

- Graph representation and traversal.
- Breadth-First Search (BFS).
- Depth-First Search (DFS).
- Articulation points.
- Biconnected components.
- Time and space complexity analysis.
- Dynamic graph operations.

🤝 Team Contribution

This project was developed collaboratively by the team as part of an academic mini-project to apply graph algorithms to a real-world-inspired agricultural problem.

📜 License

This project is developed for academic and educational purposes.

---

AgriGuard – Analyze Connections. Identify Critical Farms. Plan Smarter Quarantine Zones. 🌾
