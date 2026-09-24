# PROG8245-Lab-DataEngineering&EDA
Lab - Data Engineering & EDA with Python, SQL, and Pandas

Objective
You will practice hands-on data engineering by:

Connecting to a free cloud SQL database

Collecting, cleaning, transforming, and scaling real data using Python and Pandas

Conducting exploratory data analysis (EDA)

Creating and explaining insightful visualizations

# Quick Start
1. Clone the repository to your local machine using the following command:
    ```
    git clone https://github.com/your-username/PROG8245-Lab-DataEngineering&EDA.git
    ```
2. Navigate to the project directory:
    ```
    cd PROG8245-Lab-DataEngineering&EDA
    ```
3. Install the required dependencies using pip:
    ```
    python -m venv .venv
    .\.venv\Scripts\Activate.ps1
    pip install -r requirements.txt
    ```
4. Connection String is included in the .env file.
    The .env file contains the connection string to the cloud SQL database. Make sure to keep this file secure and do not share it publicly.
    There .gitignore file is included to prevent the .env file from being tracked by Git.
    The .env file will be zipped with password and emailed to you. Please unzip the file and place it in the root directory of the project.

5. Run the Jupyter Notebook to start exploring the data:
    ```
    jupyter notebook
    ```