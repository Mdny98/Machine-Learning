# 🎵 ML-Based Music Instrument Classification & Clustering

This Machine Learning project aims to accurately **classify** and **cluster** traditional Iranian and global musical instruments. It focuses on six instruments:

- **Ney**
- **Piano**
- **Santour**
- **Setar**
- **Tar**
- **Violon**

The project leverages both **supervised learning** (classification) and **unsupervised learning** (clustering) to achieve its goals. It was developed as part of the **Fall 2021 Machine Learning course**.

---

## 📂 Dataset

- **Total size:** ~5.5 GB
- **Samples:** 1400+ audio files
- **Features:** Extracted from frequency sampling and signal analysis.
- **Label source & contributors:** [Link to dataset and collectors](https://docs.google.com/spreadsheets/d/1loXFMd3MiwldArxzswm3GqNFW7SiV0QjJpFgQsF98ns/edit?gid=0#gid=0) 

The dataset was preprocessed and summarized into a tabular format (`data.csv`) for machine learning tasks.

---

## 📁 Project Structure

```
├── Decision Tree & Boosting.ipynb
├── KNN.ipynb
├── Clustring.ipynb
├── MLP.ipynb
├── README.md
└── data.csv
```


---

## 🧠 Techniques Used

### 🔎 Classification Algorithms
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Boosting (e.g., AdaBoost, Gradient Boosting)**
- **Multilayer Perceptron (MLP)**

### 📊 Clustering Algorithms
- **K-Means Clustering**
- **Hierarchical Clustering (Agglomerative)**

---

## 📓 Notebooks Overview

### `KNN.ipynb`
- Implements **K-Nearest Neighbors** to classify instrument types.
- Includes tuning of `k` parameter and distance metrics.
- Confusion matrix and accuracy visualizations included.

### `Decision Tree & Boosting.ipynb`
- Contains experiments using **Decision Trees** and **Boosting techniques**.
- Comparison between base learners and ensemble methods.
- Visualizes decision boundaries and feature importances.

### `MLP.ipynb`
- Implements a **Multilayer Perceptron** using `sklearn.neural_network`.
- Explores different architectures and activation functions.
- Includes training/validation loss curves.

### `Clustring.ipynb`
- Applies **K-Means** and **Hierarchical Clustering** on the same dataset.
- Uses silhouette scores and dendrograms for evaluation.
- Visualizes cluster groupings with PCA or t-SNE.

---

## 📊 Sample Visualizations

### Clustering Result (PCA Projection)
<img width="640" height="458" alt="PCA" src="https://github.com/user-attachments/assets/e434a4c4-6b37-401b-a439-30d669d4d121" />

### MLP Training Loss and Accuracy

<img width="386" height="278" alt="mlp" src="https://github.com/user-attachments/assets/7db8a863-4b45-4065-b32f-01ad67f6eee2" />
<img width="392" height="278" alt="mlpLoss" src="https://github.com/user-attachments/assets/31f246df-4ddf-465a-bffb-6a86142a7961" />

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/music-instrument-ml.git
   cd music-instrument-ml```
