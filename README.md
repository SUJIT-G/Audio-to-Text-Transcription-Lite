 Audio to Text (Transcription Lite)

**Convert speech into text in real time with transcription, timestamps, and export options.**

## 🚀 Quick summary

Transcription Lite is a small, client-side web app that uses the browser Speech Recognition API to convert microphone audio to text in real time. It shows live (interim) and finalized transcripts with timestamps and provides export options (TXT, JSON), copy-to-clipboard, and persistence to `localStorage`.

## Features

- Real-time speech → text transcription
- Interim (live) and final results
- Per-segment timestamps (HH:MM:SS)
- Export as `.txt` or `.json`
- Copy to clipboard and clear transcript
- Language selection
- Works fully client-side (no server required)

## Demo

Open `index.html` in a modern desktop browser (Chrome / Edge recommended). The app requires microphone access.

> **Note:** The Web Speech API is best supported in Chromium-based browsers. Firefox has limited or no support for SpeechRecognition in some versions.

## Installation / Usage

1. Clone or download the repo.

```bash
git clone https://github.com/<your-username>/audio-to-text-transcription-lite.git
cd audio-to-text-transcription-lite