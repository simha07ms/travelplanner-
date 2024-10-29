# travelplanner-

# Travel Planner Project

A Python-based travel planner project that uses *Dijkstra's algorithm* to find the most efficient travel routes between cities. This project generates an HTML output file displaying the optimal travel route, making it useful for users seeking efficient route suggestions based on route distances.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Dependencies](#dependencies)
7. [Future Enhancements](#future-enhancements)


---

### Project Overview
The Travel Planner project allows users to input start and destination locations, calculates the shortest path based on distances in the database, and generates an HTML file to display the results.

### Features
- Calculates shortest routes using Dijkstra's algorithm
- Outputs results in an HTML file (output.html) for easy access

### Project Structure
This project is organized into several files for modularity:

- *main.py*: Entry point of the application.
- *fileop.py*: Reads and processes input files containing route and city data.
- *graph.py*: Implements Dijkstra's algorithm for shortest-path calculations.
- *location.py*: Manages location data.
- *routes.py*: Manages route data.
- *parsing.py*: Parses data files and pre-processes information.
- *routes.csv*: Contains route data (city connections and distances).
- *cities.csv*: Contains information about cities (city names and identifiers).
- *output.html*: Displays route results in a browser.

### Installation

1. Clone the repository:
   bash
   git clone https://github.com/username/travel-planner.git
   
2. Navigate to the project directory:
   bash
   cd travel-planner
   
3. Install required Python packages:
   bash
   pip install -r requirements.txt
   

### Usage
1. Run the main.py file to start the application:
   bash
   python main.py
   
2. Input start and end locations as prompted.
3. View the optimal route and distance in the generated output.html file.

### Dependencies
- Python 3.x
- Additional libraries (listed in requirements.txt)

### Future Enhancements
- Integration with a map API for a dynamic map-based visualization
- Improved output format for mobile compatibility
