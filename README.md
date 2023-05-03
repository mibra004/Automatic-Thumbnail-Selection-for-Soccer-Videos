# Automatic-Thumbnail-Selection-for-Soccer-Videos

This is the final code for our project. The project results in creating a automatic thumbnail selection using different machine learning models. For instance, for Face Detection, different machine learning models were implemented such as dlib(default), haar, mtcnn, yolov3.

* For contribution:
	* Implemented YOLOv3, Laplacian for Blur Detection

* Future Work:
	* GMM ( Gradient Magnitude Method) can be Implemented for blur detection
	* Finding an evalution metrics to evaluate the result of the thumbail
	* SSD (Single MultiBox Detection) can be used for better Face Detection

## How to run code

1. Run on Linux  Distribution. i.e ( We have used Ubuntu 22.03)
2. 
```
apt-get update
xargs apt-get install -y <packages.txt
pip install -r requirements.txt
```
3. 
```
python create_thumbnail.py soccervideo(path to the video)
```

## Example
```
python3 create_thumbnail.py ~/Downloads/changed491.mkv -yolo --BLaplacian -LEliteserien2019 -CSurma -IQAOcampo

```
