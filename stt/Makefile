all: venv-stt
	source venv-stt/bin/activate && stt-model-manager

venv-stt:
	python3 -m venv venv-stt
	source venv-stt/bin/activate
	python -m pip install -U pip
	python -m pip install coqui-stt-model-manager
