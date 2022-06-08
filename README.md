# yolov5 deepsort counting master



## Introduction

This repository contains a detector that displays the type of detection and out counts. The detector realizes the separate detection of the comings and goings,and the default direction is  north and south.The default detection categories are pedestrian, bicycle, car, motorcycle, bus, truck.

### How to run

#### How to change the detection direction

change the line 13 and line 21 of file "main.py" .

#### How to change the detection categories

change the line 60 of file "detector.py" .

#### Before you run the tracker

1. Clone the repository recursively:

2. Make sure that you fulfill all the requirements:

   `pip install -r requirements.txt`