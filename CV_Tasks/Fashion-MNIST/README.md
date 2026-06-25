# <center> **PROJECT: Fashion-MNIST Classification**

Image classification of 10 clothing categories using Convolutional Neural Network on the Fashion-MNIST dataset.

---

### **Project Goal**

Build a robust CNN model to classify grayscale images of clothing items, demonstrating practical skills in computer vision and deep learning.

---

### **Dataset**

- **Name**: Fashion-MNIST
- **Images**: 28×28 grayscale (784 pixels)
- **Classes**: 10 categories (T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)
- **Training samples**: 60,000
- **Test samples**: 10,000

---

### **Project Stages**

1. Basic data analysis and exploration
2. Data cleaning and validation (checking for NaN values)
3. Data preparation (reshaping, normalization, one-hot encoding)
4. Model development and training (CNN architecture)
5. Evaluation and conclusions

---

### **Model Architecture**

- Convolutional layers with MaxPooling
- Flatten + Dense layers with Dropout
- Softmax output for 10 classes

---

### **Technologies Used**

- `TensorFlow` / `Keras`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `ImageDataGenerator` for data augmentation (if used)

---

### **Results**

- **Validation Accuracy**: **88.97%**

---

### **Key Achievements**

- Successfully implemented a CNN for image classification
- Performed complete data preprocessing pipeline
- Achieved solid performance on a benchmark computer vision dataset
- Gained practical experience with Fashion-MNIST — a modern replacement for the classic MNIST

---

### **Project Structure**

- `notebooks/` — main Jupyter notebook
- `data/` — dataset files (or download instructions)
- `figures/` — training plots, sample images, confusion matrix
- `requirements.txt`

---

### **Conclusion**

This project demonstrates fundamental skills in building Convolutional Neural Networks for image classification. The achieved accuracy of **88.97%** on Fashion-MNIST confirms a good understanding of CNN architecture and training process.

---