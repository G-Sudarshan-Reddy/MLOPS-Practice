# MLOPS-Practice

Introduction
    Step 1 - Install Anaconda

    wget https://repo.anaconda.com/archive/Anaconda3-2022.05-Linux-x86_64.sh - Install
    bash Anaconda3-2022.05-Linux-x86_64.sh - Agreement
    cat ~/.bashrc

    Step 2 - Create new environment using conda
    1. conda create -n mlops python=3.9 -y (Create)
    2. conda activate mlops (activate)

    Step 2 - Create Folders

    Step 3 - Open jupyternotebook
    1. Install pandas
    2. Open a parquet file using url and create a dataframe

MLFLOW
Step 1 - Run MLflow
1. pkill -f mlflow (Kill if any process is running)
1. mlflow ui --backend-store-uri sqlite:///mlflow.db (Run the flow)