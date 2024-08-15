# Identifying Risky Loans

## Project Overview

This project aims to analyze a dataset of loan applications to identify potential risky loans. The primary goal is to build a predictive model that can classify loans as either "risky" or "safe" based on a variety of financial and demographic factors. This analysis helps financial institutions minimize risk by identifying potentially problematic loans before they are approved.

## Table of Contents

- [Project Overview](#project-overview)
- [Data](#data)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [How to Run](#how-to-run)
- [Contributing](#contributing)
- [License](#license)

## Data

The dataset used in this project contains information about various loan applications, including factors such as applicant income, loan amount, credit history, employment status, and more. The data is preprocessed to handle missing values, categorical variables, and outliers.

### Key Features:

- **Applicant Income:** The income of the loan applicant.
- **Loan Amount:** The amount of money requested by the applicant.
- **Credit History:** The credit history of the applicant (binary feature).
- **Employment Status:** The current employment status of the applicant.
- **Property Area:** The area of the property (Urban, Semi-Urban, Rural).
- **Education:** The education level of the applicant (Graduate, Not Graduate).

## Methodology

The project follows the typical data science workflow:

1. **Data Exploration and Cleaning:** Initial data exploration and cleaning to prepare the dataset for modeling.
2. **Feature Engineering:** Creating new features and selecting relevant ones to improve model accuracy.
3. **Modeling:** Building and testing multiple machine learning models to predict the likelihood of a loan being risky.
4. **Evaluation:** Evaluating the models using appropriate metrics like accuracy, precision, recall, and F1-score.
5. **Interpretation:** Analyzing the results to identify key factors contributing to risky loans.

## Technologies Used

- **Programming Language:** R
- **Libraries:** `tidyverse`, `caret`, `randomForest`, `xgboost`, `ggplot2`
- **Machine Learning Algorithms:** Random Forest, XGBoost, Logistic Regression

## Results

The best-performing model in this project was the Random Forest classifier, which achieved an accuracy of XX% and a recall of YY%. The most significant features contributing to the prediction of risky loans were Credit History, Loan Amount, and Applicant Income.

## How to Run

1. Clone the repository:

   \`\`\`bash
   git clone https://github.com/sovitnayak123/identifying-risky-loans.git
   cd identifying-risky-loans
   \`\`\`

2. Install the necessary R packages:

   \`\`\`r
   install.packages(c("tidyverse", "caret", "randomForest", "xgboost", "ggplot2"))
   \`\`\`

3. Run the R script:

   \`\`\`r
   source("identifying_risky_loans.R")
   \`\`\`

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
