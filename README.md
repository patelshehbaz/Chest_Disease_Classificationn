# Chest_Disease_Classification

we've developed a cutting-edge solution to classify chest X-ray images, helping medical professionals quickly identify patients suffering from adenocarcinoma and distinguish them from normal cases. Leveraging the powerful VGG16 model, we've fine-tuned it on our custom dataset of chest CT scan images for optimal accuracy.

- [Data link](https://drive.google.com/file/d/11VhnfeSrU4gZA9LxIKMWfZ393-W_waPu/view?usp=share_link)

How to run?

```
git clone https://github.com/patelshehbaz/Chest_Disease_Classificationn.git

```

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

🛠 Tech Stack:

- TensorFlow Framework: For building and training our deep learning model.
- Python: The core programming language that powered our project.
- MLflow: This was invaluable for tracking experiments, comparing different models, and hyperparameter tuning, ensuring we always had the best performing model.
- DVC (Data Version Control): Our go-to MLOps tool for efficient pipeline tracking. It was crucial for maintaining our project's integrity over time.
- Google Drive: Our choice for data ingestion, facilitating seamless access to our dataset for training and validation.
- Flask: Used to develop the web application interface for interacting with our model, making it accessible to users and researchers.

### Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components6.
6. Update the pipeline
7. Update the main.py
8. Update the dvc.yaml

### Mlflow dagshub connection uri

```

MLFLOW_TRACKING_URI=https://dagshub.com/patelshehbaz/Chest_Disease_Classification.mlflow \
MLFLOW_TRACKING_USERNAME=**\*\*\*\***\*\*\*\***\*\*\*\*** \
MLFLOW_TRACKING_PASSWORD=**\*\*\*\***\*\*\*\***\*\*\*\***\
python script.py

```

### Run from bash terminal

```

export MLFLOW_TRACKING_URI=https://dagshub.com/patelshehbaz/Chest_Disease_Classification.mlflow

```

```

export MLFLOW_TRACKING_USERNAME=\***\*\*\*\*\*\*\***\*\*\***\*\*\*\*\*\*\***

```

```

export MLFLOW_TRACKING_PASSWORD=\***\*\*\*\*\*\*\***\*\*\***\*\*\*\*\*\*\***

```

### DVC cmd

```

dvc init
dvc repro
dvc dag

```
