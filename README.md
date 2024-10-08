# Image-cropping-with-CV

### crop images automatically with computer vision techniques

>framework  :Tensorflow 

>Images and bounding box augumentation : albumentations 

Handwritten images were collected and used [makesense.ai](https://www.makesense.ai/) for bounding box annotation.Built a custom neural network using tensorflow keras to predict bounding box co-ordinates and also used transfer learning techniques like retrainng ssd mobilenet pretrained model using tensorflow object detection api and also retrained yolov5 model using pytorch and compared the results.

Performed image augumentation on images using albumentations library and trained the custom neural network on a total of 176 images.


## Objective 

### Example Image
The model Crops the the image automatically, as shown below. 






![intro PNG](https://github.com/SSahas/Image-cropping-with-Computer-vision/assets/82393353/aa534e0c-febf-4b37-9a4b-c7ef371791de)

NOTE : To see the Tensorflow_neural_network.ipynb code please view it on colab here : https://colab.research.google.com/drive/1al5VwJEMDkp_NHlQQEaJnF14PALCNUEO#scrollTo=dxuGKZSUGobx.

## Results 

| Model | Accuracy | mAP(0.5) | Inference time(s) |
| ------ | ------ | ------ | ------ |
| Yolov5(680 X 680) | 0.996 |  0.99 | 0.298 |
| custom neural network(224 X 224) | 0.759 | 0.418 | 0.138 |
| ssd mobile net Tensorflow(320 X 320) | 0.987 | 0.817 | 0.08 |
