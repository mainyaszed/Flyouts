# Changelog

## 0.5.4 - 2026-10-30

- Video previews: for YouTube in your browser, the player shows the thumbnail, then fades into real frames from the video, flipping like a GIF (Settings > Video previews)
- The glass is rebuilt each time a flyout opens, so it can't turn see-through after a graphics driver reset
- Softer grey selected buttons with smoother edges
- Removed the go-back link from Settings

## 0.5.3 - 2026-10-30

- No more hover tooltips (the headset battery, the mute badge, display names, the go-back link)

## 0.5.2 - 2026-10-30

- Record your own mic mute shortcut in Settings (any key, with Ctrl/Alt/Shift/Win); Settings warns if another app already uses it
- YouTube covers in Chrome show again (small video thumbnails were mistaken for site logos)
- The living cover moves visibly while a track plays
- No more diagonal sheen on the selected buttons and switch knobs

## 0.5.1 - 2026-10-30

- Living cover: the album art slowly drifts and zooms while a track plays, and holds still when paused
- Progress bar in the player with elapsed and total time; click it to jump
- Flatter glass: the faint diagonal sheen across the flyouts is gone
- Windows' Media Player shows as "Media Player"

## 0.5.0 - 2026-10-30

- Mic mute: press Pause (or Ctrl+Alt+M) to mute your microphone in every app; a "Muted" badge stays on screen, click it to unmute
- Bluetooth headset battery in the volume flyout and the mixer
- Français and Arabic (right-to-left), following Windows or chosen in Settings
- Updates are now signed: Flyouts only installs updates signed by the publisher
- Settings can go back to the previous version after an update
- If the WebView2 runtime is missing (some Windows 10 PCs), Flyouts offers to install it
- Silent install (FlyoutsSetup.exe --silent) and an opt-in crash report

## 0.4.2 - 2026-10-30

- Redesigned installer: Install, Update, Repair or Install anyway depending on what's already on the PC, with tinted buttons

## 0.4.1 - 2026-10-30

- Tinted switches

## 0.4.0 - 2026-10-30

- App icon in Explorer, the Start menu, Installed apps and the taskbar
- The installer is a real window with a taskbar button; uninstalling uses the same window
- Installed apps always shows the current version

## 0.3.3 - 2026-10-30

- Quieter sounds
- Much less memory while the flyouts are hidden (about 60 MB instead of about 245 MB)

## 0.3.0 - 0.3.2 - 2026-10-30

- Cleaner, softer sounds; dragging a slider ticks like the volume keys; lower button clicks

## 0.2.0 - 0.2.9 - 2026-10-30

- First public release: volume, media, lock-key and brightness flyouts, a per-app mixer with routing, a per-user installer and automatic updates from GitHub
- Settings with descriptions, keyboard navigation, a draggable window, and update status
- Volume shortcuts (Ctrl+Alt+Up/Down), the mixer shortcut, feedback sounds
- The volume flyout sits next to the player instead of overlapping it
