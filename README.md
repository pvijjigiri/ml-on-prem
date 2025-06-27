# How all the folders connect

code            scripts/ , inference/                    Git
Data            data/, models/, *.dvc                    DVC
Pipeline        dvc.yaml, dvc.lock                       DVC
Training logs   mlruns/                                  MLflow
App delivery    Dockerfile, app.py, deployment           Docker/K8s
Scheduling      airflow/dags/                            Apache Airflow