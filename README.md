# Comprehensive Meal Timing Study Analysis

## Overview

This project presents a complete statistical analysis of a comprehensive meal timing study examining the effects of different time-restricted feeding (TRF) strategies on glycemic control in individuals with diabetes and prediabetes. The analysis demonstrates advanced statistical techniques and clinical research methodology through a simulated dataset designed for educational purposes.

**⚠️ Note: This is simulated data created for educational and portfolio demonstration purposes. The dataset and results are not from actual clinical research.**

## Study Design

- **Participants**: 200 individuals (120 with type 2 diabetes, 48 prediabetic, 32 normal glucose tolerance)
- **Interventions**: 7 meal timing strategies including various time-restricted feeding windows
- **Primary Outcome**: Change in HbA1c at 12 weeks
- **Secondary Outcomes**: Weight change, adherence, glucose metrics, quality of life measures

### Intervention Groups
- **Early TRF 6h**: 6-hour eating window (early timing)
- **Early TRF 8h**: 8-hour eating window (early timing)  
- **Early TRF 10h**: 10-hour eating window (early timing)
- **Mid TRF 8h**: 8-hour eating window (mid-day timing)
- **Late TRF 8h**: 8-hour eating window (late timing)
- **Control 12h**: 12-hour eating window (standard)
- **Irregular**: No structured eating window

## Analysis Pipeline

### Stage 1: Exploratory Data Analysis (EDA)
- Dataset overview and quality assessment
- Descriptive statistics and distributions
- Missing data evaluation
- Outlier detection using IQR method

### Stage 2: Descriptive Statistics & Group Comparisons
- Baseline characteristics by intervention group
- Statistical tests for baseline balance
- Chi-square tests for categorical variables
- ANOVA for continuous variables

### Stage 3: Primary Efficacy Analysis
- HbA1c change analysis across all groups
- Statistical significance testing (ANOVA)
- Pairwise comparisons with control group
- Effect size calculations (Cohen's d)
- 95% confidence intervals

### Stage 4: Secondary Outcome Analysis
- Weight change, adherence, and quality of life measures
- Glucose metrics analysis
- Correlation analysis with primary outcome
- Composite outcome development

### Stage 5: Subgroup & Interaction Analysis
- Analysis by diabetes status, chronotype, age groups
- BMI and baseline HbA1c subgroups
- Two-way ANOVA for interaction testing
- Propensity score analysis framework

### Stage 6: Dose-Response & Correlation Analysis
- Eating window duration relationships
- Adherence dose-response analysis
- Comprehensive correlation matrix
- Multiple linear regression modeling

### Stage 7: Predictive Modeling
- Random Forest regression and classification models
- Feature importance analysis
- Cross-validation and model performance
- Predictive scenarios for different patient profiles

### Stage 8: Clinical Significance Analysis
- Clinically meaningful threshold analysis
- Number Needed to Treat (NNT) calculations
- Composite clinical outcomes
- Safety analysis and risk stratification

## Key Findings

### Primary Results
- **Early TRF vs Other Strategies**: -0.578% difference in HbA1c change (p<0.001, Cohen's d=-1.64)
- **Most Effective Strategy**: Early TRF 6h achieved -0.852% HbA1c reduction
- **Clinical Significance**: 61% of early TRF participants achieved ≥0.5% HbA1c reduction

### Secondary Results
- Significant weight loss with early TRF strategies
- Higher adherence rates in structured timing groups
- Improved sleep quality and energy levels
- Strong dose-response relationship with eating window duration

## Technical Skills Demonstrated

### Statistical Analysis
- **Descriptive Statistics**: Comprehensive baseline characterization
- **Inferential Statistics**: ANOVA, t-tests, chi-square tests
- **Effect Size Calculations**: Cohen's d, confidence intervals
- **Advanced Methods**: Bootstrap, permutation tests, Bayesian frameworks

### Machine Learning
- **Predictive Modeling**: Random Forest regression and classification
- **Model Validation**: Cross-validation, train-test splits
- **Feature Engineering**: Categorical encoding, interaction terms
- **Performance Metrics**: R², MAE, AUC-ROC, classification reports

### Data Visualization
- Distribution plots and histograms
- Forest plot preparation
- Correlation heatmaps (framework)
- Clinical outcome visualizations

## File Structure

```
├── Complete-Analysis-and-Modeling.ipynb    # Main analysis notebook
├── comprehensive_meal_timing_study_data.csv # Simulated dataset
└── README.md                               # This documentation
```

## Technologies Used

- **Python 3.12+**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **SciPy** - Statistical functions
- **Scikit-learn** - Machine learning algorithms
- **Statsmodels** - Advanced statistical modeling
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Interactive development environment

## Running the Analysis

1. **Prerequisites**: Python 3.12+ with required packages
```bash
pip install pandas numpy scipy scikit-learn statsmodels matplotlib seaborn jupyter
```

2. **Execute Analysis**: Open and run the Jupyter notebook
```bash
jupyter notebook Complete-Analysis-and-Modeling.ipynb
```

3. **Output**: The notebook generates comprehensive statistical results, tables, and model outputs across all 8 analysis stages.

*This analysis represents a comprehensive demonstration of biostatistical and machine learning skills applied to clinical research. While the data is simulated, the methodology and techniques reflect real-world clinical trial analysis standards.*
