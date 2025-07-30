# 🔬 Blood Cell Type Classification using Deep Learning

A deep learning project to classify white blood cell images into four categories: **Eosinophil**, **Lymphocyte**, **Monocyte**, and **Neutrophil**. This classification assists in preliminary hematological analysis and automated diagnostic systems.

---

## 📁 Dataset

**Source**: [Blood Cells Dataset on Kaggle](https://www.kaggle.com/datasets/paultimothymooney/blood-cells)  
**Contributed by**: Paul Mooney

The dataset contains high-resolution images of peripheral blood smear cells, categorized into:

- **EOSINOPHIL**
- **LYMPHOCYTE**
- **MONOCYTE**
- **NEUTROPHIL**

Each class contains roughly 500 labeled images in the `TRAIN` and `TEST` folders.

---

## 🎯 Objective

To build a Convolutional Neural Network (CNN) that can classify white blood cells with high accuracy and support medical diagnostic workflows through AI-assisted tools.

---

## 🧪 Model Performance

✅ **Validation Accuracy**: `93.16%`  
📊 **Classification Report**:

| Cell Type     | Precision | Recall | F1-Score | Support |
|---------------|-----------|--------|----------|---------|
| EOSINOPHIL    | 0.89      | 0.89   | 0.89     | 499     |
| LYMPHOCYTE    | 0.98      | 0.96   | 0.97     | 496     |
| MONOCYTE      | 0.95      | 0.98   | 0.97     | 495     |
| NEUTROPHIL    | 0.90      | 0.89   | 0.90     | 499     |

📈 **Overall Accuracy**: `93.16%`  
📉 **Macro F1 Score**: `0.93`  

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- OpenCV, NumPy, Matplotlib, Pandas
- Scikit-learn
- Jupyter Notebook (Google Colab)

---


---

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/BrijeshRakhasiya/Blood-Cell-Classification.git
   cd blood-cell-type-prediction
2. Install required libraries:
   ```bash
   pip install -r requirements.txt

# 📌 Key Features
End-to-end white blood cell classification pipeline

Data preprocessing using OpenCV

Deep CNN architecture with high validation accuracy

Confusion matrix and classification report for evaluation

Can be extended into a web-based diagnostic tool

# 💡 Future Enhancements
Integrate Grad-CAM or SHAP for model interpretability

Develop a real-time prediction web app using Streamlit or Flask

Extend model to detect diseases like leukemia with extended datasets

# 🙋‍♂️ Author
Brijesh Rakhasiya
AI/ML Enthusiast | Data Scientist | Problem Solver


## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**e.
