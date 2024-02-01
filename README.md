# Hyperthyroidism Detection Project

Welcome to the Hyperthyroidism Detection Project! This project utilizes the capabilities of Machine Learning (ML) to develop a predictive model for diagnosing hyperthyroidism in patients. The goal is to contribute to improved medical diagnostics and decision-making in the field of thyroid disorders.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Project Overview](#project-overview)
  - [Data Import and Cleaning](#data-import-and-cleaning)
  - [Visualizations](#visualizations)
  - [Model Training](#model-training)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project employs Multinomial Naive Bayes, Support Vector Machine (SVM), Random Forest, and Multilayer Perceptron (MLP) classifiers to predict hyperthyroidism based on various features related to thyroid function tests, symptoms, and medical history.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required libraries (see [requirements.txt](requirements.txt))

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hzaheer48/hyperthyroidism-detection.git
   cd hyperthyroidism-detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Thyroid.ipynb
   ```

## Project Overview

### Data Import and Cleaning

The project begins with importing hyperthyroidism-related data and cleaning it to ensure the dataset's integrity. Columns with missing values are handled, and unnecessary columns are dropped.

### Visualizations

Explore visualizations to gain insights into the gender distribution, age and gender distribution, boolean column distribution, measured thyroid parameters, and more.

### Model Training

Various machine learning models, including Multinomial Naive Bayes, SVM, Random Forest, and MLP, are trained and evaluated to predict hyperthyroidism accurately.

## Usage

1. Open the Jupyter Notebook in your local environment.
2. Execute each cell sequentially to run the entire project.
3. Analyze the visualizations and model accuracies.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
