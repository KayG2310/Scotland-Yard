# Scotland-Yard

Scotland Yard Game
A digital recreation of the classic detective game Scotland Yard, featuring a graphical interface powered by Python (Pygame) and game logic implemented in C++. This project demonstrates the integration of Python and C++ using file-based communication for real-time updates.

Features
🎨 Graphical Map Interface:
Nodes represent locations on the map.
Edges denote possible paths between locations.
Dynamic player position visualization.
🕵️ Detectives vs. Mr. X:
Mr. X moves stealthily across the map.
Detectives collaborate to catch Mr. X.
🔄 Real-Time Updates:
Python and C++ interact through shared files to synchronize game state.
📂 Customizable Graph:
Easily modify the game map by updating the graph structure.
Tech Stack
1. Python (Pygame):
Responsible for:
Rendering the map, nodes, edges, and player movements.
Displaying the game's outcome.
2. C++:
Implements:
Game rules and logic.
Movement updates for Mr. X and detectives.
Winning conditions.
3. File Communication:
Shared files enable Python and C++ to exchange data seamlessly.
