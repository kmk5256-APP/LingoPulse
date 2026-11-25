# LingoPulse

**Live voice-to-text translation that feels like a conversation.**

Open-source, privacy-first real-time speech translation with dual-language captions, live waveform visualization, context awareness, and exportable history.

![LingoPulse](https://img.shields.io/badge/status-alpha-orange) ![License](https://img.shields.io/badge/license-MIT-blue) ![Platform](https://img.shields.io/badge/platform-Web-green)

## Why LingoPulse is unique

Most live translators are closed-source, require accounts, or force turn-taking. LingoPulse is designed differently:

- **Continuous dual captions** — Original speech and translation appear side-by-side in real time as you talk.
- **Waveform pulse** — Live audio visualization so you see the voice being captured.
- **Context-aware** — Keeps recent conversation history to improve translation coherence (roadmap).
- **Privacy by default** — Runs entirely in the browser. No accounts, no server storage of audio or text.
- **Open source** — Full code available. Fork, improve, or self-host.
- **Export everything** — Download conversation history as plain text or JSON.
- **Auto language detection** — Optional smart detection of source language.

Perfect for travel, meetings, medical conversations, language learning, or helping family across languages.

## Quick start

1. Open `index.html` in a modern browser (Chrome recommended for best Web Speech API support).
2. Allow microphone access.
3. Select source and target languages.
4. Press **Start Listening** and speak.

For best results use Chrome or Edge. Firefox has limited SpeechRecognition support.

## Features (current alpha)

- Real-time speech-to-text via Web Speech API
- Live translation (using free public translation endpoint)
- Dual-language live display
- Animated waveform while listening
- Language pair selection (50+ languages)
- Conversation history panel
- Export transcript
- Dark/light theme
- Mobile-friendly responsive layout

## Roadmap

- [ ] On-device Whisper.cpp for higher accuracy & offline mode
- [ ] Text-to-speech playback of translation
- [ ] Speaker diarization
- [ ] Context memory for longer conversations
- [ ] iOS / Android native apps (SwiftUI + Android)
- [ ] Multi-user conversation rooms
- [ ] Cultural nuance notes
- [ ] Custom vocabulary / glossary
- [ ] Self-hosted translation backend (LibreTranslate)

## Tech stack

- Pure HTML / CSS / JavaScript (no build step)
- Web Speech API for live transcription
- Free translation API (MyMemory or LibreTranslate)
- Canvas for waveform visualization

## Contributing

Pull requests welcome! Especially improvements to:
- Translation quality & latency
- Offline support
- Accessibility
- Additional language pairs
- Native mobile ports

## License

MIT — use it, fork it, build on it.

Built by Ai2Life Technologies · [ai2life.org](https://ai2life.org)
