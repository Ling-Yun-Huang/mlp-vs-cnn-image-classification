# Understanding and Contrasting Multilayer Perceptrons and Convolutional Neural Networks for Image Classification  

A project exploring and comparing the effectiveness of **Multilayer Perceptrons (MLPs)** and **Convolutional Neural Networks (CNNs)** in image classification. This project demonstrates strong skills in **deep learning development, image processing, and model evaluation**.

## 🔹 Project Overview  
This project was part of the **Master’s in Data Science** program (*Neural Computing course*) at **City, University of London** (2024), where it was awarded a **Distinction**.  

### 🚀 Key Skills Demonstrated  
- **Deep Learning:** Neural network development with **MLPs** and **CNNs**  
- **Image Processing:** Resizing, normalization, and tensor conversion  
- **Model Evaluation:** Performance analysis using **accuracy, precision, recall, and F1-score**  
- **Hyperparameter Tuning:** Optimizing architectures with early stopping & dropout  
- **Comparative Analysis:** Assessing computational efficiency and feature extraction  

## 📂 Dataset  
Dataset: [**Intel Image Classification**](https://www.kaggle.com/datasets/puneet6060/intel-image-classification) (*not included in this repository*).  

- **Categories:** Building, forest, glacier, mountain, sea, and street  
- **Training Data:** ~14,000 images  
- **Testing Data:** ~3,000 images  

### 📌 Preprocessing  
- Images resized to **32x32 pixels**  
- Train-Validation-Test Split: **80%-10%-10%**  
- **Batch size:** 32, using tensor conversion  
- **Early stopping:** Training stops after **5 non-improving epochs** (max **20 epochs**)  

## 🔍 Model Development  
### **Multilayer Perceptrons (MLPs)**  
- Fully connected layers processing flattened image data  
- No spatial awareness, requiring extensive preprocessing  

### **Convolutional Neural Networks (CNNs)**  
- Uses convolutional layers for spatial feature extraction  
- More efficient for image classification tasks  

## 📊 Evaluation & Findings  
| Model | Accuracy | Strengths | Weaknesses |  
|--------|---------|------------|------------|  
| **MLP** | Moderate | Works on structured data | Lacks spatial feature extraction |  
| **CNN** | High | Captures spatial hierarchies | More computationally expensive |  

**Key Takeaways:**  
✔ CNNs significantly outperform MLPs for image classification.  
✔ Feature extraction is crucial for complex image data.  
✔ MLPs struggle without spatial awareness mechanisms.  

## ⚡ Conclusion  
This project highlights the advantages of CNNs over MLPs in image classification, showcasing expertise in **deep learning, neural networks, and model evaluation**.  

## 📜 License  
This project’s **code** is licensed under the [MIT License](LICENSE).  

