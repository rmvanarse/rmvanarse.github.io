---
title: "Robot Localization using Object Tracking"
excerpt: "_Obtaining a localization prior by tracking 'Objects of Interest' in a depth map_"
header:
  teaser: /assets/images/projects/cogneuro_dp.png
gallery:
  - url: /assets/images/projects/cog1.png
    image_path: /assets/images/projects/cog1.png
    alt: "placeholder image 1"
  - url: /assets/images/projects/cog2.png
    image_path: /assets/images/projects/cog2.png
    alt: "placeholder image 2"
  - url: /assets/images/projects/cog3.png
    image_path: /assets/images/projects/cog3.png
    alt: "placeholder image 3"
---
This project attempts to model localization in robots as humans do while navigating in the real world. Humans use their semantic understanding of the environment to often track entire 'objects of interest' rather than relying only on features/keypoints (as done in most VIO/SLAM methods).

The focus of this project was exploring a new method based on navigation in humans, and not on developing a robust localization system. A calibrated Kinect was used for obtaining a depth map and a monochrome image. Objects of interest were detected in the images using YOLOv3 and their approximate 3D location is estimated. These objects were then tracked through the frames (without the use of features), to obtain a localization prior.

{% include gallery caption="The images above show the YOLOv3 output registered onto the depth map, on a cropped portion of the scene, as the robot moves progressively. The scene is ideally cluttered with many more objects" %}

This project was done as a part of the **Cognitive Neuroscience** course in BITS Goa in Fall 2019, with the aim of incorporating ideas from the brain's navigation methods in robotics.


\[[**GitHub Repo**](https://github.com/rmvanarse/slam_cogneuro)\]
