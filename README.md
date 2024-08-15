### Ongoing Project (2024.06 ~)

#### 'inference_sample' folder is for testing the model
#### 'detected' folder is the object-detected results of our model
#### 'main' folder contains our learning procedure of YOLO

#### We collected over 79,000 food ingredient images with 40 classes
#### classes were arranged based on the popularity. (Apple, Pork, Chicken, cabbage, ....)
#### For those who are interested in the dataset, please feel free to contact me!"

# Food Ingredient Detection
## Object Detection & Freshness Assessment for Food Ingredients
Welcome to the Food Ingredient Detection project! This repository is part of a larger platform designed to facilitate the buying and selling of leftover ingredients. The platform leverages advanced AI techniques to detect, assess, and value food ingredients based on their freshness.

## Project Pipeline
Our platform operates on the following pipeline:

### 1. Image Capture: Users upload an image of the ingredients.
### 2. Object Detection:
       The image is processed using YOLOv8 to detect each ingredient with high accuracy (currently 93%).
### 3. Image Processing:
       Each detected ingredient is cropped from the original image.
       OpenCV is used to preprocess these cropped images for further analysis.
### 4. Freshness Detection:
       The freshness of each ingredient is evaluated using several neural network architectures, including ResNet, DenseNet, and GoogleNet.
### 5. Fair Price Calculation:
       A proprietary algorithm calculates the fair price for each ingredient based on its freshness and other factors.
### 6. Platform Integration:
       The calculated prices are used to facilitate the buying and selling of leftover ingredients on our platform.


## Repository Overview
This repository will contain the core code for:
### Object Detection: Implementing YOLOv8 for high-accuracy ingredient detection.
###  Freshness Detection: Utilizing neural networks to determine the freshness of each detected ingredient.

We hope this project contributes to reducing food waste by providing a reliable and efficient way to trade leftover ingredients.
