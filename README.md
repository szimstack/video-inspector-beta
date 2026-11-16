# Video Inspector — Beta

Beta builds of Video Inspector for testing.

**Download the latest build: [Releases → Latest](../../releases/latest)**

| Platform | File | Install |
|---|---|---|
| macOS (Apple Silicon) | `.dmg` | Open it and drag Video Inspector to Applications |
| Windows | `.msi` or `-setup.exe` | SmartScreen warning → **More info → Run anyway** |
| Linux | `.AppImage` (or `.deb` / `.rpm`) | `chmod +x Video*.AppImage`, then run it |

### Bitrate graph on Windows and Linux
For MOV, MP4 and most other formats the bitrate graph uses **ffprobe** (part of FFmpeg). Install it once, then restart the app:

- **Windows:** `winget install ffmpeg`
- **Linux:** `sudo apt install ffmpeg` (Debian/Ubuntu) or `sudo dnf install ffmpeg` (Fedora)

`.ts` / `.m2ts` files and the macOS build don't need it.

## Feedback
Reply to the email you got this link from.
