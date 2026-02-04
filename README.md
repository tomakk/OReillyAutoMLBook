# Learning AutoML

<p align="center">
  <img src="docs/assets/images/book-cover.png" alt="Learning AutoML Book Cover" width="300">
</p>

<p align="center">
  <strong>Automating ML Pipelines with AutoGluon, Leading Frameworks, and Real-World Integration</strong>
</p>

<p align="center">
  <a href="https://tomakk.github.io/OReillyAutoMLBook/">📖 View Companion Site</a> •
  <a href="https://www.oreilly.com/">O'Reilly Media</a>
</p>

---

## About This Book

**Learning AutoML** is your comprehensive guide to Automated Machine Learning, covering everything from feature engineering to production deployment. This repository contains all the code examples and Jupyter notebooks from the book.

**Author:** Kerem Tomak

## 📚 Table of Contents

### Part I: Foundations
| Chapter | Title | Notebook |
|---------|-------|----------|
| 4 | Automated Feature Engineering & Data Preprocessing | [Chapter4.ipynb](Chapter4.ipynb) |
| 6 | Neural Architecture Search (NAS) | [Chapter6.ipynb](Chapter6.ipynb) |

### Part II: Data Modalities
| Chapter | Title | Notebook |
|---------|-------|----------|
| 7 | Working with Tabular Data | [Chapter7.ipynb](Chapter7.ipynb) |
| 8 | Processing Text & NLP Data | [Chapter8.ipynb](Chapter8.ipynb) |
| 9 | Time Series Forecasting | [Chapter9.ipynb](Chapter9.ipynb) |
| 10 | Computer Vision | [Chapter10.ipynb](Chapter10.ipynb) |

### Part III: Production & Deployment
| Chapter | Title | Notebook |
|---------|-------|----------|
| 11 | AutoML in Production - MLOps Integration | [Chapter11.ipynb](Chapter11.ipynb) |
| 12 | Automating Data Pipelines with Apache Airflow | [Chapter12.ipynb](Chapter12.ipynb) |
| 13 | Deployment & CI/CD for AutoML Models | [Chapter13.ipynb](Chapter13.ipynb) |

### 🏢 Industry Case Studies
| Case Study | Industry | Notebook |
|------------|----------|----------|
| A | Financial Services - Fraud Detection | [Supplementary_Code_A_Fraud_Detection.ipynb](Supplementary_Code_A_Fraud_Detection.ipynb) |
| B | Retail - Omnichannel Demand Forecasting | [Supplementary_Code_B_Demand_Forecasting.ipynb](Supplementary_Code_B_Demand_Forecasting.ipynb) |
| C | Healthcare - Patient Readmission Prediction | [Supplementary_Code_C_Healthcare_Readmission.ipynb](Supplementary_Code_C_Healthcare_Readmission.ipynb) |

## 🚀 Getting Started

### Prerequisites

- Python 3.8+ (3.10 recommended)
- CUDA-capable GPU (recommended for deep learning chapters)
- 16GB+ RAM for large-scale examples

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/tomakk/OReillyAutoMLBook.git
   cd OReillyAutoMLBook
   ```

2. **Create a virtual environment**
   ```bash
   conda create -n automl python=3.10
   conda activate automl
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter**
   ```bash
   jupyter lab
   ```

## 🛠️ Key Technologies

This book covers the following frameworks and tools:

| Category | Tools |
|----------|-------|
| **AutoML Frameworks** | AutoGluon, AutoKeras, Optuna, Ray Tune |
| **Deep Learning** | PyTorch, TensorFlow, Keras |
| **MLOps** | MLflow, Kubeflow, Apache Airflow |
| **Deployment** | FastAPI, Docker, Prometheus |
| **Data Processing** | pandas, NumPy, scikit-learn |

## 📊 Case Study Results

| Case Study | Key Metric | Business Impact |
|------------|------------|-----------------|
| Fraud Detection | 89% detection rate | $223.5M annual value, 4,470x ROI |
| Demand Forecasting | 11.8% MAPE | $43M working capital freed |
| Readmission Prediction | 0.73 AUC | $79.1M annual value, 720% ROI |

## 📁 Repository Structure

```
OReillyAutoMLBook/
├── Chapter4.ipynb          # Feature Engineering
├── Chapter6.ipynb          # Neural Architecture Search
├── Chapter7.ipynb          # Tabular Data
├── Chapter8.ipynb          # NLP & Text
├── Chapter9.ipynb          # Time Series
├── Chapter10.ipynb         # Computer Vision
├── Chapter11.ipynb         # MLOps Integration
├── Chapter12.ipynb         # Data Pipelines
├── Chapter13.ipynb         # Deployment & CI/CD
├── Supplementary_Code_A_Fraud_Detection.ipynb
├── Supplementary_Code_B_Demand_Forecasting.ipynb
├── Supplementary_Code_C_Healthcare_Readmission.ipynb
├── requirements.txt        # Python dependencies
├── docs/                   # GitHub Pages site
└── README.md
```

## 🤝 Contributing

Found an issue or have a suggestion? Please open an [issue](https://github.com/tomakk/OReillyAutoMLBook/issues) or submit a pull request.

## 📄 License

The code in this repository is released under the [MIT License](LICENSE). The book content is copyright O'Reilly Media.

## 🔗 Links

- [📖 Companion Website](https://tomakk.github.io/OReillyAutoMLBook/)
- [🛒 Buy the Book](https://www.oreilly.com/)
- [📧 Contact Author](mailto:ktomak@mindspaceai.nl)

---

<p align="center">
  Made with ❤️ for the ML community
</p>
