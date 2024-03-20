# Predicting ICO Success with Machine Learning

This project explores the application of various machine learning (ML) models to predict the success of Initial Coin Offerings (ICOs). ICOs are a novel way of fundraising for blockchain-based projects, where success is critical for investors and project teams alike. The goal is to create predictive models that accurately classify ICO outcomes based on multiple factors, thereby aiding investment decisions and resource allocation.

## Project Components

- **Jupyter Notebook (`data_understanding.ipynb`)**: Explores the ICO dataset, including data quality checks, outlier detection, and preliminary data visualizations. It provides a foundational understanding of the data and its characteristics.

- **PDF Report (`201684933.pdf`)**: A comprehensive report detailing the motivation, methodology, model evaluation, and conclusions of the machine learning analysis performed on the ICO dataset. This report contains a thorough exploration of the data, preprocessing steps, model implementation, and an insightful discussion on the results obtained from various ML models, including Decision Trees, Random Forest, SVM, and ANN.

## Key Highlights

- **Data Exploration**: Initial analysis to understand the dataset's structure, detect outliers, and identify key variables influencing ICO success.

- **Preprocessing**: Detailed preprocessing steps, including handling missing values, data type corrections, normalization, and one-hot encoding to prepare the dataset for modeling.

- **Modeling**: Application of multiple machine learning techniques to predict ICO success. The models explored include Decision Trees with AdaBoost, Random Forest, Support Vector Machines (SVM), and Artificial Neural Networks (ANN).

- **Evaluation and Insights**: The models' performance is evaluated using accuracy, AUC, and F1 scores. Random Forest and Decision Trees with AdaBoost showed promising results, highlighting their potential in predicting ICO success.

## Dataset

The dataset includes a variety of features related to ICOs, such as start and end dates, the number of coins issued, team size, and the presence of promotional materials like videos, GitHub repositories, and Reddit pages. The target variable is the success of the ICO, categorized as 'Yes' or 'No'.

## Requirements

To run the notebook and replicate the findings, the following libraries are required:
- Pandas
- NumPy
- Seaborn
- Matplotlib
- scikit-learn
- missingno

## Usage

1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed, or use Google Colab to open the `.ipynb` file.
3. Install the required Python libraries mentioned above.
4. Run the notebook cells sequentially to explore the data, preprocess it, and evaluate the different machine learning models.

## Conclusion

The analysis provides valuable insights into the factors contributing to ICO success and demonstrates the applicability of machine learning in the cryptocurrency domain. The project underscores the potential of data-driven approaches in enhancing decision-making processes in ICO investments.
