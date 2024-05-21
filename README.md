## Description

A suite for training a *resnet18* model and live detection of whether someone is waving their hand or not.

## What is included

- `web_cam_capture.ipynb`: Contains a Jupyter notebook used to capture images from a webcam.
These images are then used to fine-tune the resnet18 model.

- `wave_recognition_gen.ipynb`: A Jupyter notebook for model fine-tuning.
FastAI's vision library is used for training and debugging.

- `wave_recognition_exec.ipynb`: Run this notebook to start using the model.
It accesses your webcam and begins detecting if someone is waving or not.