FROM python:3-slim-bullseye

RUN apt-get update && apt-get install -y build-essential sox libsndfile1 ffmpeg && apt-get clean && rm -rf /var/lib/apt/lists/*
RUN pip3 install TTS

CMD [ "tts-server" ]
