 ## 🎥 Video Journal Emotion Analyzer

This project is a FastAPI-based web service that accepts a public video URL (typically a user-recorded personal journal video), extracts the audio, transcribes it using Whisper, detects dominant emotions using DeepFace, and generates a summary and emotional insights using Cohere's NLP API.

> ⚠️ **Note:** This project is still under development. Model tuning is ongoing, so outputs might occasionally be off or inaccurate.

---

## 💡 Features

- 📥 Downloads video from a URL and processes it.
- 🔊 Extracts audio using `moviepy`.
- 🧠 Transcribes speech using OpenAI's `whisper`.
- 🧠 Summarizes and generates insights using `cohere`.
- 😢 Detects dominant emotion using `deepface`.
- 🧪 Built with `FastAPI` for easy API usage.

---
