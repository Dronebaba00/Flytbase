# Flytbase
FlytSim Navigation APIs

Problem Statement:

Build a demo app (using C++/Python FlytAPIs) to make the drone takeoff at 5m, move in a square trajectory of side length 6.5m at height 5m and land once the entire mission is over. Demonstrate the app and fly the drone in the FlytSIM simulator.

File arrangement: Python code: test.py  CPP code: first.cpp

OS: Linux Ubuntu 16.04 

Simualtion config used: FlytSim in its default configuration runs a headless (no-GUI) APM-SITL. It is computationally light weight and should suit most of your simulation requirements. If your use-case doesn’t need a 3D Gazebo based GUI, please continue to Intel GPU section and don’t pay heed to any warning.

About FlytSim: FlytSim offers SITL (Software In The Loop) simulation environment for testing user apps without the drone hardware. FlytSim simulates the drone and its world, programmatically generating the state variables, while the control algorithms applied are same as onboard the drone. The FlytAPIs are also available in FlytSim and thus the user apps built with these APIs can be tested on any computer running FlytSim.

Helpful links:
Demonstrate the app and fly the drone in the- https://docs.flytbase.com/flytsim/flytsim-docker
FlytBase Documentation: https://docs.flytbase.com/
Demo app creation: https://docs.flytbase.com/flytos/developers/building-custom-apps/onboard-apps/onboard-python
