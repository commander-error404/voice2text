<div align="center">

# voiceboard

**voice is the keyboard text appears at the cursor**

Hold a hotkey, speak, release. The text gets typed wherever your cursor is.

</div>

---

### Status

Early development. Nothing to install yet.

### Goals

- Runs locally  no cloud, no accounts
- Cross-platform Windows and Linux
- Light on CPU and RAM when idle
- Works in any text field of any app

### Stack

`Python` for the main app and glue. `Rust` and `Go` for the parts where
Python is too slow — audio, hotkeys, text injection. A local Whisper-like
model handles the speech-to-text.

### task
I don't know yet

### License
MIT
