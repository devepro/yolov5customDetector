# Yolov5 Custom Detector:

![](messigif.gif)

This is an implementation of the Ultralytics Yolov5 github repository on custom data. To run this code on the bottle data:

1. Clone this repo.
2. Install the dependenciers using

`$ pip install -U -r requirements.txt` 

3. Get the data from [kaggle](https://www.kaggle.com/deadskull7/cola-bottle-identification) and put it into the training folder

4. Run:

```
# Train yolov5l on custom dataset for 300 epochs
$ python train.py --img 416 --batch 16 --epochs 30 --data bottle.yaml --cfg training/yolov5s.yaml -—weights ‘’

