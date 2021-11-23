# Wav2Vec2Align
Wav2Vec2 based forced alignment tool

## Background
This project is based on DSAlign which relies on DeepSpeech for transcribing audio. Since Wav2Vec2 models has been released in many languages this project needed to be adapted to use Wav2Vec2 for transcriptions. Current status is very much WIP and only a Jupyter notebook is available.

Please see the original repository for more information: https://github.com/mozilla/DSAlign

## Changes
* DeepSpeech replaced with Wav2Vec2
* WebRTC VAD relaced with pyannote-audio (https://github.com/pyannote/pyannote-audio)