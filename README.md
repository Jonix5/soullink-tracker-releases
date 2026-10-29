# Jonix Soullink Tracker – downloads

This repository only hosts the Windows installers and the files the app uses for automatic updates.
The source code is not public.

**Download:** see [Releases](../../releases/latest) → `Jonix-Soullink-Tracker-Setup-<version>.exe`

- Website, install guide and help: https://jonix-soullinktracker.com
- Discord (questions, bug reports, partner search): https://discord.gg/UNgnDh2gf7

## Windows warning

The installer is not code-signed (a certificate costs money, this is a free hobby project), so Windows
SmartScreen may show "Windows protected your PC". Click **More info → Run anyway**.
You can check the file with the SHA-256 checksum listed in each release:

```powershell
Get-FileHash .\Jonix-Soullink-Tracker-Setup-<version>.exe -Algorithm SHA256
```

Unofficial fan project, not affiliated with Nintendo, Game Freak or The Pokémon Company.
