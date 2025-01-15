# 🌸 Iris Flower Classification Project  

📄 Overview  
This project focuses on classifying the **Iris flower species** (Setosa, Versicolor, Virginica) using popular machine learning algorithms. The **Iris dataset** is a small yet classic dataset in machine learning, ideal for beginners to explore concepts like exploratory data analysis (EDA), data visualization, and classification models.  

📊 Dataset  
The dataset contains **150 samples** of Iris flowers with 5 key attributes:  
- sepal_length: Length of the sepal in cm.  
- sepal_width: Width of the sepal in cm.  
- petal_length: Length of the petal in cm.  
- petal_width: Width of the petal in cm.  
- species: The flower species (Setosa, Versicolor, Virginica).  

🛠️ Steps in the Project  
1. **Data Preprocessing and Exploration**  
- Loaded and explored the dataset to understand its structure and distribution.  
- Visualized relationships between features using **pair plots** and **kde plots** with Seaborn.  

 2. **Model Training and Evaluation**  
- Split the dataset into **training** and **test sets** (80%-20%).  
- Implemented and evaluated the following models:  
  - **Logistic Regression**: Achieved 100% accuracy.  
  - **K-Nearest Neighbors (KNN)**: Tuned `k` for optimal performance and achieved 100% accuracy.  
  - **Random Forest Classifier**: Achieved 96.7% accuracy.  
  - **Support Vector Machine (SVM)**: Achieved 96.7% accuracy.  

 3. **Model Comparison**  
- Evaluated models using metrics like **accuracy**, **precision**, **recall**, **F1-score**, and confusion matrices.  
- **Logistic Regression** and **KNN** emerged as the best-performing models for this dataset.  

📈 Visualizations  
The project includes the following key visualizations:  
- **Pair Plot**: Feature relationships grouped by species.  
- **KNN Error Rate Plot**: Error rate vs. `k` neighbors for optimization.  
- **Confusion Matrix Heatmaps**: For model evaluation.  

 🚀 Technologies Used  
- **Languages**: Python  
- **Libraries**:  
  - Data Manipulation: Pandas, NumPy  
  - Visualization: Matplotlib, Seaborn  
  - Machine Learning: Scikit-learn  

---

 🎯 Results  
| Model                   | Accuracy |  
|-------------------------|----------|  
| Logistic Regression     | 100%     |  
| K-Nearest Neighbors (KNN) | 100%     |  
| Random Forest           | 96.7%    |  
| Support Vector Machine (SVM) | 96.7%    |  

---

## 📥 How to Use the Code  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/MonirulIslamm08/Iris-Flower-Classification.git  
   cd Iris-Flower-Classification  
   ```  
2. Install the required libraries:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run the notebook or Python script to train and evaluate the models.  

 💡 Key Takeaways  
- The Iris dataset is linearly separable, which allows simple models like Logistic Regression to achieve perfect accuracy.  
- KNN performs well but can be computationally expensive for larger datasets.  
- Hyperparameter tuning enhances model performance, especially for KNN and Random Forest.  

🔗 Links  
- [Iris Dataset Documentation](https://archive.ics.uci.edu/ml/datasets/iris)  
- [My GitHub Profile](https://github.com/MonirulIslamm08)  
- [Connect on LinkedIn](https://www.linkedin.com/in/monirul-m08/)  

 Acknowledgments : 
Special thanks to the creators of the Iris dataset and the Scikit-learn team for providing powerful tools to explore machine learning concepts. 
