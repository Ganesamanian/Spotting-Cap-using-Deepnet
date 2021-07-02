# Spotting-Cap-using-Deepnet

This repository contains the code for detecting bottle cap using deep learning based model called SSD (Single shot detector) from the stable frame extracted from the video.

Refer [report](CV_Report_2021_02_07.pdf) for the detail understanding.

The pipeline of the project is depicted in [image](flowchart.png)

## Steps to execute
1. The model is reused from one of my friend's work [model](https://github.com/mohanrobotics/models)
2. Follow all the ten steps to train the model specified in the above link.
3. Once the model is trained, load the trained from inference_graph folder under object detection (the trained model for this project is avialable at inference_graph folder)
4. Change the following details, availale after the function block [input_video_path, frozen_model_path, output_folder_path, input_image_path]
5. Execue the file to predict the object from the stable frame extarcted from the video.
	
## Samples
1. Sample input video is provided [video](CV20_video_1.mp4)
2. Sample output image is provided [Output](1_label.jpg)

