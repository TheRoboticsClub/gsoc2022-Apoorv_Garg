---
layout: single
permalink : /CBW3/
title:  "Community Bonding - Week 3"
categories: jekyll update
sidebar:
  nav: "docs"
---
As discussed in the previous meet, we scheduled to meet every Thursday and discuss the progress, findings and challenges of the project. With few days left with the community bonding period, we discussed the approches and goals of the coding period.

### Goals

- [x] Run the Robotics Academy using the **Django** Server 

- [x] Understand the [React frontend base](https://github.com/JdeRobot/RoboticsAcademy/pull/1760) for Robot academy developed by **[David Maria Arribas](https://github.com/dmariaa)**

- [x] Go through the Google Material design guidelines for the new React interface for the exercises


### Accomplishment and Challenges 

* #### Django Server \[Task 1\]

Robotics Academy can be access in two ways- 

1. Running the webserver inside the RADI

```shell
$ docker run --rm -it -p 8000:8000 -p 2303:2303 -p 1905:1905 -p 8765:8765 -p 6080:6080 -p 1108:1108 jderobot/robotics-academy 
```
2. Running the webserver outside the RADI and then connect with RADI separately

*Terminal 1*
```shell
$ python3 manage.py runserver
```
*Terminal 2*
```shell
$ docker run --rm -it -p 8000:8000 -p 2303:2303 -p 1905:1905 -p 8765:8765 -p 6080:6080 -p 1108:1108 jderobot/robotics-academy --no-server
```

* #### React frontend base for Robot academy developed by David Maria Arribas \[Task 2\]

I was confused in the beginning how django will serve React as a frontend, but on seeing the changes and going through them I learned a lot about How Django is communicating with React. 
Django uses urls.py and views.py for routing. To understand this in depth I followed the documentation on [URL dispatcher](https://docs.djangoproject.com/en/4.0/topics/http/urls/) understanding how Django processes a request.

* #### [Google Material Design Guidelines](https://material.io/design/introduction) \[Task 3\]

Material is a design system created by Google to help teams build high-quality digital experiences. Material design guidelines provides Components and themes. Material Components are interactive building blocks that include a built-in states system for communicating focus, selection, activation, error, hover, press, drag, and disabled states. Material Theming makes it easy to customize Material Design to match the look and feel of your project, with built-in support and guidance for customizing colors, typography styles, and corner shapes. Material design guidelines provides easy integration and collaborations.
