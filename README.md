# 🧠 Speech-to-Text Analysis & Semantic Chunking

This Jupyter Notebook explores advanced speech-to-text processing through two major tasks:

## 🎬 Part 1: Semantic Chunking of YouTube Audio
- Downloaded and extracted audio from a YouTube video using `yt-dlp`.
- Transcribed speech to text using OpenAI Whisper.
- Performed **time-aligned transcription** and **speaker diarization** using PyAnnote.
- Applied **semantic chunking** based on sentence structure, speaker turns, and conjunctions for meaningful text segmentation.

## 📖 Part 2: Exploratory Analysis of New Testament Audio
- Aligned audio and transcript at the **word and phoneme level**.
- Conducted detailed **word-level speech analysis**, including misalignment, pauses, and anomalies.
- Detected **audio anomalies** (like silence, distortion) using waveform and spectral analysis.
- Performed **text bias and linguistic analysis** to examine potential content skew.
- Analyzed **audio quality**, **duration trends**, and **phoneme usage**.

## 🔧 Tech Stack
- Python, Jupyter
- OpenAI Whisper, PyAnnote, SpaCy, NLTK, Librosa, YouTube-DLP
- Matplotlib, Seaborn for visualization

## 📌 Future Work
- Automate semantic segmentation for long-form educational videos.
- Extend phoneme-based alignment to multilingual corpora.
