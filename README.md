# Age of Mythology - Greeks Sound Pack

A CESP v1.0 sound pack for [OpenPeon](https://github.com/PeonPing/openpeon) featuring authentic Ancient Greek dialogue from Age of Mythology.

## 📦 Contents

- **35 sound files** in MP3 format (444 KB total)
- Ancient Greek unit voice lines from villagers, soldiers, and heroes
- Organized into 9 CESP event categories
- 49 total sound mappings across all categories

## 🎵 Sound Categories

| CESP Category | Sounds | Examples |
|---------------|--------|----------|
| `session.start` | 13 | "Λέγε (Speak)", "Πρόσταγμα (Order?)", "Δρυτόμος (Woodcutter)" |
| `task.acknowledge` | 7 | "Ἔστω (Let it be)", "Μάλιστα (Of course)", "Ὀρθῶς (Correctly)" |
| `task.complete` | 3 | "Ἕτοιμος (Ready/willing)" from all unit types |
| `task.error` | 2 | "Πρόσεχε (Be careful!)" |
| `input.required` | 8 | "Πρόσταγμα (Order?)", "Λέγε (Speak)", "Εἰς μάχην (To battle)" |
| `resource.limit` | 3 | "Πρόσεχε (Be careful!)" warnings |
| `task.progress` | 7 | Work sounds: "Τέκτων (Mason)", "Μεταλλεύς (Metalworker)" |
| `user.spam` | 3 | "Εἰσβολή (Invasion!)" from all unit types |
| `session.end` | 3 | "Καλῶς (Good, well)", "Ἐργάτης (Worker)" |

## 🗣️ Language

All dialogue is in **Ancient Greek** (language code: `el`) using Modern Greek pronunciation, as featured in the original Age of Mythology game.

## 📋 Installation

Sound packs are installed via the [OpenPeon registry](https://openpeon.com/packs) during peon-ping setup.

### Via Registry (Recommended)

Once this pack is published to the registry, install it using:

```bash
peon-ping install --packs=aom-greeks
```

Or install it alongside other packs:

```bash
peon-ping install --packs=aom-greeks,glados,peon
```

### Activation

After installation, activate the pack:

```bash
peon packs use aom-greeks
```

### Manual Installation (Development)

For testing or development, place the pack in:
- **Global**: `~/.openpeon/packs/aom-greeks/`
- **Local project**: `./.claude/hooks/peon-ping/config/aom-greeks/`

Packs must follow the [CESP v1.0 specification](https://github.com/PeonPing/openpeon).

## 🎮 Source

Sound files sourced from the [Age of Empires Fandom Wiki](https://ageofempires.fandom.com/wiki/Greeks_(Age_of_Mythology)/Dialogue_lines).

## 📄 License

**CC-BY-NC-4.0** (Creative Commons Attribution-NonCommercial 4.0 International)

This sound pack is for non-commercial use only. The original sound files are copyrighted by Ensemble Studios / Xbox Game Studios.

## 📁 Repository Structure

```
aom-greeks/
├── openpeon.json          # CESP v1.0 manifest
├── README.md              # This file
├── LICENSE                # CC-BY-NC-4.0 license
└── sounds/                # 35 MP3 files (flat structure)
    ├── villager-male-select-lege.mp3
    ├── soldier-attack-isvoli.mp3
    ├── hero-move-esto.mp3
    └── ... (32 more files)
```

All sound files use Greek transliterations in their filenames (e.g., `isvoli` for "Invasion!", `esto` for "Let it be").

## 👤 Author

**Konstantinos Diamantidis** ([@kdmnt](https://github.com/kdmnt))

## 🙏 Credits

- **Ensemble Studios** - Original Age of Mythology game and sound assets
- **Age of Empires Fandom Wiki** - Sound file hosting and documentation
- **OpenPeon/PeonPing** - Sound pack framework
