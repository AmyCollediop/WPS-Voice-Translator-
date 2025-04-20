# 🎙️ WPS Voice Translator

WPS Voice Translator is a lightweight prototype that:
- Detects the spoken language (Wolof, Pulaar, or Sérère) from an audio file
- Automatically transcribes the content
- Translates it into French 🇫🇷

This tool is ideal for working with local African languages in a speech-to-text and translation context.

---

## 🚀 Features

- 🎧 Audio input (WAV format)
- 🌍 Language detection using MFCC + Logistic Regression
- 📝 Transcription using OpenAI Whisper
- 🇫🇷 Translation to French using Hugging Face's Transformer models
- 🌐 Web interface via Gradio

---

## 🧰 Installation

```bash
git clone https://github.com/your-username/wps-voice-translator.git
cd wps-voice-translator
pip install -r requirements.txt
