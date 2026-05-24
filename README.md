# Rodent IV for Android - External Personalities Mod

## Features
- ✅ Android 15 (API 30+) compatible
- ✅ Load personalities from external storage
- ✅ UCI_Elo limit support
- ✅ Works with Chess for Android GUI

## Installation
1. Install the APK
2. In Chess for Android: Engines & Tournaments → Import engine
3. Select "Rodent IV 0.33"

## UCI Configuration

PersonalityFile = /storage/emulated/0/c4a/uci/personalities/tal.txt
UCI_LimitStrength = true
UCI_Elo = 1600
Verbose = true

## Folder Setup (on your phone)
Create this folder:
/storage/emulated/0/c4a/uci/personalities/

Copy your personality `.txt` files there.

## Note
The warning `no 'basic.ini' - check installation, please` is **harmless** and does not affect engine functionality.

## Included Personalities
- tal.txt (aggressive, sacrifices)
- kasparov.txt (dynamic, pressure)
- fischer.txt (precise, tactical)
- default.txt (base style)

## Credits
- Original engine: Rodent IV by Pawel Koziol
- Chess for Android GUI by Aart Bik
- Mod for external personalities on Android 15

## License
GPL v3
