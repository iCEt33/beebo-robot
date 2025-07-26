# Beebo Setup

## Requirements
- Python 3.8+
- Microphone + speakers
- OpenAI API key

## Install
```bash
pip install tkinter pyttsx3 openai pygame pillow vosk pyaudio numpy
```

## Run
```bash
python beebo_prototype.py
```

## Configure
1. Configuration tab
2. Paste OpenAI API key  
3. Save Config
4. Load Config

## Test
Say "Mango" → Watch face light up → Ask anything

## Fix Issues
- **No wake word**: Increase mic gain to 3x-4x, make sure wake word is enabled
- **No AI**: Check API key
- **Other**: Idk I was happy it worked for me back to back 😭🙏