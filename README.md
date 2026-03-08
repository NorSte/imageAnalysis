# Deep Learning for Image Analysis – IN3310 Mandatory Assignment 1

This repository contains the implementation for **Mandatory Assignment 1** in the course **IN3310 – Deep Learning for Image Analysis**.

## Files

- **Assignment1.py**  
  Main code file containing the training and evaluation pipeline for the assignment.

- **IN3310Mandatory1.pdf**  
  The original assignment description as provided in the course.

- **ResNet.py**  
  Implementation of the full ResNet architecture used in the assignment.

- **ResnetBlocks.py**  
  Contains the building blocks (residual blocks) that make up the ResNet architecture.

## Description

We implemented a ResNet-based model for image classification from scratch. The code includes training, validation, and result logging. For modularity, the architecture is split into two files: one for the overall network and one for the individual blocks used within the model.

---

## Status quo

This mandatory assignment was developed and trained on the **University of Oslo ML-nodes**, which are shared computing resources provided by the university IT department for machine learning and deep learning workloads.

Training was performed by SSH-ing into the ML-nodes and running the experiments directly on these machines. The dataset used in the assignment was provided through the course infrastructure and stored on the university systems. Due to its size and course distribution restrictions, the dataset is **not included in this repository**, which means the project is **not directly runnable from this repository alone**.

The purpose of this repository is therefore to document the implementation of the model architecture, training pipeline, and experimental setup used for the assignment.

To reproduce the results, access to the original dataset and a compatible compute environment (such as the UiO ML-nodes or a similar GPU-enabled machine learning environment) would be required.
