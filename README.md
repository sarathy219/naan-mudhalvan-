# naan-mudhalvan-
Title: AI-Based Autonomous Vehicle Navigation System

1. Features

Autonomous vehicle pathfinding using A* algorithm.

Real-time obstacle detection and pedestrian awareness (grid simulation).

Simple chatbot interface for interaction and vehicle control.

Encrypted IoT sensor data transmission (e.g., temperature, distance).

Visual path output using matplotlib.


2. Technology Used

Language: Python 3

Libraries:

matplotlib – for grid visualization

numpy – for sensor/environment data

hashlib – for data encryption

queue.PriorityQueue – for A* algorithm


GitHub for version control


3. How It Works

1. A grid-based map is generated to simulate the vehicle’s environment.


2. The A* algorithm finds the shortest path from the start to the destination.


3. The vehicle avoids obstacles and detects pedestrians in its path.


4. A chatbot answers vehicle-related queries.


5. Sensor data (like obstacle distance, temperature) is generated and encrypted using SHA-256.


6. The final path and system actions are visualized in real-time.


4. Data Collection

Sensor data is simulated using random functions.

No real-world dataset is used. However, if required, a CSV format is available (sensor_dataset.csv).

5. Objective

To build a basic AI-based simulation of an autonomous robot that can navigate, detect, and respond intelligently using real-time data.

6. Controls

Text-based chatbot for commands:
E.g., "function", "obstacles", "security", "developer"


7. ML Techniques Used

Heuristic search: A* pathfinding (rule-based, not trained ML).

8. Model Training

No ML model training involved – algorithm is rule-based and deterministic.


9. Output Explanation

Start: Blue circle

Goal: Red circle

Path: Green dots

Obstacles: Black squares

Pedestrians:
Magenta

Encrypted Data: Printed in console/log
