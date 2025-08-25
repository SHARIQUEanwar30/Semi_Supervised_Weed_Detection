# Semi_Supervised_Weed_Detection
# Introduction
This repository contains the implementation of various semi-supervised learning approaches for weed detection in sesame crop fields. The project was developed as part of the Semi-Supervised Weed Detection Challenge organized by 4i Labs, KRITI'25, IITG.

We aim to improve weed detection accuracy while minimizing the need for large labeled datasets. The challenge requires leveraging a small labeled dataset alongside a larger pool of unlabeled images to train an object detection model effectively.
# Problem Statement
The objective is to develop a weed detection model capable of identifying and localizing weeds in agricultural field images. The challenge dataset consists of:

Labeled Dataset: 200 images with YOLOv8-format annotations
Unlabeled Dataset: 1000 images without annotations
Test Dataset: 100 images with annotations
Evaluation is based on the following metric:

Metric = 0.5 * (F1-Score) + 0.5 * (mAP@[.5:.95])
