# Chest_Disease_Classification

- [Data link](https://drive.google.com/file/d/11VhnfeSrU4gZA9LxIKMWfZ393-W_waPu/view?usp=share_link)

### Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components6.
6. Update the pipeline
7. Update the main.py
8. Update the dvc.yaml

How to run?

```
conda create -n chest python=3.8 -y
```

```
conda activate chest
```

```
pip install -r requirements.txt
```

```
python app.py
```

### Mlflow dagshub connection uri

```
MLFLOW_TRACKING_URI=https://dagshub.com/patelshehbaz/Chest_Disease_Classification.mlflow \
MLFLOW_TRACKING_USERNAME=******************** \
MLFLOW_TRACKING_PASSWORD=********************\
python script.py
```

### Run from bash terminal

```
export MLFLOW_TRACKING_URI=https://dagshub.com/patelshehbaz/Chest_Disease_Classification.mlflow
```

```
export MLFLOW_TRACKING_USERNAME=**************************
```

```
export MLFLOW_TRACKING_PASSWORD=**************************
```

### DVC cmd

```
dvc init
dvc repro
dvc dag
```
