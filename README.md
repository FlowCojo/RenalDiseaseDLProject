# Renal Disease Deep Learning Project

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml
9. app.py

# How to run?

### STEPS:
Clone the repository

```bash
https://github.com/FlowCojo/
RenalDiseaseDLProject
```
### STEP 01 - Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```

### STEP 02 - install the requirements
```bash
pip install -r requirements.txt
```
### DvC cmds

1. dvc init
2. dvc repo
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)

### STEP 03 - run the app
```bash
python app.py
```
