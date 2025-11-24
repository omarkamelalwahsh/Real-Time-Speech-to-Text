
# Real-Time Audio Transcription with Gradio and Transformers

This project allows you to record audio from your microphone and get real-time transcription using Hugging Face's **Transformers** automatic speech recognition (ASR) pipeline and **Gradio** for the interface.

---

## Features

- Record audio directly from your microphone.
- Real-time transcription.
- Keeps previous transcriptions in session (stateful transcription).

---

## Requirements

- Python 3.8+
- Gradio
- Transformers
- Torch

Install dependencies:

```bash
pip install gradio transformers torch
