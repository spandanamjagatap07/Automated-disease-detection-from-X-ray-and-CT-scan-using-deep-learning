# Automated-disease-detection-from-X-ray-and-CT-scan-using-deep-learning

This project is a **Deep Learning based medical image analysis system** that detects diseases from **X-ray and CT scan images**. The system allows users to upload a medical scan image and predicts whether the disease is present or not.

The application supports detection of multiple diseases such as:
* Pneumonia (Chest X-ray)
* Brain Tumor (CT Scan)
* Kidney Stone (CT Scan)
* Bone Tumor (Bone X-ray)

The project uses **Convolutional Neural Networks (CNN)** for training models and a **Streamlit web interface** for easy interaction.

### 1️⃣ Data Collection

* Collected medical image datasets for different diseases.
* Organized the dataset into **disease and normal classes**.
* Example:
  * yes/ → disease images
  * no/ → normal images

### 2️⃣ Data Preprocessing

* Image resizing
* Image normalization
* Train–test split (80% training, 20% testing)

### 3️⃣ CNN Model Development

A **Convolutional Neural Network (CNN)** was built using **TensorFlow and Keras**.
* Convolution layers (Conv2D)
* Activation layers (ReLU)
* MaxPooling layers
* Flatten layer
* Dense layers
* Dropout for overfitting prevention
* Softmax output layer for classification
The model was trained for several number of epochs and saved as an `.h5` file for prediction. 

### 4️⃣ Multiple Disease Prediction System

We developed a **multi-disease prediction system** where the user can select the disease type and upload a scan image.
Supported disease modules:
* Pneumonia Detection
* Brain Tumor Detection
* Kidney Stone Detection
* Bone Tumor Detection

### 5️⃣ Web Application Interface

A **Streamlit web application** was developed where users can:

1. Select the disease type
2. Upload an X-ray or CT scan image
3. Click **Predict**
4. View the prediction result with confidence score

Example output:
* ✅ Disease Detected
* 🟢 Normal (No Disease)
The interface is designed to be **simple and user-friendly for medical image analysis**. 

# Applications

* Early disease detection
* Medical image analysis
* AI-assisted healthcare systems
* Clinical decision support
