
FROM quay.io/jupyter/minimal-notebook:python-3.11
COPY requirements.txt /tmp/requirements.txt
RUN pip install --no-cache-dir -r /tmp/requirements.txt
EXPOSE 8888
