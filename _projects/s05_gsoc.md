---
title: "Autonomous Vehicle Controller"
excerpt: "Real-time IMU-based control adaptable to any vehicle type"
header:
  teaser: /assets/images/projects/boat.png
gallery:
  - url: /assets/images/projects/osavc.png
    image_path: /assets/images/projects/osavc.png
    alt: "placeholder image 1"
  - url: /assets/images/projects/tumble_test1.jpg
    image_path: /assets/images/projects/tumble_test1.jpg
    alt: "placeholder image 2"
  - url: /assets/images/projects/tumble_test2.jpg
    image_path: /assets/images/projects/tumble_test2.jpg
    alt: "placeholder image 3"

---
The Open Source Autonomous Vehicle Controller (OSAVC) project is designed to provide a real-time hardware controller adaptable to any vehicle type —aerial, terrestrial, marine, or extraterrestrial. The controller is designed to allow development of state estimation algorithms, sensor calibration methods and vehicle control models in a modular fashion, to allow easy switching of algorithms while retaining the hardware used.

{% include gallery caption="Left: The PIC32-based controller mounted on a test platfotm. Middle and right: Tumble tests and simulated tests demonstrating elliptical structure of uncalibrated IMU data." %}

As a part of OSAVC, a novel method of real-time in-flight IMU calibration was developed. This work was funded by **Google** and was done as a part of the Google Summer of Code (GSoC) 2021 program,  with the [**Autonomous Systems Lab of University of California, Santa Cruz**](https://asl.soe.ucsc.edu/), and the [**Center for Research in Open Source Software**](https://cross.ucsc.edu/). The method used recursive least squares to continually optimize for IMU calibration parameters. The method was able to correct sudden changes in IMU calibration parameters and did not require any external mechanical setup. The work was also published in IEEE International Systems Conference in 2022.

\[[**Link to published paper**](https://ieeexplore.ieee.org/document/9773885)\]

\[[**GSoC project page**](https://summerofcode.withgoogle.com/archive/2021/projects/5949449569828864)\]

\[[**Full report**](https://drive.google.com/drive/u/2/folders/1BAXaWAtuxt6L9MFq6kdZxs5tpW7G5Jjd)\]

\[[**Symposium talk**](https://www.youtube.com/watch?v=0lqBhH3Z5kA)\]

