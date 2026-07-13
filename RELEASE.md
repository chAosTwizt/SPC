# Release notes

## SPC Super Poker Custom v1.5.0 (July 12, 2026)

Download **`SPC-SuperPoker-Custom-2026-07-12.zip`** from [Releases](https://github.com/chAosTwizt/SPC/releases/latest).

### New in v1.5.0

- **Dodo Script** window — plain-English Orville step editor (every button + wait)
- **Restore defaults** — stock Black/Splatoon timing (17s internet wait)
- **OrvilleMacro.txt** — OnlineConnect / DodoMenu / Departure sequences, reloaded every Run Dodo
- **Close Gate** button — close airport gate after a villager visit and return to drop spot
- **Seaside Seating / Downloads NHI fallback** when a collection pack is missing from `strobe/`
- **Load NHI** no longer crashes on empty/invalid files (shows an error instead)
- Strobe panel layout cleanup (Import Pockets, Run Dodo, dodo code, logs)

### Still included from v1.0.2

- First-run setup wizard for staff (Switch IP, anchors, theme)
- Connect validation soft-fail on empty peek
- Run Dodo / dropper crash fixes, present items, villager name fixes

### Staff setup

1. Extract zip on Windows 10/11
2. Install [.NET 9 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/9.0)
3. Run `win-x64\ACNHPokerCore.exe` inside the extracted folder
4. Follow wizard → see SETUP-STAFF.md

### Do not distribute

- Personal `ACNHSuperPoker-Red/Black/Splatoon` folders (contain host IP + anchors + image cache)
