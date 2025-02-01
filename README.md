# Breast Cancer Detection using Machine Learning

## 🚀 **Project Overview**

Breast cancer is one of the most prevalent cancers among women. Early detection plays a crucial role in improving the chances of successful treatment. This project uses **Machine Learning** techniques to classify breast tumors as **Malignant** (cancerous) or **Benign** (non-cancerous) based on a set of medical features from the **Breast Cancer Wisconsin Dataset**.

The project implements the **Naïve Bayes Classifier**, a probabilistic model that applies **Bayes' Theorem** to classify tumors based on their features.

## 📊 **Dataset**

The dataset used for this project is the **Breast Cancer Wisconsin Dataset** and includes:

- **30 Features**: These features represent various characteristics of cell nuclei present in breast cancer biopsies, such as:
  - Mean radius
  - Texture
  - Perimeter
  - Area
  - Smoothness, etc.
  
- **Target Labels**:
  - **Malignant (1)**: Cancerous tumor
  - **Benign (0)**: Non-cancerous tumor

### 📥 **Install Dependencies**

Before running this project, ensure you have all necessary dependencies installed. You can install them using the following command:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

### ⚙️ **Project Workflow**

**1. Data Loading & Exploration**
Understanding the dataset: Load and explore the dataset, check for null values, and analyze the features.
Key Operations:
Load dataset using load_breast_cancer() from sklearn.datasets.
Explore the structure and distribution of the features.

**2. Data Preprocessing**
Split the dataset into training (80%) and testing (20%) sets for evaluation.
Perform any necessary data transformations or scaling.

**3. Model Training**
Train a Naïve Bayes classifier, which is effective for classification tasks like this one.
Evaluate model performance on the test set.

**4. Predictions**
Use the trained model to make predictions on unseen test data.

**5. Evaluation**
Measure model performance using Accuracy, Classification Report, and Confusion Matrix.
Visualize results with Matplotlib and Seaborn.

**6. Visualization**
Visualize the Confusion Matrix with a heatmap.
Create distribution plots for key features.

### 📝 **Running the Project**
Start Jupyter Notebook:

```bash
jupyter notebook
```
Open the Notebook:

Navigate to the project directory and open the .ipynb file in Jupyter Notebook.
Execute the Cells:

Run each code cell in order to load data, train the model, make predictions, and visualize the results.

### 📈 **Results**

Accuracy Score: ~95% (May vary slightly due to dataset splits)

Confusion Matrix:
True Positives (TP), True Negatives (TN), False Positives (FP), and False Negatives (FN) are visualized.

Classification Report: Includes Precision, Recall, and F1-score.

### 🖼️ **Visualizations**

- Heatmap of the Confusion Matrix
- Distribution plots of key features

![image](https://github.com/user-attachments/assets/fc056a03-aaf4-42db-8a19-872e7d8a983e)


### 🔧 **Future Enhancements**

- Implement other ML models like Logistic Regression, Decision Trees, or Neural Networks.
- Perform Feature Selection to optimize performance.
- Experiment with Hyperparameter Tuning.
