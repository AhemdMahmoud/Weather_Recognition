# Weather_Recognition
## This project implements a` web-app `weather recognition classifier using deep learning with EfficientNetB4 architecture. The classifier is trained to classify images into 11 weather classes, including ` hail, snow, glaze, lightning, fog smog, frost, dew , rain, rainbow, rime, and sandstorm`.

# Dataset
## This dataset contains images categorized by different weather conditions. It can be used for weather image classification tasks, helping models recognize various weather types like cloudy, rainy, sunny, etc.

## For more details and to access the dataset, visit the [Kaggle page](https://www.kaggle.com/datasets/jehanbhathena/weather-dataset).

# Model Architecture

## The classifier utilizes the EfficientNetB4 architecture, a state-of-the-art convolutional neural network (CNN) known for its efficiency and effectiveness in image classification tasks. EfficientNetB4 is a convolutional neural network architecture that belongs to the EfficientNet family, introduced by Mingxing Tan and Quoc V. Le in 2019. It is designed to balance model size and accuracy by scaling the depth, width, and resolution of the network in an optimal manner. EfficientNetB4 is one of the larger variants in the series, offering better performance at the cost of increased computational resources compared to smaller variants like EfficientNetB0 or B1. It has been widely used for various computer vision tasks, including image classification, object detection, and segmentation.

### EfficientNetB4 offers a good balance between model size and performance, making it suitable for deployment on resource-constrained devices.

#Deployment
## The model is deployed using a streamlit  web application, allowing users to interact with it by uploading images and receiving predictions on weather conditions in real time. The deployed application achieves 91% accuracy on the test set, demonstrating its effectiveness in recognizing weather patterns.
