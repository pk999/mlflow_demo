# mlflow_demo
https://dagshub.com/pk999/mlflow_demo.mlflow

##
import dagshub
dagshub.init(repo_owner='pk999', repo_name='mlflow_demo', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)