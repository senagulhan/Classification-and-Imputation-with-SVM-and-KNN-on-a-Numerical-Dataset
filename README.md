# Classification and Imputation with SVM and KNN on a Numerical Dataset

This project explores how Support Vector Machines (SVM) and K-Nearest Neighbors (KNN) perform on a medical dataset. I also experimented with handling missing values by introducing NaNs and imputing them using the column mean.

## 🛠️ Tools Used

- Python (Pandas, NumPy, Matplotlib)
- Scikit-learn (SVM, KNN, metrics)
- Google Colab
- Dataset: Pima Indians Diabetes dataset

## 📌 What I Did

1. Loaded and explored the dataset
2. Trained SVM and KNN classifiers on the original data
3. Randomly introduced missing values into each feature
4. Replaced missing values using column-wise mean (mean imputation)
5. Trained the models again on the filled data
6. Compared the evaluation results before and after imputation

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion matrix visualizations for both models

## 💡 Notes

- SVM was tested with different kernels; final model used `poly` kernel
- KNN used 27 neighbors in this experiment
- The imputation process didn’t significantly affect the model results, but it's a critical step when working with real-world datasets

---

This project helped me better understand the preprocessing steps in machine learning pipelines and how classification models respond to incomplete data.
