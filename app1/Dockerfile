FROM python:3.8

WORKDIR /app1
COPY requirements.txt /app1/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /app1/requirements.txt

COPY . /app1

CMD bash -c "while true; do sleep 1; done"