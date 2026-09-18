# ida_teknofestparkur1
# TEKNOFEST USV (Unmanned Surface Vehicle) - Parkur 1 Simulation

This repository contains the Parkur 1 simulation environment and vehicle models developed for the TEKNOFEST Unmanned Surface Vehicle (USV) competition. The project is built using ROS (Robot Operating System) and Gazebo infrastructure.

## 📹 Project Media & Simulation Videos:

https://github.com/user-attachments/assets/417e47ca-a608-45ed-aa99-b61fc2692316

https://github.com/user-attachments/assets/116d3f96-541d-42ea-bf8e-0e879e086702

## 📂 Repository Structure

The project root directory is structured according to standard ROS package guidelines:

```text
ida_teknofestparkur1/
├── govde/          # USV hull and body XACRO models
├── yuzeyi/         # STL mesh files and surface-related models
├── worlds/         # Gazebo world files and configurations
├── urdf/           # URDF definitions
├── src/            # ROS package source files
├── CMakeLists.txt  # ROS package build configuration
└── package.xml     # ROS package metadata and dependencies
govde/: Contains XACRO model definitions for the USV hull.

yuzeyi/: Houses STL mesh files and surface models for 3D visualization and physical simulation.

worlds/: Includes Gazebo world files and configurations for the course layout.

urdf/: Holds the main URDF/XACRO definitions integrating all robot components.

src/: Contains ROS nodes and package source codes.

⚙️ Prerequisites
To run this project locally, ensure you have the following installed:

Ubuntu (e.g., 20.04 / 22.04)

ROS (Robot Operating System - Noetic / Humble, etc.)

Gazebo Simulator

🚀 Installation
Follow these steps to clone and build the project in your local catkin workspace:

Navigate to your workspace's src directory:

Bash
cd ~/catkin_ws/src
Clone the repository:

Bash
git clone [https://github.com/Elifuzunsinan/ida_teknofestparkur1.git](https://github.com/Elifuzunsinan/ida_teknofestparkur1.git)
Return to the workspace root and build the package:

Bash
cd ~/catkin_ws
catkin_make
Source your environment variables:

Bash
source devel/setup.bash
🕹️ Usage
To launch the Gazebo environment and the USV model, run the corresponding launch file:

Bash
roslaunch ida_teknofestparkur1 [your_launch_file_name.launch]
(Note: Remember to update the command with your actual launch file name.)

💡 Acknowledgement
The structuring and documentation of this project were optimized with the assistance of AI-powered tools during the development process.
