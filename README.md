# Patria AI Hub: Machine Learning Showcase

![Patria AI Hub](https://img.shields.io/badge/Patria-AI%20Hub-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-brightgreen)
![Streamlit](https://img.shields.io/badge/Streamlit-1.30.0-red)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive Streamlit application showcasing 10 diverse machine learning use cases using UCI datasets. This application demonstrates practical applications of supervised learning (regression and classification) and unsupervised learning (clustering) algorithms.

## Table of Contents
- [Overview](#overview)
- [Featured UCI Datasets](#featured-uci-datasets)
- [Machine Learning Use Cases](#machine-learning-use-cases)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [Contact](#contact)
- [License](#license)

## Overview

This application provides a user-friendly interface to explore different machine learning techniques across various domains and datasets. Each use case includes:
- Dataset exploration and visualization
- Data preprocessing steps
- Model training and evaluation
- Interactive predictions
- Explanations and insights

## Featured UCI Datasets

1. Wine Quality Dataset
2. Heart Disease Dataset
3. Iris Dataset
4. Boston Housing Dataset
5. Bank Marketing Dataset
6. Breast Cancer Wisconsin Dataset
7. Auto MPG Dataset
8. Diabetes Dataset
9. Mall Customer Segmentation Dataset
10. Adult Census Income Dataset

## Machine Learning Use Cases

### Regression
1. **Wine Quality Prediction**: Predict wine quality scores based on physicochemical properties
2. **Boston Housing Price Prediction**: Predict housing prices based on neighborhood characteristics
3. **Auto MPG Prediction**: Predict vehicle fuel efficiency based on car attributes

### Classification
4. **Heart Disease Prediction**: Classify heart disease presence based on patient data
5. **Bank Marketing Campaign Success**: Predict if a client will subscribe to a term deposit
6. **Breast Cancer Diagnosis**: Classify tumors as benign or malignant
7. **Adult Income Classification**: Predict whether income exceeds $50K per year

### Clustering
8. **Iris Flower Clustering**: Unsupervised clustering of iris flowers
9. **Mall Customer Segmentation**: Segment customers based on spending behaviors
10. **Diabetes Patient Grouping**: Identify patient groups with similar characteristics

## Installation

```bash
# Clone the repository
git clone https://github.com/harrypatria/patria-ai-hub.git
cd patria-ai-hub

# Create and activate a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Usage

```bash
# Run the Streamlit application
streamlit run app.py
```

The application will open in your default web browser at `http://localhost:8501`.

## Project Structure

```
patria_ai_hub/
├── app.py                      # Main Streamlit application
├── requirements.txt            # Project dependencies
├── README.md                   # Project documentation
├── assets/                     # Static assets
├── components/                 # Reusable UI components
├── pages/                      # Application pages
└── utils/                      # Utility functions
```

## Technologies

- **Frontend**: Streamlit
- **Data Processing**: Pandas, NumPy
- **Machine Learning**: Scikit-learn, XGBoost, LightGBM, CatBoost
- **Visualization**: Matplotlib, Seaborn, Plotly, Altair
- **Model Explainability**: SHAP

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Contact

**Dr. Harry Patria**  
Email: harry.patria23@imperial.ac.uk  
LinkedIn: [linkedin.com/in/harry-patria/](https://linkedin.com/in/harry-patria/)

## License

This project is licensed under the MIT License - see the LICENSE file for details.
