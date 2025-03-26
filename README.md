# Project-Capstone-Project
This project based MLOps project will help you to lay a strong foundation starting from intuition building to learning trending mlops tools and finally do industry grade MLOps projects !!!


## Install Cookiecutter
Cookiecutter -c v1 https://github.com/drivendataorg/cookiecutter-data-science

## Experiment tracking using Dags and mlflow

url = 'https://dagshub.com/coding-fame/my-first-repo/experiments'
``python 
import dagshub
dagshub.init(repo_owner='coding-fame', repo_name='my-first-repo', mlflow=True)
```

``python 
import mlflow
with mlflow.start_run():
  # Your training code here...
  mlflow.log_metric('accuracy', 42)
  mlflow.log_param('Param name', 'Value')
```