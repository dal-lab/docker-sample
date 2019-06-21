FROM python:3.7.3

RUN pip install -U pip

WORKDIR /tmp

COPY requirements.txt /tmp/requirements.txt

RUN pip install -r requirements.txt

WORKDIR /u/myapp

COPY . /u/myapp

CMD flask run --host=0.0.0.0
