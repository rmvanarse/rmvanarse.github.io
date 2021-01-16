---
title: "Multispectral Image Registration"
excerpt: "_Alignment of drone images taken from multiple spectral cameras for precision agriculture applications_"
header:
  teaser: /assets/images/projects/farm.png
gallery:
  - url: /assets/images/projects/imgR.png
    image_path: /assets/images/projects/imgR.png
    alt: "placeholder image 1"
  - url: /assets/images/projects/imgIR.png
    image_path: /assets/images/projects/imgIR.png
    alt: "placeholder image 2"
  - url: /assets/images/projects/imgRGIR.png
    image_path: /assets/images/projects/imgRGIR.png
    alt: "placeholder image 3"
---
<sub>Precision agriculture often require images from different spectra in infrared & visual for gaining nutritional information about the crop. In this project, multispectral images of a field were taken by flying a drone over the field. A method for alignment of images from different spectra was developed.</sub>

<sub>Infrared images differ significantly from visual-spectrum images (in terms of texture, intensity gradients, etc), so standard feature-based computer vision methods cannot be used. The project used an iterative method for maximising 'Mattes Mutual Information' between visual and infrared images,  for multi-channel registration. Additionally a method for estimating a prior transform between channels was developed, to move towards real-time performance.</sub>

{% include gallery caption="**Image 1:** Red-edge channel; **Image 2:** Near-IR channel; **Image 3:** Registered R-G-NIR image" %}

<sub>This project was done in July 2020  as a short, month-long project with the [**Autonomous Robots Lab**](https://www.autonomousrobotslab.com/) (**University of Nevada, Reno**), under [**Prof Kostas Alexis**](http://www.kostasalexis.com/).</sub>

<sub></sub>

