# Clustering Analysis on Seeds Dataset

This project explores clustering techniques on the Seeds dataset using various preprocessing methods. We evaluate the performance of **K-Means**, **Hierarchical Clustering**, and **KMeans Shift**, alongside different levels of data preprocessing such as normalization, transformation, and PCA.

## 🔗 Google Colab

You can view and run the notebook here:  
[Open in Google Colab](https://colab.research.google.com/drive/1J-9E6oJUfPQFp5gpCdSyg3cE7ENjRd4d#scrollTo=XR9r30jCCmuP)

## 📊 Dataset

- **Name**: Seeds Dataset  
- **Source**: UCI Machine Learning Repository

The dataset consists of measurements of geometrical properties of kernels belonging to three different varieties of wheat.

## 🧪 Clustering Techniques

The following clustering algorithms were applied:

- **K-Means Clustering**
- **Hierarchical Clustering**
- **KMeans Shift Clustering**

## ⚙️ Preprocessing Approaches

Each algorithm was tested under four preprocessing scenarios:

1. **No Preprocessing**
2. **Normalization Only**
3. **Transformation + Normalization (T+N)**
4. **Transformation + Normalization + PCA (T+N+PCA)**

---

## 🏆 Results

| Criterion | Best Result |
|----------|-------------|
| **Best Clustering Algorithm** | K-Means (with T+N+PCA) |
| **Best Number of Clusters** | 3 |
| **Best Silhouette Score** | ~0.32 (K-Means with T+N+PCA) |

K-Means performed consistently well across all preprocessing combinations. Using all three steps — transformation, normalization, and PCA — led to the highest silhouette score, indicating well-formed clusters.

---

## 📈 Visualizations

The clustering results were visualized using 2D projections post-PCA to demonstrate the separation between clusters across different techniques and preprocessing steps.

---

## 🧠 Conclusion

- **K-Means** clustering proved to be the most reliable and effective algorithm, especially when used with full preprocessing (T+N+PCA).
- **Hierarchical Clustering** improved with normalization but did not outperform K-Means.
- **KMeans Shift** worked decently without preprocessing but had higher computational costs.
- **Optimal clustering was achieved with 3 clusters**, matching the expected number of seed types in the dataset.
- **Silhouette analysis confirmed** the quality of clustering, with the best score achieved using K-Means after full preprocessing.

---

## 📄 PDF Report

A full breakdown of results and metrics is available in the [PDF report](https://github.com/AnMaster15/clustering/blob/main/Results_Clustering%20(1)%202%20(1).pdf).

## 👤 Author

**Anchit Mehra**  
3co18
