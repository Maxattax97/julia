all: julia_tts

.PHONY=jula_tts
julia_tts: coqui
	docker build -t jula_tts .

.PHONY=coqui
coqui:
	cd TTS/ && docker build -t tts .
