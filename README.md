# H-1B Visa Petitions Analysis (2011-2016)

A comprehensive data analysis of 3+ million H-1B visa petitions using Python and Seaborn for statistical visualization.

## 📊 Dataset Overview

- **Records**: 3,002,458 H-1B petitions
- **Time Period**: 2011-2016
- **Features**: 11 columns including employer, job title, salary, location, case status
- **Size**: 252MB+ dataset

## 🔍 Analysis Highlights

### Key Insights
- **Approval Rate**: Overall certification rate analysis with temporal trends
- **Geographic Distribution**: Concentration in tech hubs (CA, NY, TX)
- **Salary Patterns**: Correlation between wages and approval rates
- **Top Employers**: Technology and consulting firms dominate
- **Risk Analysis**: Employer risk profiles and anomaly detection

### Statistical Methods
- Chi-square tests for categorical associations
- Confidence intervals for approval rates
- Correlation analysis and heatmaps
- Outlier detection using IQR method
- Market concentration (HHI) analysis

## 📈 Visualizations (30+ Charts)

All visualizations created using **Seaborn** exclusively:
- Temporal trends and seasonal patterns
- Geographic heatmaps and distributions
- Salary analysis and box plots
- Employer performance metrics
- Executive dashboard summary
- Risk assessment visualizations

## 🛠️ Technical Stack

```python
pandas>=1.3.0
numpy>=1.21.0
seaborn>=0.11.0
matplotlib>=3.4.0
scipy>=1.7.0
```

## 📁 Project Structure

```
h1b-analysis/
├── notebooks/
│   └── h1b_analysis.ipynb          # Main analysis notebook
├── data/
│   └── h1b_visa_petitions.csv      # Dataset (not included)
├── reports/
│   └── executive_summary.pdf       # Key findings summary
└── README.md
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/h1b-analysis.git
   cd h1b-analysis
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download dataset**
   - Place your H-1B dataset in the `data/` folder
   - Update file path in the notebook

4. **Run analysis**
   ```bash
   jupyter notebook notebooks/h1b_analysis.ipynb
   ```

## 📋 Key Findings

- **85%+** overall approval rate with yearly variations
- **California** leads with 40%+ of all petitions
- **$75,000** average prevailing wage across all years
- **Technology sector** dominates employer rankings
- **Full-time positions** show higher approval rates

## 📊 Sample Visualizations

The notebook includes comprehensive analysis covering:
- ✅ Case status distribution and trends
- 🌍 Geographic concentration analysis
- 💰 Salary distribution and growth patterns
- 🏢 Employer performance and risk assessment
- 📈 Predictive analytics and statistical tests

## 🎯 Business Applications

- **HR Strategy**: Inform H-1B filing strategies
- **Policy Analysis**: Understand immigration trends
- **Risk Assessment**: Employer success probability
- **Market Research**: Tech industry labor patterns

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📧 Contact

For questions or suggestions, please open an issue or contact [your-email@example.com].

---

**Note**: This analysis is for educational and research purposes. Dataset not included due to size - please obtain from official sources.
