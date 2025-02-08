[![CI](https://github.com/SYSTRAN/faster-whisper/workflows/CI/badge.svg)](https://github.com/SYSTRAN/faster-whisper/actions?query=workflow%3ACI) [![PyPI version](https://badge.fury.io/py/faster-whisper.svg)](https://badge.fury.io/py/faster-whisper)

# Unhallucinated Faster Whisper

### Install the package
```
pip install unhallucinated-faster-whisper
```
### Usage (Same as Faster Whisper)
```
from faster_whisper import WhisperModel 
model_size = "turbo"
model = WhisperModel(model_size, device="cpu")  
```

### Enabling the Unhallucination Feature 
Simply pass unhallucinated=True when transcribing
```
segments, info = model.transcribe("voice.mp3", unhallucinated=True)
```

### Model Compatibility

Compatible with all Whisper models.
