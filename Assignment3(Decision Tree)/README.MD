# 🌳 Decision Tree Classifier on the Iris Dataset  

## 📌 Overview  
This project demonstrates how to build a **Decision Tree Classifier** using the famous **Iris flower dataset**.  
The Iris dataset is one of the most popular datasets in machine learning, containing measurements of iris flowers from three different species:  
- **Setosa**  
- **Versicolor**  
- **Virginica**  

Our goal is to train a decision tree model that can predict the species of an iris flower based on its features.  

---

## 📂 Dataset Details  
- **Features (inputs):**  
  1. Sepal Length  
  2. Sepal Width  
  3. Petal Length  
  4. Petal Width  

- **Target (output):**  
  Species of the iris flower (Setosa, Versicolor, Virginica).  

The dataset contains **150 samples** (50 from each species).  


## 🧮 Key Concepts  

- **Decision Tree**: A supervised ML model that splits data into subsets based on feature values.  
- **Entropy**: A measure of impurity/uncertainty in the dataset.  
- **Information Gain**: The reduction in entropy after a dataset is split on a feature.  
- **Overfitting Control**: Parameters like `max_depth`, `min_samples_split` help prevent overfitting.  


## 📊 Results  

- **Training Accuracy:** 95.23%  
- **Test Accuracy:** 97.78%  

The decision tree shows excellent performance on both training and test data, proving it generalizes well without overfitting.  

- The most important features for classification are **petal length** and **petal width**.  
- Setosa is classified perfectly due to its distinct petal size.  
- Versicolor and Virginica overlap slightly, but the model still achieves near-perfect accuracy.  
