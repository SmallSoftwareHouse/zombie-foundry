# Games Server Manager

**Games Server Manager (GSM)** is a lightweight terminal tool for setting up and
managing dedicated **Source Engine** game servers (Left 4 Dead 2, and more to come).
It wraps SteamCMD, server configuration, mods and day-to-day management behind a
clean text-based interface — no manual file editing, no guesswork.

> ⚠️ **Beta** — This is an early test build. Things may change and bugs are expected.
> Feedback is very welcome.

## Download

Grab the latest build from the [**Releases**](../../releases/latest) page and
download `gsm.exe`.

## How to use

1. Put `gsm.exe` in its **own dedicated folder** (not in `Program Files`).
2. Run it.
3. On first launch it creates everything it needs next to itself
   (`config`, `servers`, `logs`, `downloads`). It is fully **portable** — to move
   or back it up, just copy the whole folder.

The built-in wizard walks you through installing a server via SteamCMD, picking the
game, maps and game modes, and getting it online.

## Requirements

- Windows 10 / 11, 64-bit
- An internet connection (SteamCMD downloads the server files)

## Notes

- The executable is **unsigned**, so Windows SmartScreen may warn you on first run.
  Choose *More info → Run anyway*.
- **Updates:** the tool checks for new versions on startup and points you back to
  the Releases page when one is available.