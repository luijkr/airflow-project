### Virtual environment for Jupyter Notebook

Create virtual environment
```bash
python3 -m venv airflow-venv
source airflow-venv/bin/activate
```

Install Jupyter Notebook and add virtual environment

```bash
pip install notebook
pip install --user ipykernel
python -m ipykernel install --user --name=airflow-venv
```

Run Jupyter
```bash
jupyter notebook
```