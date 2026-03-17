# Lung Cancer Segmentation using Deep Learning
Final Project - Machine Learning in Medicine

This repository contains the full code and report for an automated framework designed to detect and segment lung nodules from Computed Tomography (CT) images, specifically supporting Lung-RADS clinical assessments.

---

## Team Members (Group 4)
* Doan Duy Thanh
* Le Viet Hoang Lam
* Chau Tuan Minh
* Hoang Nguyen Tuan Nghia
* Nguyen Minh Dat
* Duong Tuan Kiet

Lecturer:Tran Giang Son

---

## Project Overview
The primary goal of this project is to support radiologists by providing high-precision localization of pulmonary nodules. The system evaluates two distinct deep learning approaches:

* Mask R-CNN: A two-stage architecture that adds a mask prediction branch to provide precise pixel-wise segmentation.
* YOLO (v8 & 26): Single-stage detectors optimized for high inference speed and efficient clinical screening.

---

## Experimental Results

The following table summarizes the comparative performance of the YOLO architectures:

| Metric | YOLOv8 | YOLO26 |
| :--- | :---: | :---: |
| Best Epoch | 13 | 32 |
| Precision | 0.574 | 0.734 |
| Recall | 0.623 | 0.549 |
| mAP50 | 0.612 | 0.613 |

The Mask R-CNN model achieved the following segmentation performance:
* Recall: 0.56
* mAP@0.50: 0.33
* Dice Score: 0.22
* IoU: 0.16

---

## Resources
* Full Report: [Report_G4.pdf](./Report_G4.pdf)
* Full code and report (Google Drive): [Link to Drive](https://drive.google.com/drive/u/2/folders/1_LgTJsR1SbFWsIUyCqKOzIoQ1PMWCcTj)

---
University of Science and Technology of Hanoi (USTH)