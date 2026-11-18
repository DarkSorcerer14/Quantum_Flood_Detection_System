# Quantum Flood Detection System

A machine learning-based flood detection and risk analysis system integrating classical machine learning, statistical modelling, GIS concepts, remote sensing data, time-series analysis, and a simulated quantum-kernel approach.

## Project Overview

Floods are among the most destructive natural disasters, causing significant damage to human life, infrastructure, agriculture, and the environment. Early flood detection and risk assessment can help authorities take preventive measures and improve disaster preparedness.

The **Quantum Flood Detection System** explores the application of machine learning and data-driven techniques for flood classification, risk analysis, and hydrological modelling. The project combines multiple algorithms to study flood-related patterns and evaluate their potential for supporting flood prediction and analysis.

The project also explores a simulated quantum-kernel approach and compares its results with classical machine learning methods.

## Objectives

- Analyse flood-related datasets using machine learning techniques.
- Study relationships between environmental and hydrological variables.
- Apply regression models for flood-related numerical prediction.
- Perform clustering to identify patterns in flood-risk data.
- Analyse river discharge patterns using Hidden Markov Models.
- Implement decision tree and Random Forest classification models.
- Explore a simulated quantum-kernel Support Vector Machine.
- Compare the performance and limitations of different approaches.

## Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Development Environment | Jupyter Notebook |
| Data Processing | NumPy, Pandas |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Statistical Modelling | Regression, Hidden Markov Models |
| Classification | CART, Random Forest, SVM |
| Quantum Simulation | Simulated Quantum Kernel |
| Data Sources | Kaggle, Open-Meteo GloFAS API |

## Project Modules

### Unit 1: Regression Analysis

Regression techniques are used to analyse relationships between flood-related variables and estimate numerical outcomes.

Implemented techniques:
- Linear Regression
- Ridge Regression
- Hyperparameter tuning

### Unit 2: Dimensionality Reduction and Clustering

This module identifies patterns and groups within flood-related data.

Implemented techniques:
- Principal Component Analysis (PCA)
- K-Means Clustering
- Explained variance analysis
- Cluster visualization

### Unit 3: Hydrological Time-Series Analysis

This module studies river discharge patterns using time-series data.

Implemented technique:
- Hidden Markov Model (HMM)

The implementation uses river discharge observations obtained through the Open-Meteo GloFAS API.

### Unit 4: Classification Models

This module applies supervised machine learning algorithms for flood-related classification.

Implemented algorithms:
- Classification and Regression Tree (CART)
- Random Forest Classifier

### Unit 5: Quantum-Inspired Machine Learning

This module explores a simulated quantum-kernel approach for classification.

Implemented approach:
- Quantum-inspired feature mapping
- Statevector-based simulation
- Quantum Kernel Support Vector Machine
- Hyperparameter evaluation

**Note:** The quantum component is a classical simulation of quantum-inspired computations. It does not run on actual quantum hardware, and the project does not establish a demonstrated quantum advantage.

## System Workflow

```text
        Flood-Related Dataset
                  |
                  v
          Data Preprocessing
                  |
                  v
        Feature Selection and
        Data Transformation
                  |
                  v
       Machine Learning Models
                  |
       +----------+----------+
       |          |          |
       v          v          v
   Regression  Clustering  Classification
       |          |          |
       v          v          v
   Numerical   Pattern     CART and
   Analysis    Analysis    Random Forest
                              |
                              v
                       Quantum-Inspired
                       Kernel Approach
                              |
                              v
                     Model Evaluation
                              |
                              v
                    Results and Analysis
```

## Dataset Information

The project uses flood-related data and hydrological observations.

### 1. Flood Risk Dataset

Source: Kaggle

Dataset: [Flood Risk in India](https://www.kaggle.com/datasets/s3programmer/flood-risk-in-india)

### 2. River Discharge Data

Source: Open-Meteo GloFAS API

The project retrieves historical river discharge observations for hydrological time-series analysis.

## Installation and Setup

### Prerequisites

- Python 3.9 or later
- Jupyter Notebook
- pip package manager

### Clone the Repository

```bash
git clone https://github.com/DarkSorcerer14/Quantum_Flood_Detection_System.git
```

### Navigate to the Project Directory

```bash
cd Quantum_Flood_Detection_System
```

### Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn requests hmmlearn jupyter
```

### Run the Notebook

```bash
jupyter notebook
```

Open the project notebook and execute the cells sequentially.

## Model Evaluation and Results

The project evaluates different machine learning and statistical approaches.

| Model / Technique | Evaluation |
|---|---|
| Linear Regression | Regression performance using RMSE |
| Ridge Regression | Regularised regression and hyperparameter tuning |
| PCA | Dimensionality reduction |
| K-Means | Cluster identification |
| Hidden Markov Model | Hydrological state analysis |
| CART | Classification accuracy |
| Random Forest | Classification accuracy |
| Quantum-Kernel SVM | Cross-validation and hyperparameter evaluation |

### Observations

- Ridge Regression is evaluated against Linear Regression to study the effect of regularisation.
- PCA reduces the dimensionality of the dataset while retaining most of its explained variance.
- K-Means identifies groups within the transformed flood-related data.
- Hidden Markov Models are used to investigate changes in river discharge states.
- CART and Random Forest provide baseline classification performance.
- The simulated quantum-kernel approach is evaluated using cross-validation.

**Important:** Any illustrative or placeholder accuracy values must not be interpreted as actual experimental results. In particular, the 93.67% quantum accuracy figure is illustrative and is not a measured model result. The reported quantum-kernel SVM cross-validation accuracy in the notebook is approximately 50.60%.

## Key Features

- Multiple machine learning algorithms.
- Flood-related data analysis.
- Regression-based numerical modelling.
- Dimensionality reduction and clustering.
- Hydrological time-series analysis.
- Classical classification models.
- Simulated quantum-kernel exploration.
- Performance evaluation and visualisation.

## Limitations

- Model performance depends on the quality and availability of the dataset.
- Classification accuracy may be affected by feature selection and class distribution.
- Hydrological observations may not represent every geographical region.
- The quantum-kernel implementation is simulated and does not use actual quantum hardware.
- The project is an academic prototype and is not intended to replace official flood warning systems.

## Future Scope

- Integrating real-time rainfall and river-level data.
- Expanding the dataset to cover more geographical regions.
- Incorporating satellite imagery and remote sensing data.
- Exploring deep learning models such as CNNs and LSTMs.
- Improving classification performance through feature engineering.
- Integrating GIS-based flood-risk visualisation.
- Exploring execution on actual quantum computing platforms.
- Developing a real-time flood monitoring dashboard.

## Project Team

**Team Members**
- Ayush Aryan
- Mukti Shree Jain
- Vivek Kumar Prusty

## References

1. Kaggle – Flood Risk in India Dataset: https://www.kaggle.com/datasets/s3programmer/flood-risk-in-india
2. Open-Meteo – Historical and Hydrological Weather Data: https://open-meteo.com/
3. Scikit-learn Documentation: https://scikit-learn.org/stable/
4. NumPy Documentation: https://numpy.org/doc/
5. Pandas Documentation: https://pandas.pydata.org/docs/
6. Matplotlib Documentation: https://matplotlib.org/stable/
7. hmmlearn Documentation: https://hmmlearn.readthedocs.io/
