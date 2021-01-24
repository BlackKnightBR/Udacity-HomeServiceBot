# Udacity-HomeServiceBot
*Udacity's Robotics Software Engineer last project.*

### Bomb disposal home bot:

The objective: this project is the exemplification of some the concepts learned throughout the course "Robotics Software Engineer", these concepts involve, localization, mapping and navigation.

##### How to:
  *First create you catkin_ws, src and init the catkin workspace*
  
  ##### Resources:
  > Clone this repo and paste all the content inside your own catkin_ws/src
  >> https://github.com/BlackKnightBR/Udacity-HomeServiceBot.git
  
  > ### Also clone these repos:
  >> ##### https://github.com/turtlebot/turtlebot.git

 >> ##### https://github.com/turtlebot/turtlebot_interactions.git 

 >> ##### https://github.com/turtlebot/turtlebot_simulator.git
 
 *important: remove the turtlebot_gazebo from "turtlebot_simulator pkg"
 
##### Execution:
 > Do "catkin_make" at catkin_ws
 >> and source devel/setup.bash
 > Navigate to the scripts folder inside src, give exe permission to home_service.sh
 >>> chmod +x home_service.sh
 >>>> *./home_service.sh*
 >>>>> Watch the little bot retriev a bomb and take it to a safe zone outside the house.

## Slam test:

![My large image](_images/testSlam.png)

## Localization and Navigation:

![My large image](_images/Navigation.png)

## Pick Objects

![My large image](_images/pickObjects.png)

## Add Markers

![My large image](_images/addMarkers.png)

## Bomb disposal bot!

![My large image](_images/homeService.png)
![My large image](_images/homeServiceGoing.png)
![My large image](_images/homeServiceDone.png)


### References:
> Ross Wiki:
>> #### http://wiki.ros.org/catkin/CMakeLists.txt
>> #### http://wiki.ros.org/rviz/Tutorials/Markers%3A%20Basic%20Shapes
#### Udacity and peer repos: 
> Reference list:
>> #### udacity(https://github.com/udacity/RoboND-simple_arm) 
>> #### cosa2(https://github.com/csosa27/RoboND-HomeServiceBot)
>> #### dhavenm(https://github.com/dehavenm/Udacity-Home-Service-Robot/tree/master/catkin_ws/src)
