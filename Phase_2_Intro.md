PHASE 2 – CHEAT SHEET (ROS 2 Installation)
Phase 2: ROS 2 Humble Installation

1. Key Concept: Sourcing

ROS 2 is installed in /opt/ros/humble.

Linux doesn't know it exists until you run source.

Command: source /opt/ros/humble/setup.bash

Permanent Fix: Add that line to ~/.bashrc.

2. The Installation Command

sudo apt install ros-humble-desktop: Installs core ROS, simulation tools, and demos.

sudo apt install ros-dev-tools: Installs build tools (colcon).

3. Testing (The "Hello World")

Talker: ros2 run demo_nodes_cpp talker

Listener: ros2 run demo_nodes_py listener

Success: If Listener prints "I heard: [Hello World]", ROS is working.
