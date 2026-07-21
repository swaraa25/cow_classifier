# Indigenous Cattle Breed Classifier

An AI-powered deep learning system for classifying **41 indigenous Indian cattle and buffalo breeds** from images. This project leverages transfer learning with **EfficientNet-B0**, **ResNet18**, and **DenseNet121** to automate breed identification, providing a fast and accessible solution for farmers, researchers, and conservationists. 

The model is trained on a custom dataset using **PyTorch** in Google Colab with image preprocessing, augmentation, stratified dataset splitting, and fine-tuning to improve classification performance. Multiple CNN architectures were evaluated, with **EfficientNet-B0** achieving the best results and reaching **62.79% validation accuracy** after fine-tuning and **85% test accuracy** on unseen images.  

The project also includes a web-based inference system that allows users to upload cattle images and receive real-time breed predictions with confidence scores, demonstrating the practical application of computer vision in livestock management and conservation. 

### Features

* Image classification for **41 Indian cattle and buffalo breeds**
* Transfer learning using EfficientNet-B0, ResNet18, and DenseNet121
* Data preprocessing and augmentation pipeline
* Model training, fine-tuning, and checkpointing
* Real-time image inference with confidence scores
* Web application for easy breed prediction

### Tech Stack

* Python
* PyTorch
* Torchvision
* OpenCV
* Google Colab
* FastAPI
* HTML, CSS, JavaScript
