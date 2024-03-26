# chest-cancer-using-mlflow-and-dvc


#WORKFLOW

Update config.yaml

Update secrets.yaml [Optional]

Update params.yaml

Update the entity

Update the configuration manager in src config

Update the components

Update the pipeline

Update the main.py

Update the dvc.yaml


#DAGSHUB
MLFLOW_TRACKING_URI=https://dagshub.com/MOULIKA-SAGIRAJU/chest-cancer-using-mlflow-and-dvc.mlflow 

MLFLOW_TRACKING_USERNAME=MOULIKA-SAGIRAJU 

MLFLOW_TRACKING_PASSWORD=2d55d183e9a0f1f8f2891955dcf02f0e85483773 

python script.py

#gitbash terminal run commands

export MLFLOW_TRACKING_URI=https://dagshub.com/MOULIKA-SAGIRAJU/chest-cancer-using-mlflow-and-dvc.mlflow 

export MLFLOW_TRACKING_USERNAME=MOULIKA-SAGIRAJU 

export MLFLOW_TRACKING_PASSWORD=2d55d183e9a0f1f8f2891955dcf02f0e85483773 


#DVC
dvc init

dvc repro (while using this command uncomment the evaluation.log_into_mlflow())

dvc dag(flowchart)