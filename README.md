# Cheeky Votann: The Ancestor Core

<p align="center">
<img width="400" src="[https://github.com/user-attachments/assets/your-new-votann-logo-placeholder.png](https://www.google.com/search?q=https://github.com/user-attachments/assets/your-new-votann-logo-placeholder.png)" alt="Cheeky Votann Logo" />
</p>

> **"The Ancestors are watching, and they have the answers."**

**Cheeky Votann** is a privacy-first, Linux-native Strategic Intelligence Core. Originally a fork of `cheating-daddy`, this version has been remastered for the High Kahls of the galactic core who demand low-latency, local-first inference and reproducible system integration.

## 🛠 The Votann Tech Stack

Unlike cloud-dependent assistants, Cheeky Votann is engineered for the Linux power user:

* **Local Inference Engine**: Integrated support for **Ollama** (Llama 3/Qwen2-VL) and **Piper TTS**.
* **Neural Sidecar**: A Python-based "Fast Cascade" that handles VAD, transcription, and synthesis locally.
* **PipeWire Native**: Uses `parec` and PipeWire graph routing for sub-20ms audio capture latency.
* **Nix-Powered**: A fully reproducible `flake.nix` that hermetically seals the environment, dependencies, and GPU drivers.

## Core Features

* **Ancestor Wisdom (Local & Cloud)**: Support for Google Gemini 2.0 Flash Live OR local Ollama inference.
* **Multimodal Cognition**: Real-time screen analysis for coding challenges and IDE context.
* **Zero-Latency Audio**: Optimized Linux audio plumbing—records in Mono directly from the source to save CPU cycles.
* **Holo-Overlay**: A transparent, always-on-top Electron window that stays out of your way during high-stakes maneuvers.
* **Privacy-First**: Your interview audio never has to leave the system if you use the Local Stack.

## Awakening the Core (Setup)

### The Nix Way (Recommended)

If you are running NixOS or have the Nix package manager, awakening the core is a single command:

```bash
nix run github:your-repo/cheeky-votann

```

### The Standard Way

1. **Ollama**: Ensure [Ollama](https://ollama.com/) is installed and running (`ollama serve`).
2. **PulseAudio/PipeWire**: Ensure `pulseaudio-utils` is installed for the `parec` backend.
3. **Install & Start**:
```bash
npm install
npm start

```



## Battle Controls (Keyboard Shortcuts)

| Shortcut | Action |
| --- | --- |
| `Ctrl/Cmd + Arrow Keys` | Reposition the Core (Window) |
| `Ctrl/Cmd + M` | Toggle Mouse Transparency (Click-through) |
| `Ctrl/Cmd + \` | Retrench (Close/Back) |
| `Enter` | Send direct query to the Ancestors |

## System Architecture

Cheeky Votann operates on a **Dual-Path Intelligence** model:

1. **The Cloud Path**: Direct WebSocket connection to Gemini 2.0 Live for maximum reasoning breadth.
2. **The Local Path (Experimental)**: A Python sidecar utilizing `Faster-Whisper` for STT, `Ollama` for reasoning, and `Piper` for TTS, routed through the PipeWire audio graph.

## ⚖️ License

Distributed under the **GPL-3.0 License**. The Ancestors believe in open-source intelligence.

---


*Disclaimer: Use Cheeky Votann responsibly. The High Kahl is not responsible for any corporate disciplinary actions resulting from the unauthorized use of Ancestral Intelligence.*
Original work is by Soham.
