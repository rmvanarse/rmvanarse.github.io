---
title: "Visual-Inertial SLAM for AUVs"
excerpt: "Improving VIO/SLAM for underwater robots through transmission-based image enhancement"
header:
  teaser: /assets/images/projects/thesis_dp.png
gallery:
  - url: /assets/images/projects/thesis_reef.png
    image_path: /assets/images/projects/thesis_reef.png
    alt: "placeholder image 1"
  - url: /assets/images/projects/thesis_all_cave.png
    image_path: /assets/images/projects/thesis_all_cave.png
    alt: "placeholder image 2"

---
Underwater visual odometry poses several challenges due to attenuation of light, reflections, suspended particles, poor features, absence of GPS, inability to use LIDARs, etc. A light-transmission based image enhancement pipeline was developed in this project to eleminate degradations in underwater visual data and improve the performance of SLAM & VIO systems with underwater robots.

The method was tested on several open source visual inerial datasets from a vareity of underwater environments, with ORB SLAM3 (and partly with ROVIO and OKVIS).

{% include gallery layout="half" caption="The first pair of images shows a reef before & after the transmission-based enhancement. The second set of images shows features tracked in a frame in an underwater cave before/after enhancement" %}

This project was done as an **Undergraduate Thesis** in Spring 2020, with the [**Autonomous Robots Lab**](https://www.autonomousrobotslab.com/) in **University of Nevada, Reno** (now in NTNU), under the guidance of [**Prof. Kostas Alexis**](http://www.kostasalexis.com/).

