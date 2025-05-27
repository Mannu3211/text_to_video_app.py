# Text to Video Converter (FastAPI)

Convert text to video with voice-over using Google TTS, ElevenLabs, or Amazon Polly. Backend built using FastAPI, suitable for deploying on Render or Railway.

## Features
- Convert Text to Speech using Google TTS, ElevenLabs, Amazon Polly
- Create video with background image and caption
- Preview and download generated video
- Built-in HTML UI (Tailwind CSS)

## Installation

```bash
pip install -r requirements.txt
uvicorn text_to_video_app:app --reload
```

## API Endpoint
`POST /generate-video`

## Deployment (e.g. Render)
Start command:
```
uvicorn text_to_video_app:app --host 0.0.0.0 --port 10000
```