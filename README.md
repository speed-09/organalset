# MP3/MP4 to SRT Converter

This is a simple, private, and secure web application to convert your audio and video files into SRT subtitle format using Gemini 1.5 Flash and Groq Whisper V3 APIs.

## Features
- **File Support**: Upload MP3 or MP4 files directly.
- **AI Powered**: Choose between Gemini (Google) or Groq (Whisper) for transcription.
- **Secure**: All API calls are made directly from your browser. Your API keys are never stored on any server (only locally in your browser's storage).
- **Easy Download**: One-click button to download your generated `.srt` file.

## How to use on GitHub
1. Create a new repository on GitHub (e.g., `media-to-srt`).
2. Upload the `index.html` file to the repository.
3. Go to **Settings** > **Pages**.
4. Under **Build and deployment**, set the source to `Deploy from a branch`.
5. Select the `main` branch and the `/ (root)` folder, then click **Save**.
6. Wait a minute, and your website will be live at `https://your-username.github.io/media-to-srt/`.

## API Keys
You will need your own API keys to use this tool:
- **Gemini API Key**: Get it from [Google AI Studio](https://aistudio.google.com/app/apikey).
- **Groq API Key**: Get it from [Groq Console](https://console.groq.com/keys).

## Limitations
- **File Size**: Since the browser handles the upload directly to the AI providers, there is a limit (usually 25MB - 100MB depending on the provider and browser).
- **CORS**: Some API requests might be blocked by browser security if the API provider doesn't allow direct browser access. (Gemini and Groq currently support this via their standard endpoints).
