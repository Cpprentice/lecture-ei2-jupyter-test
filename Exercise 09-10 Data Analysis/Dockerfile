
FROM quay.io/jupyter/minimal-notebook:python-3.11
USER root
RUN apt-get update && apt-get install -y gcc python3-dev
USER ${NB_UID}
COPY requirements.txt /tmp/requirements.txt
RUN pip install --no-cache-dir -r /tmp/requirements.txt
EXPOSE 8888
