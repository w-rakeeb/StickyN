# StickyN

<img src="assets/logo.png" alt="StickyN" width="80">

A portable Windows desktop sticky-note app. Write on paper-style notes, format text, and lock notes in place.

[Download StickyN](https://github.com/w-rakeeb/StickyN/releases/latest)

## Getting started

Download StickyN.exe from a release, put it in a writable folder, and open it. The Windows x64 runtime is included. Settings can create a desktop shortcut.

Built for Windows 10 and 11. Windows 11 is tested; a physical Windows 10 test remains outstanding.

- Original plus eight illustrated themes: Cherry blossom, Rose, Lavender, Snowfall, Greenland, Iceland, Kyoto and Chinese garden
- 65 note styles, grouped by theme, with custom paper colors, gradients, RGB/HSV/HEX controls and saved/recent colors
- 32 bundled open-licensed font families, handwriting and clean text options, lists and H1–H4
- Resizable notes, larger corner targets, and separate lock-position and always-on-top controls
- Persistent quick tools; use the chevron or Ctrl+Shift+Space to hide/show them. Locking or hiding a note closes its tools
- Freely movable subnotes that inherit the parent color and can use every primary note style (Ctrl+Shift+N)
- Decorative pushpins, paperclips and tape, with saved positions; Full, Minimal or Off window decoration
- Local photo previews, clickable links and document attachments
- Search, sorting, filters, bulk editing, Undo and Recently deleted
- Compact Settings with keyboard category navigation and smooth section scrolling
- Local autosave, automatic backups, JSON/Markdown export and complete .stn backups with attachment files
- Locked notes hide editing controls without dimming writing; hidden notes remain hidden after sign-in

Cherry blossom, Snowfall, Greenland, Iceland and Kyoto use Light mode. Original and Lavender support System/Light/Dark; Rose and Chinese garden initially use Light and also support Dark. Theme choices and note styles are independent.

Existing notes and chosen fonts remain supported. The extra fonts increase download size. Physical mixed-DPI testing and strict frame-time targets remain outstanding; no universal 60/120fps claim is made.

## Updates

Settings offers Check for updates and an automatic-check preference. Checks run at most every 12 hours and do not install anything until Update and restart is selected. The app verifies the publisher signature and the downloaded executable, saves notes, and restarts. The previous executable is retained for recovery.

Only published stable releases enter the update channel. A source edit or Git commit is not an app update.

The update manifest is signed with a dedicated publisher key. UpdatePublicKey.txt contains the public verification key. This signature protects the update package; it is separate from a Windows Authenticode certificate. The executable does not currently have a Windows certificate signature.

## Privacy

Notes and settings stay in %LOCALAPPDATA%\StickyN. They are not uploaded to GitHub. Update checks contact GitHub for release information and downloads. Automatic checks can be turned off, and the app remains usable offline. No GitHub login is required by users.

This repository distributes app releases and public release information. It does not contain private notes, publisher credentials, or the application source.

## Credits

Created by [Wrakeeb](https://github.com/w-rakeeb). Bundled font license texts are available inside the app under Settings → About → Licenses and in the release LICENSES.txt asset.
