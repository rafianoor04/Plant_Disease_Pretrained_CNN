🌿 Plant Disease Classification using Pre-trained CNNs
This project demonstrates how to classify plant leaf diseases using Convolutional Neural Networks (CNNs). It leverages multiple pre-trained CNN models using PyTorch for transfer learning to achieve high accuracy with efficient training.

📂 Dataset
The dataset used in this project is publicly available on Kaggle:

Dataset: Plant Disease Recognition Dataset

Local Path Used: /kaggle/input/plant-disease-recognition-dataset

Classes:
Healthy

Powdery (Powdery Mildew)

Rust

Total Images per Class:
Approximately 510 images per class (Total: ~1,530 images)

Dataset Split:
Train: 70%

Validation: 15%

Test: 15%

🧠 Model Architectures
We used transfer learning with multiple pre-trained CNN models. The final classification layers of all models were modified to classify 3 output classes.

✅ Models Implemented:
ResNet50

VGG16

MobileNet v2

GoogLeNet

Each model was fine-tuned and evaluated on the same dataset for a fair comparison of performance in terms of accuracy, loss, and inference speed.
