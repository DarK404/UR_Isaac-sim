# UR_Isaac-sim

This repository provides a moveit_config to control a UR3e robot using Moveit2. The container includes Isaac Sim simulation for testing purposes.

## Getting Started

To get started with this repository, follow these steps:

1. Clone this repository to your local machine.
````
git clone https://github.com/DarK404/moveit2_tutorials
````
3. Install Docker and Docker Compose if you haven't already.
4. Open a terminal in the project directory and run the following command to build the Docker container:

````
cd moveit2_tutorials/doc/how_to_guides/isaac_panda
docker compose build
````

5. Git clone ````https://github.com/DarK404/UR_Isaac-sim/tree/main ```` and Locate the usd files in your localhost Nucleus environment under the folder name ````ur3e_gripper_humble_moveit2-humble````.


    <img src="https://github.com/DarK404/UR_Isaac-sim/assets/28174056/66bb133d-3a37-4419-91a9-1cd2c9408f52" />
6. Launch Isaac-sim inside the launch directory
 ````
 cd moveit2_tutorials/doc/how_to_guides/isaac_panda/launch
 ./python.sh isaac_moveit_Hackathon.py
 ````
10. After the build process is complete, run the following command to start the container:

````
docker compose up demo_isaac
````

8. In RVIZ, you should see a visualization of the UR3e robot. You can control the robot using Moveit2.

<p align="center">
  <img src="https://github.com/DarK404/UR_Isaac-sim/assets/28174056/513c5123-4fbd-4795-b3e9-099a2ef0ba4a" />
</p>
<p align="center">1.RVIZ visualization</p>

<p align="center">
  <img src="https://github.com/DarK404/UR_Isaac-sim/assets/28174056/ea1f0509-01dc-42cf-bc4f-51783011f0ab" alt="Material Bread logo" />
</p>

<p align="center">2.Isaac Sim visualization</p>
