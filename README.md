# HR Analytics: Identifying Job Change Factors for Aspiring Data Scientists

This project aims to identify the key factors that influence individuals to change their current jobs in favor of becoming data scientists. By analyzing various attributes related to credentials, demographics, and experience, the goal is to build models that can predict the probability of job change and interpret the underlying factors affecting this decision.

## Project Overview

The dataset comprises 19,158 instances and 14 attributes, including information about candidates' cities, genders, relevant experience, education levels, major disciplines, company sizes, company types, last new jobs, and training hours. The target variable indicates whether a candidate is looking to change jobs to become a data scientist.

## Dataset Information

- **Source:** The data is in ASCII CSV format.
- **Instances:** 19,158
- **Attributes:** 14 predictor attributes plus 1 target attribute

## Attribute Information

- `enrollee_id`: Unique ID for candidate
- `city`: City code
- `city_development_index`: Development index of the city (scaled)
- `gender`: Gender of candidate
- `relevant_experience`: Relevant experience of candidate
- `enrolled_university`: Type of University course enrolled if any
- `education_level`: Education level of candidate
- `major_discipline`: Education major discipline of candidate
- `experience`: Candidate's total experience in years
- `company_size`: Number of employees in current employer's company
- `company_type`: Type of current employer
- `last_new_job`: Difference in years between previous job and current job
- `training_hours`: Training hours completed
- **Target Attribute:**
  - `target`: 0 – Not looking for job change, 1 – Looking for a job change

## Project Goals

1. **Data Preprocessing:** Cleaning and preparing the data for analysis.
2. **Exploratory Data Analysis (EDA):** Understanding the underlying patterns and relationships in the data.
3. **Model Development:** Building and evaluating various machine learning models to predict job change probability.
4. **Model Interpretation:** Identifying key factors that influence a candidate's decision to switch to a data scientist role.
5. **Insights and Recommendations:** Providing actionable insights for HR departments to retain talent and support career development.

## Repository Structure

- `data/`: Contains the dataset.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model development.
- `models/`: Saved models and scripts for model training and evaluation.
- `scripts/`: Helper scripts for data processing and analysis.
- `README.md`: Project overview and instructions.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/HR_Analytics_Job_Change_Data_Scientists.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the data preprocessing and model training scripts in the `notebooks/` directory.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or improvements.

## License

This project is licensed under the MIT License.
