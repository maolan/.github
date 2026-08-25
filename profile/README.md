# Maolan

> An open-source digital audio workstation built in Rust.

[🌐 Website](https://maolan.rs) · [📦 Main Repository](https://github.com/maolan/maolan) · [📖 Documentation](https://doc.maolan.rs)

## What is Maolan?

Maolan is a free, open-source DAW built in Rust, focused on recording, editing, routing, automation, export, and plugin hosting. It prioritizes transparency, performance, and community-driven development.

- **Multi-track audio & MIDI** — Record and arrange with precise timing and flexible mixing.
- **Piano roll editing** — Compose and refine MIDI performances with an intuitive editor.
- **Plugin hosting** — Load CLAP, VST3, and LV2 plugins with complex routing chains, sidechains, and MIDI paths.
- **Automation & envelopes** — Automate volume, pan, sends, and plugin parameters across the timeline.
- **Export** — Render to WAV, MP3, OGG, and FLAC with normalization and master-limiter options.

## Organization Repositories

| Repository | Description |
|------------|-------------|
| [`maolan`](https://github.com/maolan/maolan) | The main DAW application |
| [`plugins`](https://github.com/maolan/plugins) | Audio plugins for the Maolan ecosystem |
| [`editor`](https://github.com/maolan/editor) | Audio editor |
| [`mixosc`](https://github.com/maolan/mixosc) | OSC mixing utilities |
| [`engine`](https://github.com/maolan/engine) | Audio engine powering Maolan |
| [`generate`](https://github.com/maolan/generate) | Maolan AI for generating music |
| [`doc`](https://github.com/maolan/doc) | Documentation source |
| [`lv2`](https://github.com/maolan/lv2) | Maolan LV2 hosting crate |
| [`plugin-host`](https://github.com/maolan/maolan/tree/main/plugin-host) | Out-of-process plugin host |
| [`plugin-protocol`](https://github.com/maolan/plugin-protocol) | Shared IPC protocol for out-of-process plugin hosting |
| [`trainer`](https://github.com/maolan/trainer) | NAM trainer |
| [`vocal`](https://github.com/maolan/vocal) | Vocal manipulation based on RVC |
| [`widgets`](https://github.com/maolan/widgets) | Reusable UI widgets |
| [`baseview`](https://github.com/maolan/baseview) | Fork of baseview with FreeBSD support |
| [`devops`](https://github.com/maolan/devops) | Maolan DevOps |
| [`site`](https://github.com/maolan/site) | Project website and documentation |

## Quick Start

```bash
git clone https://github.com/maolan/maolan
cd maolan
cargo run --release
```

## Platform Support

- Linux
- FreeBSD
- Windows

## Get Involved

- ⭐ Star the project on GitHub
- 🐛 [Report bugs](https://github.com/maolan/maolan/issues) and request features
- 🔧 [Submit pull requests](https://github.com/maolan/maolan/pulls)
- 💬 Share feedback and ideas

---

Licensed under the [BSD-2-Clause](https://github.com/maolan/maolan/blob/main/LICENSE) license.
