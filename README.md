# 🔊 Real-Time Audio Intent Classification

This project captures live voice input, transcribes it to text using the **Whisper-small** model, and classifies the spoken intent using a **pre-trained NLP model** from Hugging Face. It’s designed for real-time use in applications like customer support, smart assistants, and e-commerce platforms.

---

## 🚀 Overview

- **Voice Recording:** Records audio until the user stops speaking (detects 2 seconds of silence).  
- **Speech-to-Text:** Uses Hugging Face’s `openai/whisper-small` model to transcribe speech.  
- **Intent Detection:** Classifies the transcribed text using the `Serj/intent-classifier` model.  
- **Real-time Output:** Displays the spoken text and predicted intent instantly.

---

## 🧠 Key Features

- 🎙️ Real-time microphone input with automatic silence detection  
- 🧾 Accurate transcription with Whisper-small  
- 🤖 Intent classification using pre-trained transformer model (few-shot learning, no fine-tuning)  
- ⚡ Fast inference under 2 seconds  
- 🔧 Modular and extendable design for various voice-based applications

---

## 🛠️ Tech Stack

- Python  
- Hugging Face Transformers & Torchaudio (for Whisper)  
- `sounddevice`, `numpy`, `librosa`, `soundfile`, `matplotlib` (for audio recording and processing)  
- PyTorch (`torch`) for model inference  

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/audio-intent-classifier.git
cd audio-intent-classifier
