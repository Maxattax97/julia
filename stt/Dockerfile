FROM python:3-slim-bullseye

RUN apt-get update && apt-get install -y build-essential sox libsndfile1 ffmpeg libgomp1 libstdc++ libpthread-stubs0-dev && apt-get clean && rm -rf /var/lib/apt/lists/*
RUN pip3 install coqui-stt-model-manager
# stt

CMD [ "stt-model-manager" ]
EXPOSE 38450
