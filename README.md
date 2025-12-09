<div align="center">
  <img src="Resources/IconDavetrap.ico" alt="Davetrap" width="96" />
  
  <h1>Davetrap</h1>
  <p>A modern, community‑first Roblox bootstrapper — lean like Bloxstrap, polished like Fishtrap, built to outclass every fork.</p>
</div>

## What Is Davetrap

Davetrap is a clean, fast, and extensible alternative Roblox bootstrapper. It ships with the core feature set you already know from Bloxstrap & Fishtrap, and is designed to grow into the most trusted, best‑documented bootstrapper in the ecosystem.

## Key Features

- FFlag editor — search, toggle, and persist flags quickly
- Themes & appearance — curated presets plus fine‑grained controls
- Mods & assets — drop‑in sounds, cursors, textures, and UI tweaks
- Background updates — keep Roblox fresh without blocking play
- Discord Rich Presence — presence that just works, with smart fallbacks

## Quick Start

- Download the latest single‑file build from Releases or build locally
- Run `Davetrap.exe` once — it detects Roblox and sets itself up
- Open `-menu` to customize FastFlags, Themes, and Mods; create a Profile (planned) to save your full setup

```powershell
# Build single‑file (Release, win‑x64)
dotnet publish Davetrap/Davetrap.csproj -c Release -r win-x64 \
  /p:PublishSingleFile=true /p:SelfContained=true /p:IncludeNativeLibrariesForSelfExtract=true

# Launch settings UI
"path\to\Davetrap.exe" -menu

# Force in‑place upgrade of the installed copy
"path\to\Davetrap.exe" -upgrade
```



## Features — Now vs. Next

- FastFlags: search/filter, set & persist; prefix search, conflict hints, per‑profile overrides (✅)
- Themes: Light/Dark + custom palettes; one‑click presets, live preview, fine sliders (✅)
- Mods: sounds, cursors, textures; safe mod folders, per‑profile mod sets (✅)
- Discord RPC: rule‑based presence composer, fallback if Discord closed (✅)
- Updates: delta/patch updates, rollback, offline installers (✅) 

 ✅ = available · 🔜 = planned

## Install / Portable

- Portable: place `Davetrap.exe` anywhere; config lives beside the app
- Installed: standard user‑profile paths are used

Config paths

- Portable: `./Davetrap/UserData/`
- Installed: `%AppData%\Davetrap\`
- Logs: `%LocalAppData%\Davetrap\Logs\`

## Roadmap (milestones)

- M0 — Public build: parity with core features; stable installer + portable zip
- M4 — Presence Composer: rule‑based Discord RPC with privacy filters

## Repository Structure (simplified)

```
Davetrap/
├─ Davetrap/            # App (UI / bootstrapper)
```




## Community & Support

- Join the Davetrap Discord  https://discord.gg/Vu6D9KAfRH to get updates, discuss development, and share ff

## Credits

Special thanks to open‑source bootstrapper projects whose ideas and groundwork inspired Davetrap:

- Bloxstrap
- Fishtrap
- Frostrap



## Developers

-davedown


