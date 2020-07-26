# deepstack-analytics
Analytics with deepstack.

A collection of parameterizable Jupyter notebooks (via [Papermill](https://papermill.readthedocs.io/en/latest/)) for performing analytics with Deepstack. Integration to a pipeline via Airflow, and optional isolation using Docker

## Development
```
python3.7 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
venv/bin/jupyter lab
```

## References
* [Airflow papermill docs](https://airflow.readthedocs.io/en/stable/howto/operator/papermill.html)
* [airlow doceker operator](https://airflow.apache.org/docs/stable/_api/airflow/operators/docker_operator/index.html)
* [airflow-with-docker-example](https://medium.com/@tomaszdudek/yet-another-scalable-apache-airflow-with-docker-example-setup-84775af5c451)
* [netfix scheduled notebooks article](https://netflixtechblog.com/scheduling-notebooks-348e6c14cfd6)
