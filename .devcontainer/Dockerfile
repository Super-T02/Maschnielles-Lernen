FROM tensorflow/tensorflow:latest-gpu

WORKDIR /machinelearning

COPY requirements.txt requirements.txt

RUN pip install --upgrade pip

RUN pip install --upgrade -r requirements.txt

EXPOSE 8888