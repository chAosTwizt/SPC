# Release notes

## SuperPoker Share Pack — July 2026

Download **`ACNHSuperPoker-Share-2026-07-05.zip`** from the [Releases](https://github.com/chAosTwizt/SPC/releases/latest) page (Assets section).

## v1.0.1 (July 5, 2026)

Same build chAos runs locally — crash fixes for Run Dodo / dropper, Orville menu auto-retry, present item loading.

### Changes

- No more FormatException popup on bad sys-botbase reads (logs instead)
- Dropper survives bad memory reads instead of stopping after N items
- Run Dodo retries Orville menu (DDOWN 1 → 0 → 2)
- Website present SKUs map to gift pool
- README troubleshooting for OrvilleDodoDown config

### Quick start

1. Extract the zip on **Windows 10/11**
2. Install **[.NET 9 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/9.0)**
3. Run `win-x64\ACNHPokerCore.exe`
4. First launch downloads item images (~90 MB)
5. See **README.md** for setup, custom buttons, and keyboard-only order workflow

### Requirements

- Nintendo Switch with sys-botbase (port 6000)
- Animal Crossing: New Horizons

### Not included

- Item images (`img/` — auto-download)
- Personal IP, anchors, or save data
