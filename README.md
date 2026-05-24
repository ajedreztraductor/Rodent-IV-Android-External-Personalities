# Rodent IV for Android - External Personalities Mod

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Android 15+](https://img.shields.io/badge/Android-15+-green)]()

Rodent IV chess engine modified to work with **external personalities** on modern Android (API 30+). Works with **Chess for Android** GUI.

## Features

- ✅ **Android 15 (API 30+) compatible** – bypasses storage restrictions
- ✅ **Load personalities from external storage** – `/storage/emulated/0/c4a/uci/personalities/`
- ✅ **UCI_Elo limit support** – play at any strength level
- ✅ **Works with Chess for Android** – import as UCI engine
- ✅ **Harmless warning** – `no 'basic.ini'` message does NOT affect functionality

## Installation

1. **Download the APK** from [Releases](https://github.com/ajedreztraductor/Rodent-IV-Android-External-Personalities/releases)
2. **Install** the APK on your Android device
3. Open **Chess for Android** → Engines & Tournaments → Import engine
4. Select **"Rodent IV 0.33"**

## Folder Setup (on your phone)

Create this folder on your internal storage:
/storage/emulated/0/c4a/uci/personalities/

Use any file manager (e.g., Samsung My Files, Material Files).

## UCI Configuration

In Chess for Android engine options, set:
PersonalityFile = /storage/emulated/0/c4a/uci/personalities/tal.txt
UCI_LimitStrength = true
UCI_Elo = 1600
Verbose = true

## Personalities

The personality files (`.txt`) are **not included** in this repository out of respect for the original author.

You can download the complete official collection from:
👉 **[GitHub - nescitus/rodent-iv/personalities](https://github.com/nescitus/rodent-iv/tree/master/personalities)**

Place the `.txt` files you want into the folder created above.

## Note

The warning message:
no 'basic.ini' - check installation, please
is **completely harmless** and does NOT affect engine functionality. The engine loads personalities correctly.

## Credits

| Component | Author |
|-----------|--------|
| Rodent IV engine | [Pawel Koziol (nescitus)](https://github.com/nescitus/rodent-iv) |
| Chess for Android GUI | [Aart Bik](https://github.com/aartbik) |
| Android 15 external personalities mod | [@ajedreztraductor](https://github.com/ajedreztraductor) |

## License

GPL v3 – same as the original Rodent IV engine.
