# Iris-KNN-Classification

This project implements a classification model using the K-Nearest Neighbors (KNN) algorithm to accurately predict the species of Iris flowers (Setosa, Versicolor, or Virginica) based on their sepal and petal measurements.

It serves as a foundational exercise demonstrating core Machine Learning concepts, data visualization, and model optimization.

## Key Concepts & Techniques Used

* **Supervised Learning:** Training a model on labeled data (features and known species).
* **K-Nearest Neighbors (KNN) Algorithm:** A non-parametric, distance-based classification method. 

* **Data Visualization (EDA):** Using **Pair Plots** to analyze feature distributions and class separability.
* **Hyperparameter Tuning:** Systematically testing various **'K' values** to ensure optimal and robust model performance.

##  Repository Contents

| File | Description |
| :--- | :--- |
| `Iris_KNN_Classifier.ipynb` | The complete Jupyter Notebook containing all the executed code, analysis, visualization, training, and evaluation steps. |
| `README.md` | This overview document. |
| `requirements.txt` | Lists all necessary Python libraries and their versions (`scikit-learn`, `pandas`, `seaborn`, etc.). |

##  Results Summary

The final model achieved excellent performance on the test set:

| Metric | Result |
| :--- | :--- |
| **Accuracy** | **100.00%** |
| **Optimal K Value** | **K=5** (or K=3, K=1 based on the optimization plot) |
| **F1-Score (Macro Avg)** | **1.00** |

The high accuracy is expected due to the Iris dataset's clean nature and the clear linear separability of the Setosa species.

##  How to Run the Project

To run this project on your local machine, follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [Your Repository URL Here]
    cd Iris-KNN-Classification
    ```

2.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Notebook:**
    Open the `Iris_KNN_Classifier.ipynb` file using Jupyter Notebook or Google Colab and execute the cells sequentially.
