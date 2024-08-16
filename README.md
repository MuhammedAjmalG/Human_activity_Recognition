# Human Activity Recognition Using Machine Learning and Deep Learning Techniques

## Project Overview

This project focuses on Human Activity Recognition (HAR) using Channel State Information (CSI) data collected from wireless devices. The goal is to accurately classify various human activities through the application of both traditional machine learning algorithms and deep learning techniques.

### Key Features

- **Traditional Machine Learning Algorithms**: XGBoost, Random Forest, and Support Vector Machine (SVM) are employed for classification tasks, leveraging their effectiveness in handling structured data.
- **Deep Learning Techniques**: Long Short-Term Memory (LSTM) neural networks are used to capture temporal dependencies in sequential CSI data.
- **Preprocessing**: Includes windowing and normalization of CSI data to extract relevant features for model training.
- **Data Augmentation and Imbalance Handling**: Techniques such as data augmentation and under-sampling are applied to improve model generalization and address class imbalance.
- **Model Evaluation**: Performance is assessed using metrics like accuracy, precision, recall, and F1-score.

## Project Workflow

1. **Data Preprocessing**
   - Windowing and normalization of CSI data.
   - Feature extraction for input into machine learning and deep learning models.

2. **Model Training**
   - Training of traditional machine learning models (XGBoost, Random Forest, SVM) on preprocessed data.
   - Training of LSTM models, including single-layer and two-layer LSTM architectures, to capture temporal dependencies.

3. **Evaluation**
   - Models are evaluated based on accuracy, precision, recall, and F1-score.
   - Comparative analysis of machine learning algorithms and LSTM models to determine the most effective approach for HAR.

## Results and Insights

The experimental results demonstrate the strengths and limitations of each approach, providing valuable guidance for selecting suitable models in practical HAR applications. Detailed performance metrics and comparative analysis are provided within the project notebooks.

## Usage Instructions

- The project is implemented in a series of Jupyter notebooks, where each step of the process is documented and executable.
- Please refer to the respective notebooks for code execution, data preprocessing, model training, and evaluation.

## Notes

- For additional details and specific instructions on running the notebooks, please refer to the `human_activity_recognition_with_csi_dataset.ipynb` files included in the repository.


