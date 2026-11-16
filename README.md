# Voxora

Universal AI audio assistant for Windows: meeting transcription with speaker detection, and voice dictation into any app (double-tap Caps Lock).

## Download

Get the latest build from **[Releases](../../releases/latest)**.

## Install

1. Download `Voxora-<version>-win-x64.zip` and `install.ps1` into the same folder.
2. Right-click in that folder → *Open in Terminal*, then run:
   ```powershell
   powershell -ExecutionPolicy Bypass -File install.ps1
   ```
3. Start **Voxora** from the Start menu.

No administrator rights are needed; it installs to `%LOCALAPPDATA%\Programs\Voxora`.

## Notes

- **Windows SmartScreen:** the app is not code-signed yet. On first launch, click *More info → Run anyway*.
- **Speech model:** the Whisper model downloads automatically the first time you transcribe (internet needed once).
- **AI features** (summaries, cleanup, speaker naming) need your own AI endpoint and key, entered in Settings. Transcription and dictation work without one.

## Requirements

Windows 10/11, 64-bit.
