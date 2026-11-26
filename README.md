# Brush Up Cards — downloads

Spaced-repetition flashcards for Chinese (and other languages). Opens your Anki decks, and has its own format (`.buc`) with typed practice, tone colours and progress you can move between devices.

**Easiest:** open the [Releases page](https://github.com/qaevv/brush-up-cards-downloads/releases) and pick your system. The folders below hold the same files.

| System | File | How to open |
|---|---|---|
| Windows 10/11 (64-bit) | [`windows/BrushUpCards-0.2.0-windows-x64-portable.exe`](https://github.com/qaevv/brush-up-cards-downloads/raw/main/windows/BrushUpCards-0.2.0-windows-x64-portable.exe) | Double-click. No install. If SmartScreen warns: More info → Run anyway. |
| macOS, Apple Silicon (M1 or newer) | [`mac/BrushUpCards-0.2.0-mac-arm64.zip`](https://github.com/qaevv/brush-up-cards-downloads/raw/main/mac/BrushUpCards-0.2.0-mac-arm64.zip) | Unzip, drag **Brush Up Cards** to Applications. See "Mac won't open it" below. |
| macOS, Intel | [`mac/BrushUpCards-0.2.0-mac-x64.zip`](https://github.com/qaevv/brush-up-cards-downloads/raw/main/mac/BrushUpCards-0.2.0-mac-x64.zip) | Same as above. |
| Linux (64-bit) | [`linux/BrushUpCards-0.2.0-linux-x86_64.AppImage`](https://github.com/qaevv/brush-up-cards-downloads/raw/main/linux/BrushUpCards-0.2.0-linux-x86_64.AppImage) | `chmod +x` the file, then run it. |

Which Mac? Apple menu → About This Mac: "Chip: Apple M…" = Apple Silicon, "Processor: Intel" = Intel.

### Mac won't open it ("damaged" or "can't be verified")
The app isn't signed with an Apple developer certificate yet. Either:
- System Settings → Privacy & Security → scroll down → **Open Anyway** (after trying to open it once), or
- Terminal: `xattr -cr "/Applications/Brush Up Cards.app"` then open it normally.

### Updating from Kort 0.1.0
Just use the new file. The app keeps reading your old Kort data, so all decks and progress stay.

### What's new in 0.2.0
- New name: **Brush Up Cards**.
- **Own deck format (`.buc`)**: Settings → Your data → Export decks (with or without progress). Import on the Import page. Bring your progress to another computer.
- **Anki decks are plain flashcards**, like in Anki. "Convert to Brush Up Cards" on a deck gives a copy with Translate / Write / Fill in / Mixed and tone colours; the Anki deck is left as it is.
- **Tone colours** for Chinese words and pinyin (1 red, 2 green, 3 blue, 4 purple, neutral grey). Switch off under Profile → Appearance.
- **Record or upload audio for every audio field**, including example-sentence audio.
- **Typed meanings**: one of the listed meanings is enough.
- **New cards spread between reviews** instead of all at the start (deck option to change back).

### Checksums (SHA-256)
    0978bc41a2d742c644d6899edd11d9552f69f49f59e50bb3f44b550d56e91bad  windows/BrushUpCards-0.2.0-windows-x64-portable.exe
    7610d84b1478e2c01bdf68587781cd5988a93b3ee8698931c9ecc0f1f5ee1c94  mac/BrushUpCards-0.2.0-mac-arm64.zip
    97513618c682b94020a020b369843e5db4b9508db2e9dff16622a28ca6205b4d  mac/BrushUpCards-0.2.0-mac-x64.zip
    23025e386c06a01ba23fcfd95e0b3c735b29e0a4d429f25482b8fc0a432c7c09  linux/BrushUpCards-0.2.0-linux-x86_64.AppImage

All data is stored locally on your computer.
