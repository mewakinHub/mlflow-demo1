# MLflow-demo1 
Demo MLflow Experiment with Sklearn model for sample ML modeling and tracking 

## Setup Environment
Using Anaconda Environment
```
conda create -n mlflow-demo python=3.8 --y
conda activate mlflow-demo
pip install -r requirements.txt
```

# MLflow Server
```
mlflow server --host 127.0.0.1 --port 8080
```

# ML Experiment Tracking
## Remote Train by Python exe or Container Schedule
```
python train_model.py
```

## Experiment by Jupyter Notebook or Jupyter Lab
```
jupyter notebook
```

### In case `conda activate mlflow-demo` is not working
1. Manually activate the environment using the full path to the environment's activation script. For example:
   ```
   C:\Users\mew\anaconda3\Scripts\activate.bat C:\Users\mew\anaconda3\envs\mlflow-demo
   ```
   Replace `C:\Users\mew\anaconda3\envs\mlflow-demo` with the actual path to your `mlflow-demo` environment.

2. Once you've activated the environment, you should be able to use Python and other commands within that environment.

add `"C:\Users\mew\anaconda3\envs"` to PATH environment variable