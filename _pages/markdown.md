---
permalink: /projects/
title: "Projects"
author_profile: true
redirect_from: 
  - /md/
  - /projects.html
---
## Project 1: Face Mask Recognition
Wearing face masks has been proven highly effective in preventing the spread of Covid-19. Hence, face mask detection has become an emerging object detection task since the outbreak of the pandemic. However, there are few works focusing on detecting the correctness of the way masks are worn and the suitability of the choice of masks’ category. With the extensive usage of CCTV surveillance cameras, abundant image data of people wearing or not wearing masks of different categories in different manner can be collected in real time. In this project, we first collected images of people wearing different types of face masks to build our dataset, which contains 6500 images, containing of faces in 5 categories. We adopted deep-learning-based techniques to detect and classify faces in real time according to whether they are properly wearing face masks, and detailed to what type of mask is worn if one is wearing a mask in a proper manner. To be more specific, we experimented with the Faster-RCNN model with different baseline CNN structures and different ROI selection criterion, as well as the Yolov5 model, and eventually reached an mAP value of 0.975 with FPS of 109.8.  
[link](https://whuak.github.io/files/COMP5214_Report.pdf)  