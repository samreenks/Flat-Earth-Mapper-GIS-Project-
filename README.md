# Flat Earth Mapper (GIS Project)
An interactive GIS (Geographic Information System)/mapping software that displays maps and mapping information (such as street names, points of interests, and path-finding/directions) for different cities around the world. The final product is very similar to Google Maps. 

Tools used: 
- C++
- EZGL Library
- GTK and Glade
- OpenStreetMap API

Collaborators: Vicky Xu and Mihika Bahadur

This project was created for ECE297, the Software Design and Communication course at the University of Toronto. The source code cannot be shared, so a detailed description of the project and important features is outlined below. 

**Final course mark: 90% (4.0 GPA)**

<img src="/images/MAINProject.png" width="600" /> 

## Important Features

### 1. User Interface 

<img src="/images/UserInterface.png" width="600" /> 

### 2. Dark Mode
Light Mode                                               | Dark Mode
:------------------------------------------------------:|:---------------------------------:
<img src="/images/lightmode.png" width="300" />          | <img src="/images/darkmode.png" width="300" />

### 3. Info Button
- Used to help navigate the map

<img src="/images/info button.png" width="600" />    

### 4. Highlighting Intersections
- Click on intersections to view the intersection names
- Can also search for intersections using search bar

<img src="/images/highlightintersections.png" width="600" />    

### 5. Point of Interests
- Users can select which POIs they would like to see
- To avoid cluttering, colour coded POI pins are used
- When zooming in, POI symbols and names are shown

<img src="/images/pois.gif" width="600" />   

### 6. Level of Detail Modeling
- More detail will be shown as you zoom in 

Zoom Level 1                                               | Zoom Level 8
:------------------------------------------------------:|:---------------------------------:
<img src="/images/level1zoom.png" width="200" />          | <img src="/images/level2zoom.png" width="200" />
Major intersections, highways, major bodies of water and large parks, no street names, no buildings | Smaller intersections, smaller parks and smaller bodies of water, buildings, street names are visible

### 7. Searching + Autocomplete
- Search bar has autocomplete feature to find street names (street gets high-lighted) 
<img src="/images/searchbarautocomplete.gif" width="300" />   

- Search bar can find intersections using an ‘&’ between street names
<img src="/images/intersectionautocomplete.gif" width="300" />   

- Can load different cities by toggling the Load Maps search option
<img src="/images/loadmaps.gif" width="300" />   

### 8. Path Finding / Directions between two locations
- Users can select the Find Directions search option
- Used Dijkstra’s and A* algorithms
- Path shows up visually on map, and in written form
<img src="/images/directions.gif" width="600" />   

### 9. Subway
- Can press Subway button to toggle the cities’ subway transit system 

## Notable Algorithms
Path Finding: 
- Dijkstra
- A* Heuristic

Traveling Courier Problem: A variation of the traveling salesman problem
- Greedy 
- Iterative 2-opt
- Simulated Annealing
- Genetic

<img src="/images/algorithmcomparison.gif" width="600" />   

Please view the [Final Presentation](https://docs.google.com/presentation/d/11WJMvbJV8ZbVeGpBRn7vFChItOBLK3KEiFzHdZBCNNg/edit?usp=sharing) for more information. 
