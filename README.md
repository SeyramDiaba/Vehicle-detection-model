# CAR OBJECT DETECTION
### We have created an object detection model that can accurately detect vehicles in a video frame or an image using the predefined architectures in the TensorFlow Object Detection API
![tf](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Tensorflow_logo.svg/1200px-Tensorflow_logo.svg.png)



ensorFlow is a free and open-source software library for machine learning and artificial intelligence. It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks.



## Summary

- Install Tensorflow
- ---
- Install TFOD dependencies (Protobuf, Cocobuf API )
- ---
- convert csv labels to tf.record file format
- Complile and Install Object detection API in /models/research path 
- Download and extract pretrained model
- Train the model
- Activate TensorBoard

> model setup and training were
> all run in Google Colab
> ![colab logo](https://3.bp.blogspot.com/-apoBeWFycKQ/XhKB8fEprwI/AAAAAAAACM4/Sl76yzNSNYwlShIBrheDAum8L9qRtWNdgCLcBGAsYHQ/s1600/colab.png)

## TendorBoard Metrics
DirectionBoxes recall
>- ![DirectionBoxes recall](https://github.com/jean-on-hub/Vehicle-detection-model/blob/main/tensorboard%20snippets/DirectionBoxes%20recall.PNG?raw=true)
Direction Boxes Precision
- ![DirectionBoxes Precision](https://github.com/jean-on-hub/Vehicle-detection-model/blob/main/tensorboard%20snippets/DirectionBoxes_Precision.PNG?raw=true)
Evaluation
- ![eval 0](https://github.com/jean-on-hub/Vehicle-detection-model/blob/main/tensorboard%20snippets/eval%200.PNG?raw=true)
- ![eval 1](https://github.com/jean-on-hub/Vehicle-detection-model/blob/main/tensorboard%20snippets/eval%201.0.PNG?raw=true)
- ![eval 2](https://github.com/jean-on-hub/Vehicle-detection-model/blob/main/tensorboard%20snippets/eval%202.0.PNG?raw=true)
Learning step and steps per second
- ![learning step and steps per second](https://github.com/jean-on-hub/Vehicle-detection-model/blob/main/tensorboard%20snippets/learning%20step%20%20and%20steps%20per%20secs.PNG?raw=true)
Loss One
- ![loss functions](https://github.com/jean-on-hub/Vehicle-detection-model/blob/main/tensorboard%20snippets/loss%20functions.PNG?raw=true)
Loss Two
- ![loss](https://raw.githubusercontent.com/jean-on-hub/Vehicle-detection-model/80d3954bc517415963cd1da91da8aa8943727998/tensorboard%20snippets/loss2.PNG)




