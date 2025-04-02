# 🎙️ Whisper API Audio Transcription Tool

A simple, elegant web-based tool for transcribing audio files using the OpenAI Whisper API. It supports file chunking for large files, customizable output formats (like plain text, SRT, VTT, or verbose JSON), and provides an intuitive user interface to manage the transcription process.

---

## 🚀 Features

- Upload and preview audio files directly in the browser
- Integrate with OpenAI’s Whisper API to transcribe audio
- Support for chunking long audio files into smaller parts
- Choose between multiple output formats:
  - Plain Text
  - SRT (SubRip)
  - VTT (WebVTT)
  - Verbose JSON (with timestamps)
- Real-time progress bar and optional streaming of results
- Optional advanced configuration panel
- No server needed — runs fully in-browser (except API call)

---

## 🖥️ Getting Started

### 📁 Download and Run

1. Save the provided HTML code as `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Edge, etc.).
3. Enter your [OpenAI API Key](https://platform.openai.com/account/api-keys) when prompted.

> ⚠️ Your API key is **not stored** and is sent only to OpenAI's servers during transcription.

---

## 🔧 How to Use

1. Click **"Choose Audio File"** to upload your `.mp3`, `.wav`, `.ogg`, `.m4a`, `.flac`, or `.webm` file.
2. Enter your **OpenAI API key**.
3. (Optional) Click **Advanced Options** to:
   - Enable or disable audio chunking (useful for files >25MB)
   - Set chunk size (in minutes)
   - Select output format
   - Stream results while transcribing
4. Click **Transcribe**.
5. View the results in real-time. When finished, copy or download the transcript.

---

## 📦 Dependencies

- **Browser** with modern JavaScript support
- **OpenAI Whisper API** account and key

No additional libraries or frameworks are required.

---

## 📁 Output Formats

| Format         | Description                           |
|----------------|---------------------------------------|
| `text`         | Plain text of the transcription       |
| `srt`          | SubRip subtitles format               |
| `vtt`          | Web Video Text Tracks (WebVTT) format |
| `verbose_json` | JSON with segment timestamps          |

---

## 🔐 Privacy and Security

- The tool runs entirely in your browser.
- Your API key is used **only** for the transcription request.
- No audio files or keys are uploaded to any server (except OpenAI).

---

## ⚠️ Limitations

- Whisper API does **not** support speaker diarization.
- For speaker identification, consider using services like:
  - [AssemblyAI](https://www.assemblyai.com/)
  - [Rev.ai](https://www.rev.ai/)

---

## 🙌 Acknowledgements

- Built with 💙 by leveraging OpenAI Whisper.
- No external dependencies — just native HTML, CSS, and JavaScript.

---

## 🧪 Future Improvements

- Drag-and-drop file uploads
- File download button for transcript
- Multi-language support
- Auto-save of API key (optional & encrypted)
