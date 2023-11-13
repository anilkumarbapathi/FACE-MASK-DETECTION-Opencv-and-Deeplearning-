# FACE-MASK-DETECTION-Opencv-and-Deeplearning-

ABSTRACT:
The significance of adhering to precautionary measures to curb the spread of the COVID-19 virus cannot be overstated. Wearing face masks is widely recognized as one of the most effective means of preventing the transmission of the virus. The mask detection system serves as a valuable tool in ensuring that individuals wear masks in public settings.

PROBLEM STATEMENT:
The objective of this project is to develop a face mask detection system using OpenCV and Keras.  The system should be able to detect faces in real-time video streams and determine whether the person is wearing a face mask or not.  The face mask detection system will be trained using a dataset of images of people wearing face masks and not wearing face masks.  The system will use Deep Neural Networks (DNN) to classify the images and determine whether a face mask is present or not.

DATASET:
We used a our own dataset that consisted of 7553 images of people wearing and not wearing masks. The dataset was split into two equal parts, with 3776 images of people wearing masks and 3777 images of people not wearing masks. The dataset was balanced to ensure that the model is not biased towards one class.

METHODOLOGY:
We used a deep Neural Networks approach to train our mask detection model. We trained our model on a cloud based GPU for 30 epochs, which means that the model was trained on the dataset 30 times. We used the Adam optimizer with a learning rate of 0.001, which is a commonly used optimizer for training deep learning models. We used the binary cross-entropy loss function to optimize the model, which is a commonly used loss function for binary classification problems.

EVALUATION:
We evaluated our model on a test set that consisted of 1,511 images, which were not used during the training phase. We used accuracy as our primary metric to evaluate the model's performance. Our model achieved an accuracy of 98%, which means that the model predicted the correct class for 98% of the test set images.

USE CASE DIAGRAM:
![image](https://github.com/anilkumarbapathi/FACE-MASK-DETECTION-Opencv-and-Deeplearning-/assets/150010512/9c4b1e4a-5e53-465d-a1b5-d11e80278e09)

CLASS DIAGRAM:
![image](https://github.com/anilkumarbapathi/FACE-MASK-DETECTION-Opencv-and-Deeplearning-/assets/150010512/72b02541-bb09-4571-b49c-884b9f10c3b0)

DATA FLOW DIAGRAM:
![image](https://github.com/anilkumarbapathi/FACE-MASK-DETECTION-Opencv-and-Deeplearning-/assets/150010512/0bf30e05-30a9-4e4e-a754-3cc82065e9f0)


