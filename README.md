# K-Means Clustering From Scratch

A complete implementation of the **K-Means Clustering Algorithm** built entirely from scratch using Python and NumPy — without using any inbuilt machine learning clustering libraries like `sklearn.cluster.KMeans`.

This project demonstrates the internal working mechanism of one of the most fundamental unsupervised machine learning algorithms through mathematical computation and visualization.

---

## 🚀 Project Overview

K-Means Clustering is an **unsupervised machine learning algorithm** used to group similar data points into clusters based on feature similarity.

In this project:

- K-Means is implemented manually
- Euclidean distance is calculated from scratch
- Cluster assignment logic is manually developed
- Centroid updates are performed iteratively
- Final clusters are visualized using Matplotlib

The primary goal of this project is to deeply understand how clustering works internally rather than relying on high-level library abstractions.

---

## ✨ Features

✔️ K-Means implemented completely from scratch  
✔️ No use of `sklearn.cluster.KMeans`  
✔️ Manual centroid initialization  
✔️ Euclidean distance computation  
✔️ Iterative centroid optimization  
✔️ Data visualization using Matplotlib  
✔️ Beginner-friendly implementation  
✔️ Well-structured and readable code  

---

## 🧠 Understanding K-Means Clustering

K-Means works in the following iterative steps:

1. Choose the number of clusters (**K**)
2. Randomly initialize K centroids
3. Assign each data point to the nearest centroid
4. Recalculate centroid positions
5. Repeat until centroids stop changing

The algorithm attempts to minimize the **Within-Cluster Sum of Squares (WCSS)**.

---

## 📌 Mathematical Formula

### Euclidean Distance

\[
d(x, y) = \sqrt{\sum_{i=1}^{n}(x_i - y_i)^2}
\]

### Centroid Update Formula

\[
C_k = \frac{1}{N_k}\sum_{i=1}^{N_k} x_i
\]

Where:

- \( C_k \) → centroid of cluster k
- \( N_k \) → number of points in cluster k

---

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib

---

## 📂 Project Structure

```bash
KMeans-Clustering-From-Scratch/
│
├── dataset/
│   └── data.csv
│
├── images/
│   └── clustering_output.png
│
├── kmeans.py
├── requirements.txt
└── README.md
```

---

## 📊 Output Visualization

The algorithm groups similar data points into distinct clusters and updates centroids iteratively until convergence.

### Example Output

<p align="center">
  <img src="images/clustering_output.png" width="700">
</p>

---

## ⚡ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/your-username/KMeans-Clustering-From-Scratch.git
```

### Navigate to Project

```bash
cd KMeans-Clustering-From-Scratch
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python kmeans.py
```

---

## 📈 Future Improvements

- K-Means++ initialization
- Elbow Method for optimal K selection
- Silhouette Score evaluation
- Animated clustering visualization
- Support for higher-dimensional datasets

---

## 🎯 Learning Outcomes

Through this project, I gained practical understanding of:

- Unsupervised Learning
- Distance-based clustering
- Optimization techniques
- Iterative algorithms
- Mathematical intuition behind ML models
- Data visualization

---

## 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Ajit Yadav**

B.Tech CSE Student | Aspiring Data Scientist | Machine Learning Enthusiast

- GitHub: your-github-link
- LinkedIn: your-linkedin-link

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.