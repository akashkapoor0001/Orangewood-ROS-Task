# Orangewood ROS Task

This repository contains the code and setup for the **Orangewood ROS Task**. The task involves creating a solution using ROS (Robot Operating System) to perform a specific objective. The objective is to design a robot's motion to execute a specific path or behavior, simulating real-world tasks.

## Objective

The goal of this task is to simulate and control the movement of a turtle in a rectangular pattern using ROS, Python, and various ROS libraries. The task involves publishing velocity messages to control the turtle's movement, creating a specific path (rectangle), and stopping the turtle once the rectangle is completed.

## Installation and Setup

### Prerequisites

- **ROS (Robot Operating System)** installed on your machine.
- Python 3.x
- ROS workspace set up and sourced (`~/ros_ws` or equivalent).
- Ubuntu 18.04 or newer.

### Install ROS and Dependencies

1. First, install the required ROS packages:
    ```bash
    sudo apt update
    sudo apt install ros-melodic-ros-tutorials
    sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential
    ```

2. Initialize rosdep:
    ```bash
    sudo rosdep init
    rosdep update
    ```

3. Set up your workspace if you haven't already:
    ```bash
    mkdir -p ~/ros_ws/src
    cd ~/ros_ws/
    catkin_make
    source devel/setup.bash
    ```

### Clone the Repository

Clone this repository into your `~/ros_ws/src` directory:
```bash
cd ~/ros_ws/src
git clone https://github.com/akashkapoor0001/Orangewood-ROS-Task.git
cd ~/ros_ws
catkin_make
