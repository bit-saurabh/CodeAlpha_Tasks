# 🌸 Iris Flower Species Classification

A comprehensive machine learning project that classifies Iris flower species using their morphological measurements. This project demonstrates data visualization, exploratory data analysis, and supervised learning using the classic Iris dataset.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Visualizations](#visualizations)
- [Model Performance](#model-performance)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## 🔍 Overview

This project implements a **Logistic Regression** model to classify three species of Iris flowers:
- **Iris Setosa**
- **Iris Versicolor**
- **Iris Virginica**

The classification is based on four morphological features measured from each flower, achieving high accuracy through systematic data analysis and machine learning techniques.

---

## 📊 Dataset

The Iris dataset contains **150 samples** with the following features:

| Feature | Description | Unit |
|---------|-------------|------|
| Sepal Length | Length of the sepal | cm |
| Sepal Width | Width of the sepal | cm |
| Petal Length | Length of the petal | cm |
| Petal Width | Width of the petal | cm |
| Species | Target class (setosa, versicolor, virginica) | - |

**Dataset Distribution:**
- 50 samples per species
- No missing values
- Balanced dataset

---

## ✨ Features

### 📈 Data Visualization
- Distribution histograms for all numerical features
- Scatter plots showing feature relationships
- Species-wise color-coded visualizations
- Correlation heatmap
- Confusion matrix visualization

### 🤖 Machine Learning
- Logistic Regression classifier
- 80-20 train-test split
- Label encoding for target variable
- Comprehensive model evaluation metrics

### 🎯 Interactive Prediction
- Custom input functionality
- Sample predictions with typical measurements
- Real-time species prediction

---

## 🛠️ Installation

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/iris-classification.git
cd iris-classification
```

2. **Install required packages**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Or using requirements.txt:
```bash
pip install -r requirements.txt
```

3. **Verify installation**
```bash
python --version
pip list
```

---

## 🚀 Usage

### Running the Project

1. **Ensure the dataset is in the project directory**
```
iris-classification/
├── iris.csv
├── iris_classification.py
└── README.md
```

2. **Run the script**
```bash
python iris_classification.py
```

3. **Follow the interactive prompts**
   - View automated visualizations
   - Check model evaluation metrics
   - Enter custom measurements for prediction

### Example Usage

```python
# Sample input for prediction
Sepal Length (cm): 5.1
Sepal Width (cm): 3.5
Petal Length (cm): 1.4
Petal Width (cm): 0.2

# Output
✓ Predicted Species: SETOSA
```

---

## 📊 Visualizations

The project generates the following visualizations:

### Chart 1: Distribution of Numerical Variables
Four-panel histogram showing the distribution of each feature across all samples.

### Chart 2: Sepal Length vs Sepal Width
Scatter plot revealing the relationship between sepal dimensions for different species.

### Chart 3: Petal Length vs Petal Width
Demonstrates clear species separation based on petal measurements.

### Chart 4: Sepal Length vs Petal Length
Cross-comparison of sepal and petal length measurements.

### Chart 5: Sepal Width vs Petal Width
Relationship between width measurements across different organs.

### Bonus Visualizations
- **Correlation Heatmap**: Shows feature correlations
- **Confusion Matrix**: Visual representation of model predictions

---

## 🎯 Model Performance

### Evaluation Metrics

| Metric | Score |
|--------|-------|
| **Accuracy** | ~97-100% |
| **Precision** | High across all classes |
| **Recall** | High across all classes |
| **F1-Score** | High across all classes |

### Model Details
- **Algorithm**: Logistic Regression
- **Training Samples**: 120 (80%)
- **Testing Samples**: 30 (20%)
- **Max Iterations**: 200
- **Random State**: 42 (for reproducibility)

---

## 💻 Technologies Used

| Technology | Purpose |
|------------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | Core programming language |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white) | Data manipulation and analysis |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white) | Numerical computations |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat) | Data visualization |
| ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat) | Statistical visualizations |
| ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white) | Machine learning |

---

## 📁 Project Structure

```
iris-classification/
│
├── iris.csv                    # Dataset file
├── iris_classification.py      # Main Python script
├── README.md                   # Project documentation
├── requirements.txt            # Python dependencies
│
├── images/                     # (Optional) Screenshots folder
│   ├── chart1_distributions.png
│   ├── chart2_sepal_scatter.png
│   └── confusion_matrix.png
│
└── .gitignore                  # Git ignore file
```

---

## 📈 Results

The Logistic Regression model demonstrates excellent performance in classifying Iris species:

- **Setosa**: Perfect classification (easily separable)
- **Versicolor**: High accuracy with minimal confusion
- **Virginica**: High accuracy with occasional overlap with Versicolor

**Key Insights:**
- Petal measurements are more discriminative than sepal measurements
- Setosa is linearly separable from other species
- Versicolor and Virginica show some overlap in feature space

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contribution
- Add more classification algorithms (SVM, Random Forest, KNN)
- Implement cross-validation
- Create a web interface using Streamlit or Flask
- Add more visualization options
- Improve documentation

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Saurabh**
- GitHub: [@bit-saurabh](https://github.com/bit-saurabh)


---

<div align="center">

### ⭐ Star this repository if you find it helpful!

**Made with ❤️ and Python**


</div>
