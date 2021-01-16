---
title: "Automatic Signature Verification"
excerpt: "A Siamese Neural Network for distinguishing between authentic & forged signatures"
header:
  teaser: /assets/images/projects/ps1_dp.png
gallery:
  - url: /assets/images/projects/ps1_dp.png
    image_path: /assets/images/projects/ps1_dp.png
    alt: "placeholder image 1"

---
<sub>Signature verification involves distinguishing between authentic signatures and forgeries. Inspired from facial recognition networks, a one-shot learning convolutional neural network was designed to detect forgeries of a given signature.</sub>

<sub>A Siamese architecture was developed using PyTorch and was trained using triplet loss. A dataset containing several authentic signatures & forged signatures of around 3000 people was used. The final network converts the input signatures to a lower-dimensional embedding vector for comparison. It is able to identify forgeries even with only one or two true signatures for reference.</sub>

{% include gallery caption="**Training:** Training the Siamese architecture using triplet loss, using a pivot image, true image and false image as inputs." %}

<sub>This project was done in Summer 2019 as an internship project (as a requirement of the 'Practice School' programme of BITS Goa) for Bank of Maharashtra.</sub>


<sub>\[[**GitHub**](http://github.com/rmvanarse/ps1_project)\]</sub>
