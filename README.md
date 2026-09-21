# sparsh

Personal portfolio and engineering lab for **Sparsh Singh** — AI Systems Engineer & Autonomous Agents Architect.

Live at: **[sparsh.is-a.dev](https://sparsh.is-a.dev)**

---

## Overview

A high-performance, single-page portfolio built with raw HTML5, CSS3, and vanilla JavaScript featuring an interactive real-time ASCII particle matrix rendered via HTML5 Canvas.

As you scroll through the workspace, the background reacts dynamically with depth mapping, constellation assemblies, and interactive controls.

---

## Featured Engineering Projects

| Project | Description | Stack / Tech | Links |
| :--- | :--- | :--- | :--- |
| **NETRA** | Institutional-grade cyber-defense & forensic AI threat intelligence platform. Detects facial deepfakes, synthetic audio clones, and document tampering. | Multi-modal Deep Learning, FastAPI, Meta WhatsApp Cloud API | [Live](https://netra-deepfake-detector.vercel.app) • [GitHub](https://github.com/sparsh101sparsh/netra-deepfake-detector) |
| **NullNote** | Real-time timestamped video note-taking browser extension with cross-platform synchronization across web and mobile. | Chrome MV3 Extension, Next.js, Cloudflare Workers | [GitHub](https://github.com/sparsh101sparsh/NullNoteproject) |
| **SSB Smart Screening** | Air-gapped edge AI document inspection workstation engineered for Sashastra Seema Bal (SIH 2026). Features ICAO 9303 MRZ parsing, RSA-2048 PKI validation, and AdaFace 1:1 biometric matching. | Edge AI, Python, Android Companion, OpenCV | [GitHub](https://github.com/sparsh101sparsh/sih26188-ssb-document-screening) |
| **CodeRev** | Interactive competitive coding and algorithmic workspace with 600+ curated problems, Monaco editor, visualizers, and 1v1 battle rooms. | React, Monaco Editor, WebSockets, Node.js | [Live](https://hackathon2-olive-eight.vercel.app) • [GitHub](https://github.com/sparsh101sparsh/CodeRev) |
| **ASCII Video Player & Image Studio** | Real-time in-browser video and image rendering engine translating video streams into animated ASCII characters. | HTML5 Canvas, Custom Luminance Mapping, Web Workers | [GitHub](https://github.com/sparsh101sparsh/ascii-video-player) |

---

## Asset & Design Language System

All project branding icons are engineered with a unified squircle aesthetic:
- **NullNote, CodeRev, ASCII Studio:** 3D frosted/faceted elements embedded in vector `<svg>` wrappers with hardware-accelerated `<clipPath>` squircles (`rx="60"`).
- **SSB & NETRA:** Authentic Indian defense crests and forensic eye badges with dark-mode contrast optimization.
- **Automated Validation:** GitHub Actions workflow (`.github/workflows/validate.yml`) verifies byte integrity of all embedded graphics on every push.

---

## Running Locally

Completely static — no compilation or build steps required:

```bash
# Clone the repository
git clone https://github.com/sparsh101sparsh/sparsh.git
cd sparsh

# Serve locally
python3 -m http.server 3000
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## License

MIT © [Sparsh Singh](https://github.com/sparsh101sparsh)