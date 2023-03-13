# Computer Vision - Assignment#1 - MSDS

## Abstract:
This research paper aims to investigate the performance of BoVW and other feature detectors, namely SIFT, FAST, ORB, and BRIEF, in image classification. The study involves performing image classification on two datasets using these feature detectors and training two classifiers, namely SVM and Random Forest, using OpenCV or sklearn libraries. The paper presents the results obtained after conducting experiments with various parameters, and compares the performance of both classifiers. The study aims to evaluate the effectiveness of BoVW and feature detectors in image classification, and provide insights into their strengths and weaknesses. The research findings will help in identifying the most suitable feature detector and classifier for image classification, depending on the nature of the dataset. The study also highlights the importance of selecting appropriate parameters for achieving optimal performance in image classification. Overall, this research contributes to the field of computer vision by providing a comprehensive evaluation of different feature detectors and classifiers in image classification.

## Introduction:
Image classification is a crucial task in computer vision, with various applications ranging from object recognition to scene understanding. The task involves identifying the object or scene depicted in an image and assigning a label to it. Numerous techniques have been developed for image classification, including deep learning-based methods such as Convolutional Neural Networks (CNNs) and traditional methods such as Bag-of-Visual-Words (BoVW) and feature detectors like Scale-Invariant Feature Transform (SIFT), Features from Accelerated Segment Test (FAST), Oriented FAST and Rotated BRIEF (ORB), and Binary Robust Independent Elementary Features (BRIEF).

## Results:
![image](/Results/Results.PNG)

## Instructions For Running Train Scripts:
Open `Assignment1_SyedSaadUllahShah_400202_CV_MSDS.ipynb` in google colab and run each block in sequential order.

## Instructions For Running Test Scripts Locally:

- After cloning this repository, Create Conda environment with python=3.8 i.e. `conda create --name cv_assignment1 python=3.8`
- run command `pip install -r requirements.txt`
- open `Assignment1_SyedSaadUllahShah_400202_CV_MSDS_test.ipynb` in jupyter notebook using command `jupyter notebook` and run each cell in sequential order

