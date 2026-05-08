# Machine Learning Algorithms

Basic implementations of fundamental machine learning algorithms from scratch using Python and NumPy. Each algorithm is implemented as a standalone module with accompanying tests.

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming language |
| NumPy | Numerical computations |
| scikit-learn | Testing and validation datasets |

## Features

- Clean, educational implementations of ML algorithms
- Each algorithm in its own module with tests
- No high-level ML framework dependencies for core implementations
- Focus on understanding the underlying mathematics

## Algorithms Implemented

| Algorithm | Description |
|-----------|-------------|
| Linear Regression | Gradient descent-based regression |
| Logistic Regression | Binary classification |
| K-Nearest Neighbours | Instance-based classification |
| Naive Bayes | Probabilistic classifier |
| Perceptron | Single-layer neural network |
| Support Vector Machine | Maximum margin classifier |
| Principal Component Analysis | Dimensionality reduction |

## Prerequisites

- Python 3.7+
- pip (Python package manager)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/nikolaykolibarov/machine-learning-algorithms.git
cd machine-learning-algorithms
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install numpy scikit-learn
```

## How to Run

Each algorithm has a test file that demonstrates its usage:

```bash
# Run linear regression example
python linear-regression/linear_regression_tests.py

# Run KNN example
python k-nearest-neighbours/k_nearest_neighbours_tests.py
```

## Project Structure

```
machine-learning-algorithms/
├── linear-regression/
│   ├── linear_regression.py
│   └── linear_regression_tests.py
├── logistic-regression/
│   ├── logistic_regression.py
│   └── logistic_regression_tests.py
├── k-nearest-neighbours/
│   ├── k_nearest_neighbours.py
│   └── k_nearest_neighbours_tests.py
├── naive-bayes/
│   ├── naive_bayes.py
│   └── naive_bayes_tests.py
├── perceptron/
│   ├── perceptron.py
│   └── perceptron_tests.py
├── support-vector-machine/
│   ├── support_vector_machine.py
│   └── support_vector_machine_tests.py
├── principal-component-analysis/
│   ├── pca.py
│   └── pca_tests.py
└── .gitignore
```

## Credits

Implementations based on tutorials from [Python Engineer YouTube channel](https://www.youtube.com/channel/UCbXgNpp0jedKWcQiULLbDTA).

> **Note:** This project was created for educational/course purposes to understand machine learning algorithms at a fundamental level.
