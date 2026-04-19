🍎 Fruit Disease Detection Using VGG16
📌 Overview

This project focuses on detecting diseases in fruits using Deep Learning and Computer Vision techniques. It leverages the power of the VGG16 Convolutional Neural Network (CNN) architecture to classify fruit images into healthy and diseased categories.

The goal is to assist in early disease detection, helping improve agricultural productivity and reduce crop losses.

Deep learning models like VGG16 are widely used in image classification tasks due to their high accuracy and ability to extract complex features automatically .

🧠 Model Architecture
Model Used: VGG16 (Transfer Learning)
Pre-trained on ImageNet dataset
Fine-tuned for fruit disease classification
Why VGG16?
Strong feature extraction capability
Proven performance in image classification
Reduces training time using transfer learning

📁 Dataset

The dataset consists of fruit images categorized into:

Healthy fruits
Diseased fruits (multiple classes depending on dataset)
Data Preprocessing Steps:
Image resizing
Normalization
Data augmentation (if applied)
Train-test split

⚙️ Technologies Used
Python 🐍
TensorFlow / Keras
NumPy
Matplotlib
OpenCV (optional)

🔄 Project Workflow
1. Data Preprocessing
Load and clean image dataset
Resize images to required input size (224x224 for VGG16)
Normalize pixel values
2. Model Building
Load pre-trained VGG16 model
Freeze base layers
Add custom classification layers
3. Training
Compile model with optimizer & loss function
Train on dataset
Validate performance
4. Evaluation
Accuracy & loss metrics
Confusion matrix (optional)
Model performance comparison

📊 Results
Achieved high classification accuracy (typically ~90%+ in similar models)
Effective in distinguishing between healthy and diseased fruits

🚀 How to Run the Project
Clone the repository:
git clone https://github.com/atusharpareek/Fruit-Disease-Detection-Using-VGG16-
Navigate to project folder:
cd Fruit-Disease-Detection-Using-VGG16-
Install dependencies:
pip install -r requirements.txt
Run the model:
python main.py

📌 Key Features
🍎 Image-based disease detection
⚡ Transfer learning using VGG16
📊 High accuracy classification
🔍 Scalable for multiple fruit types

🧠 Applications
Smart agriculture
Automated crop monitoring
Disease diagnosis systems
Mobile-based farming tools

🔮 Future Improvements
Deploy as web/mobile app
Use advanced models (ResNet, EfficientNet)
Real-time detection using camera
Expand dataset for more fruit types

👨‍💻 Author
Tushar Pareek
