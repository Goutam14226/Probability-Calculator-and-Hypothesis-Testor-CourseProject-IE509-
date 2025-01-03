# Probability Calculator and Hypothesis Tester

A comprehensive Python-based toolkit designed for calculating probabilities and conducting hypothesis testing with ease. This project simplifies statistical analysis by integrating essential features into a user-friendly application.

## Features

### 1. **Probability Calculator**
- Supports various probability distributions:
  - Normal
  - Binomial
  - Poisson
  - Geometric
  - Exponential
  - Uniform
  - Gamma
  - Chi-square
- Allows interval-based calculations:
  - \( P(X < x) \)
  - \( P(X > x) \)
  - \( P(a < X < b) \)
- Visualizes distributions with shaded regions for better understanding.

### 2. **Hypothesis Testing**
- Performs:
  - One-sample t-test
  - Two-sample t-test
  - Z-test
- Automatically checks assumptions:
  - Normality using Shapiro-Wilk test.
  - Variance equality using Levene’s test.
- Handles missing values and removes outliers using the IQR method.
- Provides confidence intervals and compares p-values with significance levels.

## How It Works

### Probability Calculations:
1. Select a probability distribution.
2. Enter the required parameters (e.g., mean, standard deviation).
3. Choose the type of probability calculation (e.g., \( P(X < x) \), \( P(a < X < b) \)).
4. View the result along with a visual representation.

### Hypothesis Testing:
1. Input data manually or via a CSV file.
2. Select columns for analysis.
3. Choose the hypothesis test (e.g., one-sample t-test).
4. Enter the significance level (\( \alpha \)) and population parameters.
5. View the results:
   - Test statistic
   - p-value
   - Confidence interval
   - Detailed interpretation

## Technical Details
- **Programming Paradigm**: Object-Oriented Programming (OOP).
- **Libraries Used**:
  - NumPy: Mathematical computations.
  - Pandas: Data manipulation.
  - Matplotlib & Seaborn: Visualizations.
  - SciPy: Statistical tests and calculations.
- **Code Structure**:
  - Separate classes for probability distributions and hypothesis testing.
  - Modular design for easy extensibility.

## Applications
- Academic: Helps students and researchers understand probability and statistical tests.
- Research: Facilitates quick and accurate data analysis with visualization.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/probability-calculator-hypothesis-tester.git
   ```
2. Navigate to the project directory:
   ```bash
   cd probability-calculator-hypothesis-tester
   ```
3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the main Python script:
```bash
python main.py
```

## Future Scope
- Add support for more distributions and statistical tests.
- Integrate machine learning-based anomaly detection.
- Enhance the user interface for non-programmers.

## Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors
- **Goutam Agarwal**
- **Sarvesh Maurya**

## Acknowledgments
- Developed as part of the IE509 (Computation and Programming Lab) course at IIT Bombay.
- Special thanks to Prof. Urban Larsson and Prof. Balamurugan Palaniappan for their guidance.

---
