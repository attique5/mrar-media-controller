## Mr AR Media Controller v3.1.0

### New
- Windows desktop app (.exe), works fully offline
- Choose the display/HDMI for each output, opens fullscreen there directly
- Up to 4 screens with custom names (Center / Left / Right / Up…)
- Transitions: Cut, Crossfade, Dip to black (0.5–2s)
- At end: Loop, Hold last frame, Black, Next cue, Jump to cue #
- Lock mode: during a show only hotkeys work
- 6-digit PIN login (PC + mobile), changeable in Settings
- QR mobile remote over the same Wi-Fi, one phone at a time with a takeover option
- Mobile remote in English/Arabic with thumbnails and a queue
- Cue grid grows automatically by rows of 7
- New Apple-style icon set and app icon
- Output windows are hidden from the taskbar and can't be minimized

### Fixes
- Live-output indicator comes back after a reload
- Playback position is saved every 5s instead of constantly
- A hotkey on a missing file shows a warning instead of opening the file picker

### Notes
- Allow the app in Windows Firewall (Private networks) for the mobile remote
- Forgot PIN: delete `%APPDATA%\Mr AR Media Controller\mrar-auth.json`
