---
title: Safe Navigation Through Crowded Dynamic Environments
funding: 
  - name: Amazon Research Award
    url: https://ara.amazon-ml.com/recipients/#2018
members: 
  - alkesh-srivastava
tags:
  - dynamic navigation
---

This project aims to develop a new method for navigation that will allow a robot to reactively modify a nominal path in order to avoid dynamic unmapped objects. The system is made up of four main components: Localization, Object Recognition, Multi-Target Tracker, and CNN-based Controller. The robot’s onboard sensors feed data into each of these components, the details of which can be found below. The robot will begin the task with a nominal path through the environment that avoids collisions with shelves and other static infrastructure and which comes  from applying a standard path planning algorithm in a map of the store. The robot will modify this nominal path using its sensor data and the output of the multi-target tracker to avoid collisions with unmapped obstacles to the map (e.g., customers and temporary product displays).