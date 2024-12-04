# YOLOv8-vehicle-detection
Used YOLOv8 to identify and mark vehicles in videos

This project uses YOLOv8 CNN model developed by ultralytics to detect and mark
vehicles on in videos of busy roads. Aim of this project was to learn to work
with YOLO models and video data.

I did not want to use the pretrained yolov8 model to detect vehicles as the objective was
customization. This meant that I could use the same concepts and techniques on any type
of data I wanted in the future. Thus, I used prelabeled image data to train the YOLOv8 model
from scratch.

Finally I used both, this custom trained model and the pretrained model to detect and label
videos. The results were comparable and I believe that the custom trained model might perform 
significantly better than the pretrained model on videos where the frames are more like the 
images that were used for training the model.

Drive link for video results: https://drive.google.com/drive/folders/1rv7riETvU4DJeaPIfkn-q5g2QmdOFjUU?usp=drive_link
