# Face Attendance System with Liveness Detection & Antispoof
## Overview
This project presents a comprehensive exploration and comparison of two distinct approaches to building a face recognition application: face verification (self-supervised learning) and face classification (supervised learning). The system integrates the best-performing model into a face attendance system with an anti-spoofing module to ensure security and reliability. Please refer the [project report](102781103_FASProjectReport.pdf) for more details. 

## Files and Their Descriptions
1. `102781103_FASProjectReport.pdf`
This PDF file contains the detailed project report, which includes the introduction, methodology, results, discussion, and conclusion. It provides an in-depth analysis of the face recognition models developed and their performance.

2. `classification_vgg_model.ipynb`
This Jupyter notebook contains the implementation of the VGG-based face classification model. It includes data preprocessing, model training, evaluation, and saving of the model. The VGG model is used to classify faces into predefined identity classes.

3. `verification_siamese_model.ipynb`
This Jupyter notebook includes the implementation of the Siamese network for face verification. It involves data collection using a webcam, model architecture definition, training, and evaluation. The Siamese model determines whether two face images belong to the same person.

4. `face_attendance_app.ipynb`
This Jupyter notebook documents the process of building the face attendance application using the trained Siamese model. It includes steps for loading the model, preprocessing images, verifying faces, logging events, and creating the user interface with Tkinter. The application integrates real-time webcam functionality and an anti-spoofing module.

## Application Interface
1. Unknown user detected
![Unknown user trying to login](demo_images/unknownuser.png)

2. Registering new user
![Registering new user](demo_images/registration.png)

3. User logged in
![User logged in](demo_images/loggedin.png)

4. Antispoof triggered
![Antispoof triggered](demo_images/antispoof.png)

5. User logged out
![User logged out](demo_images/loggedout.png)

6. Event recorded in `attendance.csv`
![Event record](demo_images/attendance.png)

## Downloading Pre-trained Models
Pre-trained models and other resources must be downloaded and placed in the same directory. Ensure you have the following models and datasets downloaded:
1. [Download Kaggle Face Dataset](https://www.kaggle.com/competitions/11-785-fall-20-homework-2-part-2/data)
2. [Download `deploy.txt` & `res10_300x300_ssd_iter_140000.caffemodel`](https://github.com/Shiva486/facial_recognition)
3. [Download VGG face weights](https://www.kaggle.com/datasets/acharyarupak391/vggfaceweights)
4. [Download Pre-trained antispoofing model](https://github.com/minivision-ai/Silent-Face-Anti-Spoofing/tree/master)


If you would like to contribute to this project, please fork the repository and submit a pull request. For any issues or suggestions, please open an issue on GitHub or contact me via [email](mailto:zunyangzy03@gmail.com).
