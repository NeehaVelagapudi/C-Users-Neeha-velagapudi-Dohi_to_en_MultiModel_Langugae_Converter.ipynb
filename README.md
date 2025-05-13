
# 📝 Multimodal Language Converter (Hindi to English)

This project is a Multimodal Language Converter that translates Hindi text or speech into English.
It uses Helsinki-NLP/opus-mt-hi-en, a Transformer-based model for translation, and speech_recognition for converting speech to text.
The output can be optionally summarized and then converted into speech using gTTS or pyttsx3 for audio playback.
This notebook demonstrates a **Multimodal Language Converter** that translates **Hindi to English**, using both **text and speech inputs**. It integrates:

- Text-based translation  
- Speech-to-text conversion  
- Language translation (Hindi → English)  
- Output via both **text and synthesized speech**

---

## 🚀 Features

- **Multimodal Input**  
  Accepts either:
  - Text input (Hindi)
  - Audio input (speech) which is converted to Hindi text

- **Language Translation**  
  Translates Hindi to English using a pre-trained Transformer model (`Helsinki-NLP/opus-mt-hi-en`)

- **Text Summarization (Optional)**  
  Summarizes the translated English text using models from Hugging Face or the `sumy` library

- **Text-to-Speech Output**  
  Converts the translated or summarized English text into speech using `gTTS` or `pyttsx3`

---

## 🛠️ Technologies and Libraries Used

| Library               | Purpose                                  |
|-----------------------|------------------------------------------|
| `transformers`        | Translation with pre-trained models      |
| `speech_recognition`  | Convert spoken Hindi to text             |
| `gTTS` / `pyttsx3`    | Text-to-speech conversion                |
| `sumy`                | Text summarization                       |
| `IPython.display`     | In-notebook audio playback               |
| `tkinter` *(optional)*| GUI support in standalone version        |

---

## 📂 Project Workflow

1. **User Input**  
   - Type or record a sentence in Hindi

2. **Speech-to-Text (if applicable)**  
   - Convert speech to Hindi text using microphone input

3. **Translation**  
   - Translate Hindi text to English using NLP models

4. **Summarization** *(optional)*  
   - Summarize the translated content

5. **Text-to-Speech**  
   - Play or download the English output as audio

---

## 📌 Use Cases

- Language learning assistants  
- Accessibility for non-English speakers  
- Travel and communication tools  
- Educational language converters

---

## 🔧 Setup Instructions (for local use)

Install the required libraries:

```bash
pip install transformers
pip install speechrecognition
pip install gTTS
pip install sumy
pip install pyttsx3
```

Ensure:
- A working microphone (for speech input)
- Internet connection (for loading models and TTS)

---

## 📁 File Structure

```
Multimodal_Language_Converter.ipynb
README.md
requirements.txt
audio_input.wav        # Optional
```

---

## ✍️ Author

**Velagapudi Neeha**  
AI & NLP Enthusiast  
