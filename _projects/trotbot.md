---
title: "Trotbot"
excerpt: "_An autonomous delivery robot (and a mobile ground robotics research platform) built for indoor environments_"
header:
  teaser: /assets/images/projects/trotbot_dp.jpeg
gallery:
  - url: /assets/images/projects/trotbot_quark.jpeg
    image_path: /assets/images/projects/trotbot_quark.jpeg
    alt: "placeholder image 1"
  - url: /assets/images/projects/trotbot2020.jpeg
    image_path: /assets/images/projects/trotbot2020.jpeg
    alt: "placeholder image 2"
  - url: /assets/images/projects/trotbot_dp.jpeg
    image_path: /assets/images/projects/trotbot_dp.jpeg
    alt: "placeholder image 3"
---
<sub>**Trotbot** is an autonomous omnidirectional ground robot, designed to serve as an indoor delivery robot. It is able to autonomously navigate around dynamic obstacles and find its way to a given waypoint.</sub>

<sub>The robot uses a 2D LIDAR for obstacle detection and a RealSense sensor for visual-inertial localization. The planner uses Rapidly Exploring Random Trees (RRT) for local planning and Dijkstra for global planning. The software stack for dynamic path planning has been implemented with ROS, and the processing in done on an on-board NUC.</sub>


{% include gallery caption="**Trotbot -ERC BITS Goa:** Caption..." %}

<sub>Trotbot has been an ongoing projct of the [**Electronics & Robotics Club**](https://erc-bpgc.github.io/) of BITS Goa since March 2018. The robot is now being developed to additonally serve as a platform for research in autonomous ground robotics. In 2020, the project branched out into two more projects: [omnibase](https://index.ros.org/r/omnibase/) (an omni-wheeled robot simulator) and [gennav](https://pypi.org/project/gennav/) (a python package for path planning algorithms for robots).</sub>

<sub>_**Role in  Project:** Navigation (Path Planning, Localization, Obstacle detection, dynamic obstacle avoidance)_</sub>
