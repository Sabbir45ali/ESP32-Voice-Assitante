# ESP32 Voice Assistant with Gemini API

Welcome to the ESP32 Voice Assistant project! This repository showcases the integration of an ESP32 microcontroller with the Gemini API for voice-based interactions. The project uses Python to handle microphone input and speaker output for seamless communication.

---

## 📂 Repository Contents

1. **ESP32 Code**  
   - The ESP32 is programmed to act as the intermediary between the user and the Gemini API.
   - Communicates via Wi-Fi to send and receive voice commands.
   - GPIO control for peripheral hardware.

2. **Python Interface**  
   - Python script for handling audio input (microphone) and output (speaker).
   - Converts user speech to text and sends it to the Gemini API.
   - Processes the API response and converts it back to audio for playback.

3. **Gemini API Integration**  
   - Connects to the Gemini API for natural language processing and AI-powered responses.
   - Handles API authentication and data exchange.

---

## 🔧 Prerequisites

### Hardware Requirements:
- ESP32 microcontroller.
- Microphone and speaker for audio input and output.
- Supporting components: USB cable, breadboard, jumper wires, etc.

### Software Requirements:
- Python 3.x installed on your system.
- Required Python libraries:
  ```bash
  pip install pyaudio requests

```bash
git clone https://github.com/Sabbir45ali/ESP32-voice-Assistant.git
cd ESP32-voice-Assistant
python voice_assistant.py


