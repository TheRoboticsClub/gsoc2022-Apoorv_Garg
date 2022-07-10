---
layout: single
permalink : /CBW2/
title:  "Community Bonding - Week 2"
categories: jekyll update
toc_label: Table of Content
toc: true
sidebar:
  nav: "docs"
  
feature_row:
  - image_path: /assets/images/exercise-lasmap.png
    alt: "Exercise"
    title: "Laser Mapping"
    excerpt: "Exploring Laser mapping exercise"
  

  - image_path: /assets/images/exercise-obsavoid.png
    alt: "Exercise"
    title: "Obstacle Avoidance"
    excerpt: "Exploring Obstacle avoidance exercise"
    

  - image_path: /assets/images/exercise-vaccl.png
    alt: "Exercise"
    title: "Vacuum Cleaner"
    excerpt: "Exploring Vacuum cleaner exercise "
---
I had my first videoconference with my mentors, during which they welcomed me to the community, outlined the plans for weekly meetings, and provided me with additional information on the project.



### Goals

- [x] To find out more about new widgets such as worldview, robot web tools, and rosboard etc.

- [x] How to include an external javascript library to react ?

- [x] Identify the basic and frequent components of the Robot Academy exercises.


### Accomplishment and Challenges 



* #### Explore Widgets \[Task 1\]
  The main objective of the task is to figure out the usage of such tools and how can the Robot Academy accommodates these tools.  
    - [Robot web tools](http://robotwebtools.org) : Robot web tools is a collection of open-source libraries and tools for building web-based robot apps with ROS. I explored about various libraries, tools and ros nodes.
        - [ros2djs](https://github.com/RobotWebTools/ros2djs) - It is a standard Javascript 2D visualization manager for ROS. I read about the [tutorial](https://wiki.ros.org/ros2djs/Tutorials/VisualizingAMap) where ros2djs was used to visualiza a map.

        - [ros3djs](https://github.com/RobotWebTools/ros3djs) - It is a standard Javascript 3D visualization manager for ROS. I read about the [tutorial](https://wiki.ros.org/ros3djs/Tutorials/VisualizingAMap) where ros2djs was used to visualiza a map.

        - [rosbridge](https://github.com/RobotWebTools/rosbridge_suite) - It is a JSON interface to ROS that allows any client to post or subscribe to ROS topics, call ROS services, and more.
    
    - [Worldview](https://webviz.io/worldview/#/) : Worldview is a React library for rendering 2D and 3D scenes using regl. Worldview is a powerful tool helps in rendering 3d objects in a scene, manage the camera, and add mouse interactions. Explored some [basics examples](https://webviz.io/worldview/#/docs/examples/basic-example) to get more comfortable with worldview and read about the API on Worldview, Camera, Commands and Mouse events.

    - [Rosboard](https://github.com/dheera/rosboard) : ROS Node that runs a web server on your robot. This tool gives nice visaulizations. It is light weight and Easily extensible. It is developed on custom tornado-based websocket bridge.
  
    - [Foxglove studio](https://foxglove.dev/studio) : Foxglove Studio is an integrated visualization and diagnosis tool for robotics. This tool provides interactive charts, and 3d visualizations, to camera iamges and diagnostics feeds. A Docker image is provided to make self-hosting easy.

    ```shell
    $ docker run --rm -p "8080:8080" ghcr.io/foxglove/studio:latest
    ```



* #### Including External javascript Library into react \[Task 2\]
  I found an [article](https://www.geeksforgeeks.org/how-to-include-an-external-javascript-library-to-reactjs/) which helped me understanding how it could be achieved. Three Approaches are discussed in the article. These are-
  
  - Using react-script-tag Package.
  - Using react-helmet Package.
  - Using JavaScript DOM Methods.

  I tried finding the best approach by making small examples and figured out the best approach would be **Using JavaScript DOM Methods** as it does not require to install any external package, making our application light and fast.



* #### Explore Robot Academy exercises \[Task 3\]
The objective is to find resuable and basic components in the exercises to begin with the refractoring process.
```shell
$ docker run --rm -it -p 8000:8000 -p 2303:2303 -p 1905:1905 -p 8765:8765 -p 6080:6080 -p 1108:1108 jderobot/robotics-academy
```
**Common Components -**
  1. Navigation Bar
  2. Ace editor
  3. Gazebo (simulation) <br/>
  4. Console 



{% include feature_row %}






