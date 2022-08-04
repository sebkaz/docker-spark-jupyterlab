# docker-spark-jupyterlab

### Jupiterlab env with Python, Julia, R and Apache Spark


Przygotowanie projketu
```bash
python3 -m cookiecutter https://github.com/sebkaz/jupyterlab-project --no-input --config-file=spark_template.yml --overwrite-if-exists
```

Uruchomienie

```bash
cd spark_jupyterlab
docker-compose up -d --build
```

Zamknięcie: 

```bash
docker compose down
```