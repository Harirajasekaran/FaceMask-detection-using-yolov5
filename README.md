# FaceMask-detection-using-yolov5
# 😷 Face mask detection 😷



Experiment face mask detection with YOLOv5 models

Face mask detection is an object detection task that detects whether people are wearing masks or not  using YOLOv5 model.



# Dataset

The model was trained on Face-Mask dataset which contains 853 images belonging to 2 classes, as well as their bounding boxes in the PASCAL VOC format. The classes are defined as follows:

*With mask

*Without mask


# Yolov5
Download your model from : !git clone https://github.com/ultralytics/yolov5

To train the model use command :!python train.py --img 640 --batch 16 --epochs 50 --data "/content/drive/MyDrive/face /dataSet.yaml" --weights "/content/yolov5/yolov5s.pt" --nosave --cache ##give the file path

To test the model use command:  !python detect.py --weights "/content/yolov5/runs/train/exp/weights/last.pt" --img 640 --conf 0.25 --source "/content/drive/MyDrive/face /face_data/test"

# Results:
![image](https://user-images.githubusercontent.com/102818840/191231160-89886241-7d56-4bcd-9439-294cecbeb8ab.png)
![image](https://user-images.githubusercontent.com/102818840/191231246-bac6b917-3fec-47c8-8a3f-6bb3c449e356.png)
![image](https://user-images.githubusercontent.com/102818840/191231205-c0170bdc-f849-474c-be5f-f9e28491d897.png)
![image](https://user-images.githubusercontent.com/102818840/191231289-82db8ca0-7938-4b9e-9d6c-3ef4a3180824.png)
