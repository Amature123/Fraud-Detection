FROM apache/airflow:2.10.5

USER root
RUN mkdir -p app/models

COPY requirements.txt /temp/requirements.txt
RUN pip install --no-cache-dir -r /temp/requirements.txt

USER airflow