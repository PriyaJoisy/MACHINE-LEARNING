# 🤖 K-Nearest Neighbors (KNN) Classifier on the Iris Dataset  

## 📌 Overview  
This assignment demonstrates how to build a **K-Nearest Neighbors (KNN) Classifier** using the famous **Iris flower dataset**.  

The Iris dataset is one of the most popular datasets in machine learning, containing measurements of iris flowers from three different species:  
- Setosa  
- Versicolor  
- Virginica  

Our goal is to train a **KNN model** that can predict the species of an iris flower based on its features.  

---

## 📂 Dataset Details  
**Features (inputs):**  
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

**Target (output):**  
- Species of the iris flower (*Setosa, Versicolor, Virginica*)  

The dataset contains **150 samples** (50 from each species).  

---

## 🧮 Key Concepts  

- **K-Nearest Neighbors (KNN):** A supervised ML algorithm that classifies a sample based on the majority class among its *k* nearest neighbors.  
- **k-value Selection:** Choosing the right number of neighbors (*k*) is crucial for accuracy. In this case, **k = 13**.  
- **Standardization:** Scaling features ensures fair comparison when calculating distances.  

---

## 📊 Results (k = 13)  

- **Test Accuracy:** ~96.67%  
- **Training Accuracy:** High, with no signs of overfitting.  

### Observations:  
- *Setosa* is classified perfectly due to its distinct petal size.  
- *Versicolor* and *Virginica* slightly overlap, but the model still achieves strong accuracy.  
- Feature scaling ensures fair distance calculation and better performance.  


---



