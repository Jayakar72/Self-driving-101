<div align="center">
<h1> Self-driving-101 </h1>
<h4> <i>This is a capstone project made for tutorials of self-driving 101 in simulation for the freshmen - OOPS(python) &amp; Deep Learning </i></h4>

<image src="simulation.png" width="700">

# About Carla-sim
CARLA has been developed from the ground up to support development, training, and validation of autonomous driving systems. In addition to open-source code and protocols, CARLA provides open digital assets (urban layouts, buildings, vehicles) that were created for this purpose and can be used freely. The simulation platform supports flexible specification of sensor suites, environmental conditions, full control of all static and dynamic actors, maps generation and much more. We use Carla-Sim for training and testing home-developed self-driving logics.

You can learn more about the carla-sim and its use cases here (please make sure to download Carla-Sim's latest version) - [here](https://carla.org/), you can see more tutorials here for understanding the usecases - [here](https://carla.readthedocs.io/en/latest/tutorials/).

# Getting started 
Follow the instructions in the Jupyter notebook 
1. When starting the code or the logic of the waypoint collection, make sure to open the Carla sim in another window to make sure your code is reading the simulation input.
2. We first have an interactive car simulation , where we can drive the car around the desired map, you can change the map 
Follow the steps in the `ipynb file`:
```
Collecting_waypoints.ipynb
```
Make sure the code can detect the Carla in your local host
```
carla.Client('localhost', 2000)
```
