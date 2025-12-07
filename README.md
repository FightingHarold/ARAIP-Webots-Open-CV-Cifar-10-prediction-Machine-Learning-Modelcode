 Webots Robot - Obstacle Avoidance & Color Detection & Photo Capturing of Animals
Advanced obstacle avoidance robot with real-time color detection using both RGB and OpenCV HSV methods, featuring automatic image capture when objects are detected. After the captured images are saved on the device, we use them to train my CNN model and see whether it predicts the image correctly under the condition of 32x32 pixels.

## Features

- Dual Color Detection: RGB threshold-based + OpenCV HSV analysis
- Obstacle Avoidance: 8x IR proximity sensors with reactive turning
- Image Capture: Auto-saves detected object images (32x32 PNG)
- Debug Logging: Frame-by-frame color analysis output
- Smooth Navigation: Velocity-based turning without jerky movements

<img width="1216" height="543" alt="image" src="https://github.com/user-attachments/assets/80c61a56-d521-4d6c-8372-01fd983f9206" />


Webots Final World With the Animal photo Saving to Device

 
# CIFAR-10 Image Classification CNN

Deep learning project implementing a Convolutional Neural Network to classify the CIFAR-10 dataset (10 object categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck) with accuracy.

##  Features

- 3-layer CNN: with Conv2D, MaxPooling, Dense layers
- Data augmentation: via TensorFlow Keras
- Real-time predictions: on custom images
- Model persistence: (save/load as `.keras` format)
- Visualization: of predictions with confidence scores

Model Architecture & Training Overview:
Convolutional Neural Network (CNN)​

Input: 32×32 color images (CIFAR-10
format)​

Layers:​

3 x (Conv2D + ReLU +
MaxPool)​

Flatten​

Dense (64 units, ReLU)​

Output: Dense (10 units, softmax
for CIFAR-10 classes)​

​​
​
 <img width="659" height="381" alt="image" src="https://github.com/user-attachments/assets/0fcbd685-4ce1-4678-bc7e-ddc99f184fdd" />




Optimiser: Adam (Adaptive Moment
Estimation) specifies the optimisation
algorithm used to update the model's
weights during training​

Loss: Sparse Categorical
Crossentropy. This specific loss
function is commonly used for multi-
class classification problems where the
labels are integers​

Epochs: 10, with learning rate tuning​
<img width="1045" height="369" alt="image" src="https://github.com/user-attachments/assets/6361984c-a160-4610-b970-f41c6d4831f3" />



Provides a visual sample of the data the model is trained on and confirms the association between images and their corresponding labels​
​
<img width="720" height="730" alt="image" src="https://github.com/user-attachments/assets/c0dc058f-1b99-4389-bed1-2da6e708da4b" />





<img width="1169" height="671" alt="image" src="https://github.com/user-attachments/assets/494f5391-6812-4fc0-a5ed-a44fb3daa89c" />




<img width="768" height="805" alt="image" src="https://github.com/user-attachments/assets/e0955fc8-e7fe-438d-bba3-f888c12eaac6" />


