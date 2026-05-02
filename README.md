# 📊 Insurance Premium Analysis: Exploratory Data Analysis

A comprehensive exploratory data analysis (EDA) of insurance premium data, investigating the key factors that influence healthcare costs. This project analyzes relationships between demographic factors, lifestyle choices, and insurance premiums using Python's data science stack.

## 🎯 Key Findings

- **Smoking is the strongest predictor** of insurance premium, with smokers paying on average **4x more** than non-smokers
- Premium distribution is **right-skewed**, with most customers paying lower premiums and a small subset paying significantly higher costs
- **Age and BMI show positive correlations** with premium, but their impact varies dramatically by smoking status
- Number of children and geographic region have minimal impact on premium costs
- The **age-premium relationship is non-linear** for smokers, showing sharp increases in certain age brackets

## 📁 Project Structure

```
insurance-eda/
├── data/
│   └── insurance_synthetic_data.csv    # Dataset
├── insurance_eda.ipynb                 # Main analysis notebook
├── requirements.txt                     # Python dependencies
└── README.md                            # This file
```

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualization

## 📊 Dataset

The dataset contains **synthetic insurance data** with the following features:

| Feature | Type | Description |
|---------|------|-------------|
| `age` | Numeric | Beneficiary's age |
| `gender` | Categorical | Insurance beneficiary's gender (male/female) |
| `bmi` | Numeric | Body Mass Index |
| `children` | Numeric | Number of dependents |
| `smoker` | Categorical | Smoking status (yes/no) |
| `region` | Categorical | Beneficiary's residential area (northeast, northwest, southeast, southwest) |
| `premium` | Numeric | Medical insurance premium (target variable) |

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/insurance-eda.git
cd insurance-eda
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook insurance_eda.ipynb
```

## 📈 Analysis Overview

The notebook addresses **30 analytical questions** organized into four categories:

### 1. Data Exploration (Q1-Q5)
- Dataset dimensions and structure
- Data types and column identification
- Missing value analysis
- Unique value counts

### 2. Univariate Analysis (Q6-Q15)
- Distribution analysis for all variables
- Outlier detection
- Summary statistics
- Categorical variable frequencies

### 3. Bivariate Analysis (Q16-Q22)
- Impact of smoking on premium
- BMI vs premium relationship
- Age vs premium patterns
- Gender and regional differences

### 4. Multivariate Analysis (Q23-Q30)
- Correlation matrix and heatmap
- Feature importance ranking
- Grouped statistical analysis
- Interaction effects between variables

## 💡 Insights & Business Value

This analysis reveals actionable insights for insurance companies:

1. **Risk Stratification**: Smoking status is the most critical factor for premium calculation
2. **Demographic Targeting**: Age and BMI show predictable patterns that can inform pricing models
3. **Regional Equity**: Minimal regional variation suggests consistent pricing across geographies
4. **Family Planning**: Number of children has negligible impact on healthcare costs

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/YOUR_USERNAME/insurance-eda/issues).

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Your Name**
- GitHub: [@YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/your-profile)

## 🙏 Acknowledgments

- Dataset: Synthetic insurance data generated for educational purposes
- Inspiration: Healthcare analytics and actuarial science research

---

⭐ **If you found this project helpful, please consider giving it a star!**
