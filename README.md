﻿# High-Secured-NumberPlates-Recognition

 Automated license plate recognition is a critical 
component of modern traffic monitoring, parking management, 
and law enforcement. In this project, we present an integrated 
approach to accurately predict whether a license plate is a High
Security Registration Plate (HSRP) or not. Our system 
combines web scraping techniques, object detection using 
YOLOv3, and Convolutional Neural Networks (CNN) to 
achieve this objective. To build our dataset, we combined the 
data from OLX which we have web-scraped and popular online 
datasets available from Kaggle and GitHub. Object detection 
was performed using the YOLOv3 model, enabling us to detect 
and localize license plates within images. The model effectively 
creates bounding boxes around license plates. This step was 
crucial in segmenting license plates from the vehicle images. 
Following object detection, a CNN model was trained on the 
extracted license plate images to classify them as either HSRP 
(output label: 1) or non-HSRP (output label: 0). The CNN model 
demonstrated impressive performance in distinguishing 
between the two categories. The integrated approach 
demonstrates the feasibility of employing deep learning 
techniques in combination with web scraping for license plate 
recognition. Our model's ability to accurately distinguish 
HSRPs from non-HSRPs carries significant implications for law 
enforcement, traffic monitoring, and parking management 
systems. By presenting this project in a review paper, we hope 
to contribute to the growing field of automated license plate 
recognition, opening new avenues for improving the efficiency 
and accuracy of such systems. 
