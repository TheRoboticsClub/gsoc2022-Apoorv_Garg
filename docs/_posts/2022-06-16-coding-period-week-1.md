---
layout: single
permalink : /CPW1/
title:  "Coding Period - Week 1"
categories: jekyll update
toc: true
toc_label: Table of Content
sidebar:
  nav: "docs"
---
Coding period begins, I decided to follow a strict timeline in order to complete the tasks and manage my other work. Being on meet with the mentors and disucssing the challenges with them helps a lot in getting a clear picture of what to do next, how to proceed and also the confidence that "Yes, I can do it".
### Goals

- [x] Setup the development environment

- [x] [React MUI library](https://mui.com/) to get a handfull of material design based components for React


### Accomplishment and Challenges 


* #### Setup the development environment \[Task 1\]

Setup the environment to get started with the coding period. To set up the environment, I Followed these steps:

```shell
# Clone the Repository 
$ git clone https://github.com/JdeRobot/RoboticsAcademy.git
# Create a virtual environment
$ virtualenv env
# Activate the virtual environment
$ source env/bin/activate
# Install the required package
$ pip install django django-webpack-loader  djangorestframework 
# run the development environment
$ python3 manage.py runserver
```

* #### [React MUI library](https://mui.com/) \[Task 2\]

As discussed in the weekly meet, we will follow material design guidelines to build/migrate exercises. React MUI library provides comprehensive suites of UI tools and material design with easy integration into the project and in designing smooth UI.

```shell
# Make sure that your current directory is react_frontend
$ yarn add @mui/material @emotion/react @emotion/styled
```


