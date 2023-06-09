# UR3e Gripper Humble Moveit2

This repository provides a the moveit_config to control a UR3e robot using Moveit2. The container includes Isaac Sim simulation for testing purposes.

## Getting Started

To get started with this repository, follow these steps:

1. Clone this repository to your local machine.
````
git clone https://github.com/MetaToolEU/ur3e_gripper_humble_moveit2.git
````
3. Install Docker and Docker Compose if you haven't already.
4. Open a terminal in the project directory and run the following command to build the Docker container:

````docker compose build````

4. After the build process is complete, run the following command to start the container:

````docker compose up demo_isaac````

6. In RVIZ, you should see a visualization of the UR3e robot. You can control the robot using Moveit2.
7. Locate the usd files in your localhost Nucleus environment under the folder ````name ur3e_gripper_humble_moveit2-humble````

<p align="center">
  <img src="https://github.com/DarK404/UR_Isaac-sim/assets/28174056/66bb133d-3a37-4419-91a9-1cd2c9408f52" />
</p>

<p align="center">
  <img src="https://github.com/DarK404/UR_Isaac-sim/assets/28174056/513c5123-4fbd-4795-b3e9-099a2ef0ba4a" />
</p>

<p align="center">
  <img src="https://github.com/DarK404/UR_Isaac-sim/assets/28174056/ea1f0509-01dc-42cf-bc4f-51783011f0ab" />
</p>
