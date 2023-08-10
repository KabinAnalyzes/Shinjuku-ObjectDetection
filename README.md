# Shinjuku-ObjectDetection

## Overview
The Shibuya Crossing Pedestrian Detector is a deep learning project aimed at detecting pedestrians crossing the street at the iconic Shibuya Crossing in Tokyo. This project utilizes state-of-the-art object detection techniques to identify pedestrians in real-time footage.

The model is trained using the CrowdHuman dataset and fine-tuned using the MMdetection framework for transfer learning. The goal is to provide a reliable solution for monitoring pedestrian movement at the bustling Shibuya Crossing, aiding in traffic management and pedestrian safety.

## Features
Object Detection: The detector is capable of accurately detecting pedestrians in crowded scenes, even in challenging scenarios such as large crowds, occlusions, and varying lighting conditions.

Processing on any image or Video: The detector can be applied to any image or video provided by the user.

Customized Training: The MMdetection framework allows easy customization and fine-tuning of the detection model according to specific needs.

## Dataset
The project is built upon the CrowdHuman dataset, a large-scale benchmark dataset for crowd counting and human detection in complex scenes. The dataset contains diverse scenarios of pedestrians, making it ideal for training an effective pedestrian detector.

## Training
The model is trained using the MMdetection framework, a powerful open-source toolbox for object detection in images and videos. The transfer learning process involves taking a pre-trained model on a large dataset and fine-tuning it on our specific task using the CrowdHuman dataset.

## Usage
To use the trained model for pedestrian detection:

Clone this repository to your local machine.
Download and place the trained model weights in the appropriate directory.
Run the provided script to process real-time video footage or images.


## Demo
Check out the demo video below to see the Shibuya Crossing Pedestrian Detector in action:


https://github.com/KabinAnalyzes/Shinjuku-ObjectDetection/assets/86264301/2a2286a5-25fd-4e71-9849-99656241da63

## Drawbacks
The model is not 100% accurate due to lack of training. The model was trained on 1 epoch, which took approx 25 hours to complete. If the model were to be trained on more epochs using more GPUs it would likely be more accurate at detecting pedestrians.

## License
This project is licensed under the MIT License.
