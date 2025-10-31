# 🌸 Iris Flower Classifier using K-Nearest Neighbors (KNN)

## 📄 Abstract
This project demonstrates a practical application of the **K-Nearest Neighbors (KNN)** algorithm to classify iris flowers into their respective species — *Setosa*, *Versicolor*, and *Virginica*.  
It uses the classic **Iris dataset**, which is one of the most well-known datasets in the field of Machine Learning.  
This project is aimed at helping beginners understand how KNN works for supervised classification problems.

---

## 🎯 Objectives
1. Understand the **K-Nearest Neighbors (KNN)** algorithm and its working.  
2. Apply KNN to the **Iris dataset** using Scikit-learn.  
3. Visualize feature relationships and correlations.  
4. Evaluate accuracy and find the best `K` value.  
5. Make predictions for new flower samples.

---

## 🧩 Dataset
The dataset used is the **Iris Flower Dataset**, which contains:  
- **150 samples**  
- **4 features**: sepal length, sepal width, petal length, petal width  
- **3 classes**: *Setosa*, *Versicolor*, *Virginica*  

| Feature | Description |
|----------|--------------|
| Sepal Length | Length of the sepal in cm |
| Sepal Width | Width of the sepal in cm |
| Petal Length | Length of the petal in cm |
| Petal Width | Width of the petal in cm |

---

## ⚙️ Implementation Steps
| Step | Description |
|------|--------------|
| 1️⃣ | **Load the Dataset** — Use Scikit-learn’s `load_iris()` function. |
| 2️⃣ | **Data Visualization** — Pair plots and heatmaps to see relationships. |
| 3️⃣ | **Preprocessing** — Split data and scale features. |
| 4️⃣ | **Train Model** — Apply `KNeighborsClassifier()` and fit on training data. |
| 5️⃣ | **Evaluate Model** — Compute accuracy and confusion matrix. |
| 6️⃣ | **Tune K Value** — Find optimal K for best accuracy. |
| 7️⃣ | **Predict New Sample** — Classify an unseen flower. |

---

## 🧠 KNN Algorithm — How It Works
The **K-Nearest Neighbors** algorithm classifies a sample based on the majority label among its `k` nearest points in the feature space.  

Steps:
1. Choose a value for `k` (number of neighbors).  
2. Calculate distance (usually Euclidean) between the new sample and training samples.  
3. Select the `k` closest points.  
4. Assign the class that appears most frequently among those neighbors.

---

## 📊 Results
✅ Model Accuracy: **95–100%** (depending on K value)  
✅ Best K value found through tuning: *around 5–7*  
✅ Confusion matrix and classification report included in the notebook.  

Example Prediction:
```
Input: [5.1, 3.5, 1.4, 0.2]
Predicted Species: setosa
```

---

## 🧪 Tools & Libraries Used
- **Python 3.x**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

---

## 🚀 How to Run
1. **Clone this repository**
   ```bash
   git clone https://github.com/asimsheikh-coder/iris-flower-classifier-using-knn.git
   cd iris-flower-classifier-using-knn
   ```
2. **Install dependencies**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
3. **Run the notebook**
   ```bash
   jupyter notebook KNN_Iris_Classification.ipynb
   ```

---

## 🧑‍💻 Author
**Asim Sheikh**  
12th Grade Student | Aspiring AI Engineer  
📧 Email: asimusmansheikh0@gmail.com  
🌐 GitHub: [@asimsheikh-coder](https://github.com/asimsheikh-coder)

---

## 🔖 Citation
> Sheikh, A. *Iris Flower Classifier using K-Nearest Neighbors (KNN)*. 2025. GitHub Repository.  
> [https://github.com/asimsheikh-coder/iris-flower-classifier-using-knn](https://github.com/asimsheikh-coder/iris-flower-classifier-using-knn)

---

## 🏁 Conclusion
This project is an excellent introduction to supervised learning and the **KNN algorithm**.  
By analyzing the Iris dataset, students can understand how distance-based algorithms classify new data points based on proximity — a foundational concept for more advanced ML techniques.

---
