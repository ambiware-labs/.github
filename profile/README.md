# Loqa Labs

**Local-first AI voice platform for privacy-conscious users.**

## 🎯 Current Focus: Meeting Transcription

We're building AI-powered meeting transcription with Obsidian integration.

**[loqa-meetings](https://github.com/loqalabs/loqa-meetings)** - Record, transcribe, and summarize meetings 100% locally

- 🎙️ Live recording or process existing audio
- 📝 Incremental transcription (see partial transcript during meeting)
- 🤖 AI summaries (key points, decisions, action items)
- 👥 Speaker diarization
- 📓 Obsidian integration
- 🔒 100% local, privacy-first

**Status**: Week 1 of 10-week MVP

---

## 🏗️ Architecture

**[loqa-core](https://github.com/loqalabs/loqa-core)** - Stable foundation (Go)

- Speech-to-Text (Whisper)
- LLM inference (Ollama)
- Text-to-Speech (Kokoro)
- NATS message bus
- WASM skills runtime

**[loqa-meetings](https://github.com/loqalabs/loqa-meetings)** - Active development (Rust)

- Meeting recording & transcription
- Markdown generation
- Obsidian integration

---

## 🗺️ Roadmap

- **Phase 1** (Now): Meeting transcription ✅ In progress
- **Phase 2** (Q1 2026): Chat assistant with RAG over Obsidian vault
- **Phase 3** (Q2 2026): Real-time voice chat
- **Phase 4** (Q3 2026): Full voice assistant

See [Vision & Roadmap](https://github.com/loqalabs/loqa-meta/blob/main/docs/vision.md) for details.

---

## 💡 Philosophy

- **Local-first**: All processing on your hardware
- **Privacy-first**: Zero external connections by default
- **Open Core**: MIT-licensed core, optional premium features
- **Composable**: Swap LLMs, STT engines, storage backends
- **Ambient technology**: Work normally, technology in background

---

## 📚 Documentation

**[loqa-meta](https://github.com/loqalabs/loqa-meta)** - Strategy, RFCs, architecture decisions

---

## 🤝 Contributing

We're currently in MVP development (Phase 1). Contributions will open after the initial release.

Interested in the vision? Star ⭐ [loqa-meetings](https://github.com/loqalabs/loqa-meetings) and watch for updates!

---

## 📄 License

- **Code**: MIT (Open Core)
- **Docs**: CC BY 4.0

---

**Follow our journey**: [Strategy docs](https://github.com/loqalabs/loqa-meta) • [Roadmap](https://github.com/loqalabs/loqa-meta/blob/main/docs/vision.md)
