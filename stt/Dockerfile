FROM continuumio/miniconda3

RUN apt-get update && apt-get install -y build-essential && apt-get clean && rm -rf /var/lib/apt/lists/*
RUN pip3 install coqui-stt-model-manager

CMD [ "stt-model-manager" ]
EXPOSE 38450
