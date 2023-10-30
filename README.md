# data-pipeline

# confluent-kafka-python

This repo publish and consume data to and from kafka confluent in json format.

Step1: Create a conda environment

```
conda create -p venv python==3.8 -y
```

Step2:

```
conda activate venv/
```

Step3:

```
pip install -r requirements.txt
```

Cluster Environment Variable

```
API_KEY
API_SECRET_KEY
BOOTSTRAP_SERVER
```

Schema related Environment Variable

```
SCHEMA_REGISTRY_API_KEY
SCHEMA_REGISTRY_API_SECRET
ENDPOINT_SCHEMA_URL
```

Data base related Environment Variable

```
MONGO_DB_URL
```

Build docker image

```
docker build -t data-pipeline:lts .
```
