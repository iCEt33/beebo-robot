# B-b0 Robot 🤖

*Voice-controlled AI assistant with animated face*

## 2-Minute Setup (may vary based on your internet speed)

1. **Download**: Clone or download this repo
2. **Install**: `pip install tkinter pyttsx3 openai pygame pillow vosk pyaudio numpy`
3. **Get Vosk model**: Download [vosk-model-en-us-0.15](https://alphacephei.com/vosk/models) → extract to `models/vosk-model-en-us-0.15/`
4. **Run**: `python beebo_prototype.py`
5. **Add OpenAI key**: Configuration tab → paste API key → Save
6. **Test**: Say "Mango" → ask questions

Done. Working AI robot.

## What You Get

- 🗣️ Say "Mango" to wake up
- 🎭 Animated face (7 different expressions)  
- 🧠 AI conversations (multiple personalities)
- 🔦 Voice commands ("sleep") xd

## Files Included

All animations already included:
- `animations/face_on.gif` - Wake up
- `animations/standby_face.gif` - Idle face
- `animations/blink.gif` - Blinking
- `animations/speaking_face.png` - Talking
- Plus speaking transitions

Should just work right away.

## Troubleshooting

**Can't hear you**: Increase microphone gain in Voice tab
**No AI response**: Add OpenAI API key in Configuration tab
**No animations**: Check files are in `animations/` folder

## What's Next

**Phase 2**: Physical robot build
- Microcontroller 
- OLED screen + speakers
- Battery powered
- Solar recharge
- 3D printed body

**Phase 3**: Advanced features
- Multiple robots talking
- Custom PCB design
- Mobile app control

Want to help test hardware? Open an issue.

Questions? Open an issue.

Hotel? Trivago.