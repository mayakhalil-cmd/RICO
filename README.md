# RICO

> Real-time AV control hub for OSC, MIDI, NDI, Spout, DMX, and more.

RICO is a lightweight Windows application that bridges your creative tools together — no patching, no complicated setup. Plug in your controller, open RICO, and start routing signals between your software in seconds.
RICO also lets artists and developers control 3D and generative environments with any physical interface, in real time, with zero setup.

Built for artists, performers, and creative technologists who want to focus on the work, not the wiring.

---

## What RICO Does

RICO acts as a central hub for real-time multimedia control. It handles:

- **MIDI** — route, learn, and remap any controller
- **OSC** — send and receive to multiple destinations simultaneously
- **Spout** — share textures between DirectX applications in real time
- **NDI** — send and receive video streams over a network
- **DMX / Art-Net** — control lighting rigs
- **MQTT** — connect to IoT devices and custom hardware
- **Audio Analysis** — FFT-based audio reactivity with beat detection
- **Guitar to MIDI** — convert live audio input to MIDI in real time
- **Ableton Link** — sync tempo across devices on a network
- **Virtual MIDI** — create software MIDI ports (requires teVirtualMIDI)

---

## Download

**[→ Download RICO Beta v2.2.0](https://github.com/mayakhalil-cmd/RICO/releases)**

Windows 10/11 x64 only.

---

## Before You Install

RICO requires these free runtimes to be installed first:

- **NDI Runtime** — [ndi.video](https://downloads.ndi.tv/SDK/NDI_SDK/NDI%206%20Runtime.exe) — required for NDI send/receive
- **teVirtualMIDI** — [tobias-erichsen.de](https://www.tobias-erichsen.de/software/virtualmidi/virtualmidi-sdk.html) — RICO will not launch without these! This is a temporary solution for testing only.

---

## Installation

1. Download `RICO_Setup_v2.2.0.exe` from the [Releases](https://github.com/mayakhalil-cmd/RICO/releases) page
2. Run the installer — click through Next → Install → Finish
3. Launch RICO from the Start Menu or desktop shortcut

> **Note:** Windows may show a SmartScreen warning on first launch. Click **"More info" → "Run anyway"** — this is normal for unsigned apps.

---

## Who It's For

- VJs and live visual performers
- Musicians and live electronic artists
- New media artists building interactive installations
- Creative technologists prototyping AV systems
- Studios and agencies working with real-time media
- Developers building interactive or generative spatial systems

---

## RICO in Action

**Audio-reactive Projection in Touchdesigner**

[![Phantom Performer](https://img.youtube.com/vi/JMEpWeDxqos/hqdefault.jpg)](https://www.youtube.com/watch?v=JMEpWeDxqos)

**Live Demo**

[![RICO Live Demo](https://img.youtube.com/vi/WFSsrMt0q5o/hqdefault.jpg)](https://www.youtube.com/watch?v=WFSsrMt0q5o)


**RICO as a switcher** 

[![RICO Demo](https://img.youtube.com/vi/pCdKzlmJL9U/hqdefault.jpg)](https://www.youtube.com/watch?v=pCdKzlmJL9U)

**What if we can VJ in After Effects in Real-time with RICO?**

[![RICO Demo](https://img.youtube.com/vi/H7p1swY0vSk/hqdefault.jpg)](https://www.youtube.com/watch?v=H7p1swY0vSk)


---

## Status

RICO is currently in **public beta**. Core features are stable and in active use. Some features are still being refined.

If you find a bug or have a feature request, please [open an issue](https://github.com/mayakhalil-cmd/RICO/issues).

---

## Built With

- C++ / DirectX 11 / ImGui
- RtMidi, oscpack, Spout, NDI SDK, paho-mqtt, miniaudio, pffft, Ableton Link

---

## License

RICO is currently closed source. A public source release is planned for a future version.

© 2025 Maya Khalil. All rights reserved.
