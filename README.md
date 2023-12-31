# Wildlife Object_Detection through YOLOv8-
## _For Wildlife Surveillance and Protection_

Made for [Department of Information Technology & Communication](https://www.doitc.rajasthan.gov.in/) (DoIT&C), Government of Rajasthan
For Practice School- I, 
by Bhaskar Mishra (2021B4A72427H)
BITS Pilani Hyderabad Campus
- Wildlife detection through Webcam, Video or Photo
## - FOR THE FULL CODE OF WEBSITE CHECK [Wildlife-Detection-Web_Application](https://github.com/blaze0081/Wildlife-Detection-Web_Application)

## Features

- Import any Picture or Video (supported by OpenCV)
- Live detection through webcam
- from ultralytics import YOLO
- Based on yolov8n: 

| Model | size (pixels) | Speed CPU ONNX (ms) | Speed A100 TensorRT (ms) | params (M) |
| ------ | ------ | ------ | ------ | ------ |
| YOLOv8n | 640 | 80.4 | 0.99 | 3.2 |


## Installation

# Step 1: Set up a Virtual Environment
In the terminal, run the following command to install the virtualenv package if you don't have it already:
```sh
pip install virtualenv
```
Next, create a new virtual environment in your project directory with the following command:
```sh
python -m venv venv
```
Activate the virtual environment: 
```sh
On Windows, run: .\venv\Scripts\Activate 
On macOS/Linux, run: source venv/bin/activate
```


# Step 2: Install the dependencies and libraries and start the server.

```sh
pip install -r requirements.txt 
```


# Step 3: Change the file per your need and run

Change ```Yolo-Webcam.py``` as you need (Picture, Video or Camera) through given comments.
Run using  
```sh
python Yolo-Webcam.py
```
