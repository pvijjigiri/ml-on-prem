# How all the folders connect

code ---------- scripts/ , inference/ ------------------ Git /n
Data ---------- data/, models/, *.dvc ------------------ DVC /n
Pipeline ------ dvc.yaml, dvc.lock --------------------- DVC /n
Training logs - mlruns/ -------------------------------- MLflow /n
App delivery -- Dockerfile, app.py, deployment --------- Docker/K8s /n
Scheduling ---- airflow/dags/ -------------------------- Apache Airflow /n