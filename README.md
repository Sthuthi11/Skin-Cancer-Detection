# Skin Cancer Detection using ResNet, GoogleNet, and Ensemble Learning

This project focuses on the classification of skin cancer using deep learning models on the HAM10000 dermatoscopic image dataset. A comparative study between **ResNet** and **GoogleNet** was conducted, varying key parameters like epochs (5, 10), optimizers (Adam, SGD), batch sizes (16, 32), and a fixed learning rate (0.0001).

**ResNet** performed better than GoogleNet because of its deeper design and skip connections. These results show that CNNs are effective for classifying skin lesions and can help in early skin cancer diagnosis.

**Ensemble Learning:**
To further improve accuracy and stability, an ensemble of six CNNs was used:
  ResNet, GoogleNet, VGG, DenseNet, EfficientNet, and MobileNet
Voting strategies (soft/hard) were applied to combine predictions and boost performance.
