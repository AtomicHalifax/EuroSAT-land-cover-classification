# 🛰️ EuroSAT Land Cover Classification using ResNet50

A deep learning project that classifies satellite images into **10 land cover categories** using **Transfer Learning** with **ResNet50** and **PyTorch**.


## 📖 Project Overview

This project uses the **EuroSAT RGB** dataset and a pretrained **ResNet50** model to classify satellite images into different land cover classes such as forests, rivers, residential areas, highways, and more.

Instead of training a convolutional neural network from scratch, Transfer Learning is used to leverage features learned from the ImageNet dataset, resulting in faster training and high classification performance.

This project was developed in **Google Colab** using **PyTorch** and serves as my first end-to-end computer vision project.

## 🔄 Project Workflow
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/32d79c49-e752-4b36-be83-e7f99a76bc33" />

# 🖼️ Project Showcase
## Dataset Sample

 <img width="1203" height="990" alt="Sample Predictions" src="https://github.com/user-attachments/assets/aeef62ea-e63f-45c3-b095-43533a6055e6" />


## 📊 Project Results

The model was trained using **Transfer Learning with ResNet50** on the **EuroSAT RGB** dataset. After 10 epochs of training, the model achieved the following performance:

| Metric | Result |
|:-------|:------:|
| 🧠 Model | ResNet50 (Transfer Learning) |
| 📦 Framework | PyTorch |
| 🛰️ Dataset | EuroSAT RGB |
| 🗂️ Classes | 10 |
| 🖼️ Total Images | 27,000 |
| 🎯 Training Accuracy | **94.61%** |
| ✅ Test Accuracy | **93.70%** |
| 📈 Weighted F1-Score | **0.94** |

> **Summary:** The model achieved strong generalization on unseen satellite images, obtaining **93.70% test accuracy** and a **0.94 weighted F1-score** across all 10 land-cover classes.

---

## 📂 Dataset

This project uses the **EuroSAT RGB** dataset, which contains **27,000 satellite images** across **10 land-cover classes**.

Download the dataset from the official source:

**EuroSAT Dataset:** https://github.com/phelber/EuroSAT

After downloading, extract the dataset and update the dataset path in the notebook before running the project.
## ✨ Key Features

- Transfer Learning using ResNet50
- Multi-class satellite image classification
- PyTorch implementation
- Data preprocessing and augmentation pipeline
- Model evaluation using Accuracy, Precision, Recall and F1-score
- Confusion Matrix and error analysis
- Google Colab compatible


## 🔄 Project Workflow

 <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/32d79c49-e752-4b36-be83-e7f99a76bc33" />

# 🖼️ Project Showcase

## Dataset Sample

 <img width="1203" height="990" alt="Sample Predictions" src="https://github.com/user-attachments/assets/aeef62ea-e63f-45c3-b095-43533a6055e6" />

## Class Distribution

<img width="859" height="558" alt="EuroSAT Class distribution" src="https://github.com/user-attachments/assets/7f089ecf-fde0-4f05-87b3-365bf5ccb5d6" />

## Confusion Matrix

<img width="932" height="808" alt="Confusion Matrix   Predictions" src="https://github.com/user-attachments/assets/26e8bea1-3509-4c89-a12d-ed6a05ec57ca" />

## Sample Predictions

<img width="1203" height="990" alt="Sample Predictions" src="https://github.com/user-attachments/assets/1f909d6b-cbd1-4485-95aa-d84c4e5dc434" />

## Misclassified Images

<img width="1191" height="985" alt="Misclassified Test Images" src="https://github.com/user-attachments/assets/95b7a8ad-6d92-4c97-b2b1-f1cdd9a87908" />


## 🧠 Model Architecture

This project uses **ResNet50**, a pretrained Convolutional Neural Network (CNN), with **Transfer Learning**. The final fully connected layer was modified to classify the **10 land-cover classes** in the EuroSAT RGB dataset.


## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/AtomicHalifax/EuroSAT-land-cover-classification.git
cd EuroSAT-land-cover-classification
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```
## 📦 Trained Model

The trained model weights (`eurosat_resnet50.pth`) are not included in this repository due to GitHub file size limitations.

You can reproduce the model by running the notebook from start to finish.


## 🚀 How to Run

1. Clone this repository.
2. Download the **EuroSAT RGB** dataset.
3. Open `notebook/EuroSAT_ResNet50.ipynb` in Google Colab or Jupyter Notebook.
4. Update the dataset path if needed.
5. Run all cells sequentially.
6. The notebook will train the model, evaluate its performance, and generate visualizations.

## 🛠️ Tech Stack

- Python
- PyTorch
- Torchvision
- Google Colab
- NumPy
- Matplotlib
- Scikit-learn


## 🔮 Future Improvements

- Fine-tune additional ResNet50 layers
- Compare with EfficientNet and Vision Transformers (ViT)
- Apply advanced data augmentation
- Deploy the model using Streamlit or Gradio
- Extend the project for satellite-based deforestation detection


## 📄 License

This project is licensed under the **MIT License**.


## 🙏 Acknowledgements

- EuroSAT RGB Dataset
- PyTorch & Torchvision
- Google Colab

⭐ If you found this project interesting, feel free to **star the repository**!
