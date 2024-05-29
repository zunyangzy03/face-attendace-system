# Face Attendance System with Liveness Detection
## Overview
This project presents a comprehensive exploration and comparison of two distinct approaches to building a face recognition application: face verification (self-supervised learning) and face classification (supervised learning). The system integrates the best-performing model into a face attendance system with an anti-spoofing module to ensure security and reliability.

## Files and Their Descriptions
1. `102781103_FASProjectReport.pdf`
This PDF file contains the detailed project report, which includes the introduction, methodology, results, discussion, and conclusion. It provides an in-depth analysis of the face recognition models developed and their performance.

2. `classification_vgg_model.ipynb`
This Jupyter notebook contains the implementation of the VGG-based face classification model. It includes data preprocessing, model training, evaluation, and saving of the model. The VGG model is used to classify faces into predefined identity classes.

3. `verification_siamese_model.ipynb`
This Jupyter notebook includes the implementation of the Siamese network for face verification. It involves data collection using a webcam, model architecture definition, training, and evaluation. The Siamese model determines whether two face images belong to the same person.

4. `face_attendance_app.ipynb`
This Jupyter notebook documents the process of building the face attendance application using the trained Siamese model. It includes steps for loading the model, preprocessing images, verifying faces, logging events, and creating the user interface with Tkinter. The application integrates real-time webcam functionality and an anti-spoofing module.

Adding Pictures
You can add pictures of the application to visually demonstrate its functionality. Place the images in a directory named images within your project folder. Here’s an example of how to include an image in the README:

markdown
Copy code
## Application Interface

![App Screenshot](images/app_screenshot.png)
## Dependencies
This project relies on several dependencies that need to be installed. Additionally, pre-trained models and other resources must be downloaded and placed in the same directory. Ensure you have the following dependencies installed:

TensorFlow
OpenCV
Tkinter
Joblib
Scikit-learn
Download Links for Required Models and Resources
Place the following resources in the appropriate directories as mentioned in the notebooks:

VGG Face Model - Download and place in the directory specified in classification_vgg_model.ipynb.
Siamese Model - Download and place in the directory specified in verification_siamese_model.ipynb.
Anti-Spoofing Model - Follow the instructions in the repository to download and set up the anti-spoofing model.
Usage Instructions
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/face-attendance-system.git
cd face-attendance-system
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Download Required Models and Resources:
Ensure you download and place the required models in the directories specified in the notebooks.

Run the Notebooks:
Open and run the Jupyter notebooks in the following order:

classification_vgg_model.ipynb
verification_siamese_model.ipynb
face_attendance_app.ipynb
Contribution
If you would like to contribute to this project, please fork the repository and submit a pull request. For any issues or suggestions, please open an issue on GitHub.

