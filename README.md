# Telecom-churn-prediction
This project focuses on predicting customer churn in the telecom industry using an Artificial Neural Network (ANN).
Customer churn refers to customers leaving a service provider, and predicting it helps companies take preventive actions.

## Objective
* Analyze telecom customer data.
* Build a predictive model to identify churn.
* Visualize model performance using multiple evaluation metrics.

## Technologies Used
* Python
* NumPy
* Pandas
* Matplotlib & Seaborn
* Scikit-learn
* TensorFlow / Keras
  
## Workflow
### 1. Data Preprocessing
* Removed missing values.
* Converted categorical data using.
* Standardized features using.

### 2. Model Building (ANN)
* Input Layer
* Hidden Layers:
  * Dense (64 neurons, ReLU)
  * Dense (32 neurons, ReLU)
* Output Layer:
  * Dense (1 neuron, Sigmoid)

### 3. Training
* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Epochs: 50
* Batch Size: 32

### 4. Evaluation
* Accuracy Score
* Confusion Matrix
* ROC Curve & AUC Score

## Visualizations

The project includes a complete dashboard with:

* Training vs Validation Loss
* Training vs Validation Accuracy
* Confusion Matrix (Heatmap)
* ROC Curve (AUC Score)
* Probability Distribution of Predictions
* Churn Rate by Geography 

## 📂 Dataset

* File: `Artificial_Neural_Network_Case_Study_data.csv`
* Contains customer details and churn status (`Exited` column)

## How to Run

1. Install dependencies:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

2. Run the notebook or Python script:

```bash
python your_file_name.py
```

---

## Output

* Model Accuracy printed in console.
* Graphical dashboard showing performance metrics.

## Key Insights

* ANN model effectively predicts churn probability.
* Visualization helps understand model performance.
* ROC-AUC provides deeper evaluation beyond accuracy.

## Author
**Kaushiki Rani**

