# Image-cropping-with-CV

crop images automatically with computer vision techniques

>framework  :Tensorflow 

>Data and bounding box augumentation : albumentations 

Original image             |  Croped image(Predicted)
:-------------------------:|:-------------------------:
<img src="Images/Test/058eeccda566ce0132bd7a2ffe3f5272.jpg" width = "395" height = "500">  |  <img src="Images/croped_image.png" width = "395" height = "500">


## Results 

| Model | Accuracy | mAP(0.5) | Inference time(s) |
| ------ | ------ | ------ | ------ |
| Yolov5 | 0.996 |  0.99 | 0.298 |
| custom neural network | 0.759 | 0.418 | 0.138 |
| ssd mobile net Tensorflow | 0.987 | 0.817 | 0.08 |
