# Machine Learning Assignment 1: Tree-Based Classifiers & Optimization

## 📌 Overview
This repository contains the solution for **Assignment 1** of the "Introduction to Machine Learning" course. [cite_start]The project involves building, training, and optimizing three different **tree-based classifiers** to detect cancer based on a numerical dataset[cite: 3, 4, 5, 42].

## 🛠️ Tech Stack
* **Language:** Python
* [cite_start]**Environment:** Google Colab [cite: 7]
* [cite_start]**Libraries:** Scikit-learn, MLFlow [cite: 29]

## 🚀 Key Features

### 1. Model Implementation
* [cite_start]Implementation of **3 distinct tree-based classifiers** following specific architectural constraints[cite: 5].
* [cite_start]Data processing involves purely **numerical data** for cancer detection (no image processing)[cite: 43].

### 2. Hyperparameter Optimization (Grid Search)
* [cite_start]Optimization performed using **Grid Search** logic implemented within the notebook[cite: 27].
* [cite_start]Over **100 experiments** were conducted across the different models to find the optimal parameter sets[cite: 26].

### 3. Experiment Tracking with MLFlow
* [cite_start]All experiments are tracked and logged using **MLFlow**[cite: 29].
* Logs include parameters, metrics, and model performance to ensure reproducibility and easy comparison.

### 4. Evaluation Metrics
[cite_start]Models are evaluated and compared using the following four metrics[cite: 19, 20]:
* **Accuracy**
* **Precision**
* **Recall**
* **F-score**

## 📂 Project Structure
* [cite_start]`ig_nor_ex1.ipynb`: The main Jupyter Notebook containing the code for the classifiers, Grid Search logic, and MLFlow integration[cite: 12, 40].
* [cite_start]`ig_nor_ex1.xlsx`: An Excel file summarizing the optimization results and best-performing parameters[cite: 40].

## ⚙️ How to Run
1.  Open the `.ipynb` file in **Google Colab**.
2.  Ensure all dependencies are installed (as defined in the notebook).
3.  Run the cells sequentially to train the models and execute the Grid Search optimization.
4.  The final results are exported to an Excel file.

---
*Created as part of the Introduction to Machine Learning course requirements.*
