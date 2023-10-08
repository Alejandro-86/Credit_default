# Credit Risk Prediction Project

This project aims to develop a credit risk prediction model using time series data. The goal is to forecast the likelihood of loan defaults based on historical time series data of borrowers' financial behavior. The project combines time series analysis, data preprocessing, feature engineering, and machine learning for risk assessment.

## Project Structure

The project is organized into the following directories and files:

- **data/**: Contains raw data, processed data, and model-related data.
    - `raw_data/`: Raw data on borrowers and credit scores.
    - `processed_data/`: Cleaned and preprocessed data.
    - `model_data/`: Trained machine learning model and model evaluation metrics.

- **notebooks/**: Jupyter Notebooks for each major project step.
    - `01-data-preprocessing.ipynb`: Data preprocessing notebook.
    - `02-feature-engineering.ipynb`: Feature engineering notebook.
    - `03-model-training.ipynb`: Model training notebook.
    - `04-model-evaluation.ipynb`: Model evaluation notebook.

- **src/**: Python scripts for data preprocessing, feature engineering, model training, and evaluation.

- **reports/**: Project documentation and findings.
    - `project_report.pdf`: Detailed project report summarizing findings.
    - `figures/`: Directory for project visualizations.

- `requirements.txt`: List of project dependencies.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/credit-risk-prediction.git
   cd credit-risk-prediction
    ```

2. Create a virtual environment and install dependencies:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
    ```

3. Dependencies can be updated using `pip freeze > requirements.txt`.


4. Run the Jupyter Notebooks in the `notebooks/` directory to reproduce the project results.


Created by [Alex ALonso](aalonsocanales@gmail.com)
