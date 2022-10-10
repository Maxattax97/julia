FROM ubuntu:focal

RUN apt-get update && apt-get install -y build-essential python3 python3-pip && apt-get clean && rm -rf /var/lib/apt/lists/*
RUN pip3 install TTS

CMD [ "tts-server" ]
