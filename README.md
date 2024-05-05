# End-to-End-ML-Project-with-MLflow

Project implementation with pipeline.

## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the app.py

# How to run?

### STEPS:

Clone the repository

```bash
https://github.com/kalpesh-patel-20/End-to-End-ML-Project-with-MLflow.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mlproj python=3.8 -y
```

```bash
conda activate mlproj
```

### STEP 02- install the requirements

```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,

```bash
open up you local host and port
```

## MLflow

##### cmd

- mlflow ui

### dagshub

[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kalpesh2003patel/End-to-End-ML-Project-with-MLflow.mlflow \
MLFLOW_TRACKING_USERNAME=kalpesh2003patel \
MLFLOW_TRACKING_PASSWORD=247a5e8972461026c26da95f46a42599bc30ae6c \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/kalpesh2003patel/End-to-End-ML-Project-with-MLflow.mlflow

export MLFLOW_TRACKING_USERNAME=kalpesh2003patel

export MLFLOW_TRACKING_PASSWORD=247a5e8972461026c26da95f46a42599bc30ae6c

```
