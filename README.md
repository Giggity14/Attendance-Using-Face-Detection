# Attendance-Using-Face-Detection


**Overview**

This project presents an automated attendance system using face recognition technology to improve accuracy, efficiency, and security in attendance tracking. The system detects and recognizes faces in real-time and records attendance automatically, eliminating the need for manual entry.


**Problem Statement**

Traditional attendance systems suffer from:

Manual errors and inefficiency

Time-consuming processes

Proxy (fake) attendance

Poor record management

This project solves these issues using AI-based facial recognition.


**Objectives**

Automate attendance using face recognition

Eliminate proxy attendance

Reduce manual effort and errors

Maintain accurate and real-time attendance records


**Technologies Used**

Programming Language: Python

Libraries: OpenCV, Dlib, Pillow (PIL)

Database: MySQL

GUI: Tkinter


**Methodology**

Face Detection: HOG + SVM (Dlib)

Feature Extraction: 128-dimensional embeddings

Image Processing: OpenCV techniques (histogram equalization, blur)

Model Training: Supervised learning


**Challenges**

Reduced accuracy in low-light conditions

Difficulty with occluded (masked) faces


**System Workflow**

Register student and capture face dataset

Train model to generate facial embeddings

Detect faces using webcam

Recognize faces using trained model

Mark attendance with date and time

Store records in CSV/database
