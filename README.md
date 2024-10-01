# Brain Metastasis Segmentation using Nested U-Net and Attention U-Net
This project implements metastasis segmentation on brain MRI images using two deep learning architectures: Nested U-Net (U-Net++) and Attention U-Net. The models are trained on preprocessed MRI images, and the DICE score is used as the primary evaluation metric for segmentation accuracy. A web application is also provided using FastAPI for the backend and Streamlit for the user interface, allowing users to upload MRI images and view metastasis segmentation results.

Table of Contents
Project Overview
Dataset Structure
Preprocessing
Model Architectures
Training and Evaluation
Web Application
Installation
Usage
Contributing
License
Project Overview
The goal of this project is to develop and compare two deep learning models to accurately segment brain metastases from MRI images:

Nested U-Net (U-Net++)
Attention U-Net
After training, the best-performing model is deployed using a FastAPI backend. A Streamlit interface allows users to upload MRI images and get metastasis segmentation predictions.
