
## EasyVisa-Ensemble-Learning (Classification)


## Project Evolution

### v1.0.0 — ML Development

Initial machine learning implementation.

### Skills & Tools
------------------
- EDA
- Data Preprocessing
- Bagging Classifier
- Boosting Classifier
- Stacking CLassifier
- Random Forest Classifier
- AdaBoost
- Gradient Boosing
- XGBoost
- HyperParameter Tuning
- Model Performance Evaluation
- Business Recommendations

## Steps to Run the project:
----------------------------

- Local venv environment
  - py -3.12 -m venv .venv
  - source .venv/Scripts/activate  (Git bash)  or .\.venv\Scripts\Activate.ps1 (PowerShell)
  - source .venv/bin/activate (on linux)
  - python -V
  - python -m pip install --upgrade pip
  - python -m pip install -r requirements.txt
  - open notebook and select the local python .venv as kernel
  - run all the cells

  - deactivate if you want to come out of the virtual environment

- Local conda environemnt
  - conda env create -f environment.yaml
  - conda activate env-easyvisa-ensemble-learning
  - open notebook and select the local python .venv as kernel
  - run all the cells

- Inside docker
  - docker build -t easyvisa-ensemble-learning .
  - docker run --rm -p 8889:8888 -e JUPYTER_TOKEN=my-secret-token easyvisa-ensemble-learning
  - Run with gpu
    - check if GPU is available
    - nvidia-smi
    - If avialable,
    - docker run --gpus all --rm -p 8889:8888 -e JUPYTER_TOKEN=my-secret-token easyvisa-ensemble-learning
    - open http://localhost:8889/?token=my-secret-token
    - run the notebook

