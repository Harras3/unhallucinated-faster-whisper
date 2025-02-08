
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
