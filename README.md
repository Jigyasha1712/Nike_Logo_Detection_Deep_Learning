# Nike Logo Detection using Deep Learning (VGG16 Transfer Learning)

A Computer Vision and Deep Learning project implementing **Transfer Learning with VGG16** in Keras/TensorFlow to detect and classify Nike brand logos in real-world images.

---

## 🚀 Key Features
- **Transfer Learning Backbone**: Leverages pre-trained **VGG16** weights (ImageNet) for high-level feature extraction.
- **Custom Classification Head**: GlobalAveragePooling2D + Dense layers with Sigmoid activation for binary logo classification.
- **Data Augmentation Pipeline**: `ImageDataGenerator` with random shear, zoom (0.2), and horizontal flips to prevent overfitting.
- **Exported Weights**: Saves trained model weights to `logo_detection_model.h5`.

---

## 🛠️ Tech Stack
- **Frameworks**: TensorFlow, Keras
- **Architecture**: VGG16 CNN Backbone
- **Image Preprocessing**: Keras ImageDataGenerator, Pillow
- **Optimization**: Adam Optimizer, Binary Crossentropy Loss

---

## 📦 How to Run in Google Colab / Locally

### Option 1: Google Colab
1. Upload `Nike_Logo_Detection_VGG16.ipynb` to [Google Colab](https://colab.research.google.com/).
2. Enable GPU Acceleration: `Runtime > Change runtime type > T4 GPU`.
3. Run all cells.

### Option 2: Local Execution
```bash
pip install -r requirements.txt
jupyter notebook Nike_Logo_Detection_VGG16.ipynb
```

---

## 📄 License
MIT License
