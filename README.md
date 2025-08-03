# Predictive Maintenance of Industrial Machinery

## Project Description
This project focuses on building a machine learning model to predict potential failures in industrial machines before they occur. The goal is to move from a reactive maintenance approach to a proactive one, thereby reducing machine downtime and cutting operational costs.

The model analyzes a rich dataset of sensor readings, including air temperature, rotational speed, torque, and tool wear, to identify patterns that precede different types of machine failures.

## Technology Used
The project was developed following a standard data science workflow on the IBM Cloud platform.
-   **Platform:** IBM Watsonx AI Studio (using a Jupyter Notebook).
-   **Programming Language:** Python 3.11.
-   **Key Libraries:**
    -   `pandas`: Used for efficient data loading, exploration, and preprocessing.
    -   `scikit-learn`: The core library for implementing the machine learning model, specifically the `RandomForestClassifier`, and for evaluating its performance.
    -   `matplotlib` and `seaborn`: Utilized for creating visualizations, such as the confusion matrix, to better understand and present the model's results.

## Model and Methodology
-   **Algorithm:** We employed a **Random Forest Classifier**, a powerful ensemble learning model well-suited for multi-class classification tasks. It works by building a multitude of decision trees and combining their outputs for a more accurate and robust prediction.
-   **Data Splitting:** The dataset was split into a training set (80%) and a testing set (20%) to ensure the model's performance could be accurately evaluated on unseen data.
-   **Performance Evaluation:** The model was evaluated using a **Confusion Matrix** and a detailed **Classification Report**, which provided key metrics like overall accuracy, precision, and recall for each failure type.

## Key Findings
The model achieved an outstanding **overall accuracy of 99%** on the test data. It proved highly effective at identifying common failure types like "No Failure," "Heat Dissipation Failure," and "Power Failure." The results demonstrate the potential of using machine learning for predictive maintenance to significantly improve operational efficiency.

## How to Run the Project
1.  Download the repository files to your local machine.
2.  Launch a Jupyter Notebook environment (e.g., in IBM Watsonx AI Studio).
3.  Open the `Predictive Maintenance Notebook.ipynb` file.
4.  Run the cells sequentially to reproduce the entire workflow, from data loading to model evaluation.
