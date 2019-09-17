# Install

## Create a virtualenv  
- virtualenv -p python3 ./

## Activate virtualenv
- source bin/activate

## Run pip
- pip install -r requirements.txt

## Download yolov3.weights
- cd yolo-coco
- wget https://pjreddie.com/media/files/yolov3.weights

## Run application
- python yolov3.py --image ponte_zoom.png
