[![CI](https://github.com/SYSTRAN/faster-whisper/workflows/CI/badge.svg)](https://github.com/SYSTRAN/faster-whisper/actions?query=workflow%3ACI) [![PyPI version](https://badge.fury.io/py/faster-whisper.svg)](https://badge.fury.io/py/faster-whisper)

# Unhallucinated Faster Whisper

# Install the package
pip install unhallucinated-faster-whisper

# Use just like normal faster-whisper
from faster_whisper import WhisperModel 
model_size = "turbo"
model = WhisperModel(model_size, device="cpu")  

# Just pass unhallucinated=True if you want to use the new feature
segments, info = model.transcribe("voice.mp3", unhallucinated=True)

# Models
Works with every Whisper model
