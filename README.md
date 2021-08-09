# Opencv Spatial AI 2021 submission for Autonomous Navigation with the OAKD camera
Repository summarizing all code repositories used for our submission to the OpenCV Spatial AI 2021 competition

## Project name
Autonomous navigation with RGB-D data for search and rescue operations using a ground robot in confined environments

## Team Name
Guará Wolves FTW (For the Win)

## Code sources
Our source code is freely available on GitHub. The links to the different code repositories are depicted below:

- Docker container with ROS and our integration of the OAK-D: 
    - https://github.com/h3ct0r/docker_oakd_ros
- Our integration of ROS with the OAK-D (our camera driver): 
    - https://github.com/h3ct0r/oakd_pcloud
- Mesh path planner integrated with ROS: 
    - https://github.com/ITVRoC/espeleo_planner
- Mesh reconstruction integrated with ROS: 
    - https://github.com/ITVRoC/espeleo_planner/tree/master/recon_surface
- RTAB-Map OAK-D integration (compatible with the `docker_oakd_ros container`):
    - https://github.com/rafaelfgs/oak_rtabmap

## Video demonstration
A video of the results of this project can be acessed in https://www.youtube.com/watch?v=Y6YkvsPTYww

![oakd_github](https://user-images.githubusercontent.com/2656938/128640037-c61afa5f-8fd4-43ab-91f5-d5018e4020f9.gif?v26)
