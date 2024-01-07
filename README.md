
# Sign Language Detection using LSTM Deep Learning

This project aims to detect and recognize sign language gestures using LSTM (Long Short-Term Memory) networks in deep learning.

## Steps

### 1. Import and Install Dependencies
Ensure you have the required dependencies installed to run the project. Use the following command to install them:
```bash
pip install -r requirements.txt
```

### 2. Keypoints using MP Holistic
Use MediaPipe Holistic to extract keypoints from sign language gestures.

### 3. Extract Keypoint Values
Extract keypoint values representing hand and body landmarks from the MediaPipe Holistic model.

### 4. Setup Folders for Collection
Set up a directory structure for collecting and organizing keypoint values.

### 5. Collect Keypoint Values for Training and Testing
Collect and store keypoint values for training and testing sets. Divide data into appropriate folders for model training and evaluation.

### 6. Preprocess Data and Create Labels and Features
Preprocess the collected data by converting keypoint values into appropriate feature sets. Create corresponding labels for sign language gestures.

### 7. Build and Train LSTM Neural Network
Design an LSTM-based deep learning model to recognize sign language gestures. Train the model using the preprocessed data.

### 8. Make Predictions
Make predictions using the trained LSTM model on unseen sign language gestures.

### 9. Save Weights
Save the weights of the trained LSTM model for future use and retraining.

### 10. Evaluation using Confusion Matrix and Accuracy
Evaluate model performance using a confusion matrix and calculate accuracy metrics.

### 11. Test in Real Time
Test the LSTM model in real-time to detect sign language gestures from a live video feed.


### This README provides an overview of the steps involved in the sign language detection project using LSTM deep learning. Feel free to expand each section with more detailed instructions, code examples, or explanations based on your project's specifics.