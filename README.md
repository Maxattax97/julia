# Julia

Also called Jules for short, Julia is a Virtual Assistant (VA).

## Goals

- A privacy-respecting VA
- Portable, due to it's networked nature
- Uses existing works in TTS, STT, Semantic engines, public API's
- Easily adapted and extended for the Open Source community

## Architecture

Ideally this would be best written in Python.

- Mimics Amazon Alexa skills API
- Uses Intents
- Intents have several sample strings
- String similarity is used to determine what is closest to what was uttered
  - Or this? https://www.sbert.net/
- String is given to command logic for processing
- Headless vs. with head (i.e. can use GUIs like open a browser tab)
  - https://albertlauncher.github.io/
- Uses a docker swarm
- Container for high quality text to speech AI with API
- Container for high quality speech to text AI with API
- Abstract API away, so we can change container
- Locally ran client
- Sends requests to cloud
- Returns with response and Command and Control

## Commands

Feature parity with Siri would be nice:
https://www.computerworld.com/article/3261408/hey-siri-142-useful-voice-commands-for-siri.html

## Existing Projects

- https://github.com/CorentinJ/Real-Time-Voice-Cloning
- https://www.sbert.net/
- https://albertlauncher.github.io/
- https://github.com/coqui-ai/TTS
