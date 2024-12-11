# URDFs
This repository contains URDFs (Unified Robot Description Format) and associated files for various robotics projects. The folders are organized to support both ROS 1 and ROS 2 environments.

# Folder Structure
1) ROS_descriptions :-
   
This folder includes URDFs and necessary files for projects using ROS 1.

a) "two_wheel_drive_description" contains .xacro files, launch files, configuration and mesh files for two-wheel drive robots equiped with a 2-D lidar mount.
    
b) "four_wheel_drive_description" contains .xacro files, launch files, configuration and mesh files for four-wheel drive robots equiped with a 2-D lidar mount.
   
2) ROS2_descriptions :-
   
This folder includes URDFs and necessary files for projects using ROS 2.

a) "two_wheel_drive_description" contains .xacro files, launch files, configuration and mesh files for two-wheel drive robots equiped with a 2-D lidar mount.
    
b) "four_wheel_drive_description" contains .xacro files, launch files, configuration and mesh files for four-wheel drive robots equiped with a 2-D lidar mount.

c) "eureka_description" contains .xacro files, launch files, configuration and mesh files for 6 dof robotic arm having two fingers.

d) "perceptor_description" contains .xacro files, launch files, configuration and mesh files for two-wheel drive robots equiped with a depth-camera mount.

e) "rhino_description" contains .xacro files, launch files, configuration and mesh files for 6 dof robotic arm having two fingers.

# Contents

Each subfolder includes:

1) xacro files: XML Macro files that simplify the process of creating URDFs.
    
2) Launch files: To easily start and test the robot descriptions in a simulated environment.
    
3) Configuration files: Necessary configurations to ensure proper functioning of the robot prototypes.
    
4) Mesh files: 3D models used in the robot descriptions for visual and collision elements.
    
Along with all the dependencies required to directly use the prototypes in your projects.

# Usage
To use these URDFs in your project, follow these steps:

  1) Clone the repository to your local machine:
       ```git clone https://github.com/GradVizor/URDFs.git```

  2) Navigate to the desired folder based on your ROS version and robot type.
  3) Add the required "CMakeLists.txt" file to your package.
  
  4) Use the provided launch files to initialize the robot in your ROS environment.


