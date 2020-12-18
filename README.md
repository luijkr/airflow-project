### Virtual environment for Jupyter Notebook

Create virtual environment

```shell script
python3 -m venv venv
source venv/bin/activate
```

Install Jupyter Notebook and add virtual environment

```shell script
pip install notebook
pip install --user ipykernel
python -m ipykernel install --user --name=venv
```

Run Jupyter
```shell script
jupyter notebook
```

### Starting up an Airflow server in Docker

Start Airflow in Docker

```shell script
docker-compose up
```

Shut the server down

```shell script
docker-compose down
```
