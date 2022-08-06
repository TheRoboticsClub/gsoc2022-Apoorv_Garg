---
layout: single
permalink : /CPW5/
title:  "Coding Period - Week 5"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
With the First exercise migrated to React based code, we discussed the next steps for the week and decided to proceed with the next exercise that will consists of 3d widgets, so we landed on the 3d-reconstruction exercise. There were one more concern "How exercise developer can use the components easily ?". David Maria Arribas came up with the solution that will help exercise developers to resuse componenets in a convenient way.

### Goals

- [x] Integrate the React based code with the new solution 

- [x] Discover new 3d-widgets to build 3d reconstruction exercise 

- [x] Create a documentation to guide developers 
 

### Accomplishment and Challenges 

* #### Integrate the React based code \[Task 1\]

Follow line exercise code being refractored in react was not the only main requirement of the project, But for the exercise developers to carry the legacy in the different exercises in react and avoid any sort of hardship in reusing the react based widgets that are common for the exercises.
To reuse the widgets, exercise developers needs to make a template html and then add tags and resue the component by adding it in similar fashion as using normal django custom template tags. 

* #### Discover new 3d-widgets to build 3d reconstruction exercise \[Task 2\]

Now to start the refractoring of the next most interesting exercise "3d-reconstruction", the first task was to find the correct library to meet the requirements to build 3d-widgets. So I started my research with the keeping in the requirements. In my research, I found two libraries that met the requirements : Three.js and Worldview

| Three.js | worldview | 
|-------|--------|
| Three.js is a 3D library that tries to make it as easy as possible to get 3d content on a webpage| Worldview is a library to render 3D objects in a scene, manage the camera, and add mouse interactions |
| Three.js handles scenes, light, shadows, materials, textures, 3d math and all other great things that is achievable with 3d objects| Worldview is restrcited to limited features |
| Three.js has a bigger Open source community | Worldview has comparatively smaller community |
| Tutorials on three.js are easily available | Worldview tutorials aren't that easily available |

* #### Documentation guiding developers on "How to create react based exercise from Scratch" \[Task 3\]

With the first exercise refractor completion, There was react base template code available for the exercise developer to begin creating exercises from scratch, but just going deep into 20,000 line of code won't help exercise developer help build a exercise quickly and efficiently. Documentation was required to ensure easy integration and effectiveness of the process.

### Pull Request and Issues

* #### Issues

1. [https://github.com/JdeRobot/RoboticsAcademy/issues/1774](https://github.com/JdeRobot/RoboticsAcademy/issues/1774)

2. [https://github.com/JdeRobot/RoboticsAcademy/issues/1775](https://github.com/JdeRobot/RoboticsAcademy/issues/1775)