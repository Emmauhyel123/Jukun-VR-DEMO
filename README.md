# Jukun-VR-DEMO

Welcome to the Jukun VR Demo project! This repository contains a virtual reality demonstration application.

## Overview

Jukun-VR-DEMO is a VR project designed to showcase immersive experiences and interactive environments.

## Features

- [ ] Add feature descriptions here
- [ ] VR environment setup
- [ ] Interactive elements
- [ ] User interaction handling

## Getting Started

### Prerequisites

- List your project dependencies and system requirements here
- VR headset/device requirements (if applicable)
- Software/SDK versions needed

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Emmauhyel123/Jukun-VR-DEMO.git
   cd Jukun-VR-DEMO
   ```

2. Install dependencies:
   ```bash
   # Add your installation commands here
   ```

3. Build/Setup:
   ```bash
   # Add build commands here
   ```

## Usage

Add instructions on how to run and use your VR demo:

```bash
# Example commands
```

## Project Structure

```
Jukun-VR-DEMO/
├── README.md
├── ...
└── [Add your project structure here]
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue on the GitHub repository.

## Authors

- **Emmauhyel123** - Initial work

---

*Last updated: August 22, 2026*

---

## New in this build

- **Download page** now has two tabs — **PCVR / Meta Quest** and **Android APK** —
  each with its own download button, requirements list, and installation steps.
- **Bilingual site**: an EN / JUK toggle in the nav (desktop + mobile) switches every
  page between English and Jukun (Wapan). Logic lives in `assets/i18n-data.js`
  (the translation strings) and `assets/site.js` (the switching engine).
- **Listen (text-to-speech)**: a "Listen" button in the nav reads the current page
  aloud in the selected language, with pause/resume/stop, using the browser's
  built-in Web Speech API — no extra services or API keys required.

### ⚠️ About the Jukun translations
There's no public dictionary or machine-translation engine for Jukun/Wapan, so the
`jkn` strings in `assets/i18n-data.js` are a **best-effort draft**, not a verified
translation — proper nouns and dance/festival names (Aku Uka, Kwararafa, Keku,
Ajo-Bwi, Ajo-Niku, Puje, Wukari) are left as-is since they're already Jukun words.
Before using this publicly, have a native Wapan/Jukun speaker review and correct
that one file — every page will pick up the fix automatically.

Likewise, there is no real Jukun text-to-speech voice in any browser, so "Jukun"
narration is read using the closest available voice as a phonetic approximation.
