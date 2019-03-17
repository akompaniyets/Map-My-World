# Map My World #
#### Robotics Software Engineering ####
#### Term 2 ####
#### Project 3 ####

_Concepts/Skills Learned:_
  * Occupancy Grid Mapping: octomap, binary Bayes filter
  * SLAM: grid-based FastSLAM, graph-SLAM (w/ RTAB-Map)

---

_Project Description:_

This project continued the process of ROS interaction via a C++ interface, this time adding a mapping component to the previously achieved robot localization step. The project began by providing a fundamental understanding of the challenges of robotic mapping, discussing the concepts of occupancy grid mapping, grid-based FastSLAM, and graph-SLAM. Graph-SLAM was the mapping method chosen for this project.

Using the basic, two-wheeled robot created for the localization project, a pre-made Gazebo interior environment was mapped via the use of an attached RGB-D camera and the teleop keyboard command package. RTAB-Map was used to assist with successful mapping, particularly with loop closure.

With the provided environment successfully mapped, the challenge of mapping was extended to a more complex custom map. This map employed a wide array of unique Gazebo objects, placed in an intentionally cluttered array. The same robot and mapping model was used for this environment (using keyboard teleop commands for movement), with hyperparameters tuned to allow for superior loop closure within the larger and more complex environment.
     
   For a full report of how this was accomplished, see the included write-up: 
   
   [Map My World Write-Up](https://github.com/akompaniyets/Map-My-World/blob/master/Project%203%20Write-Up.pdf)
