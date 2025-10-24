# MLOPs-MLFlow-Experiments-Tracking
This is repo of complete mlflow experiments

MLFlow Tracking URI 
```python
mlflow.set_tracking_uri('https://dagshub.com/asadullahcreative/MLOPs-MLFlow-Experiments-Tracking.mlflow')

```

import dagshub
dagshub.init(repo_owner='asadullahcreative', repo_name='MLOPs-MLFlow-Experiments-Tracking', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)