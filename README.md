# FACE-MASK-DETECTION-Opencv-and-Deeplearning-

Harnessing the power of machine learning, we developed a predictive model to identify individuals at risk of developing diabetes. By analyzing a comprehensive dataset of patient demographics and medical information, our model achieved remarkable accuracy, outperforming traditional methods. This breakthrough has the potential to revolutionize diabetes prevention, leading to improved patient outcomes and significant cost savings for the healthcare system.

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

![image](https://github.com/anilkumarbapathi/FACE-MASK-DETECTION-Opencv-and-Deeplearning-/assets/150010512/50ae556b-187a-4095-9187-3db0cf3d75ef)


CLASS DIAGRAM:

![image](https://github.com/anilkumarbapathi/FACE-MASK-DETECTION-Opencv-and-Deeplearning-/assets/150010512/837904e6-87f9-414f-99e8-d5fc450f0f46)

DATA FLOW DIAGRAM:

![image](https://github.com/anilkumarbapathi/FACE-MASK-DETECTION-Opencv-and-Deeplearning-/assets/150010512/39d56b56-b52e-41be-b2a3-ee1f9122740c)

CONCLUSION:

In conclusion, we developed a mask detection system that can detect whether people are wearing masks or not. We used a deep learning-based approach and achieved an accuracy of 98% on the test set. Our model can be an effective tool for enforcing mask-wearing in public places. We also deployed our model on a low- power device like the Raspberry Pi, which makes it easily accessible and affordable. Overall, our mask detection system has the potential to contribute to the ongoing efforts to prevent the spread of the COVID-19 virus.
