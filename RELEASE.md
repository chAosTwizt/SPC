# Release notes

## SPC Super Poker Custom v1.5.1 (July 13, 2026)

Download **`SPC-SuperPoker-Custom-2026-07-13.zip`** from [Releases](https://github.com/chAosTwizt/SPC/releases/latest).

### New in v1.5.1

- **Themes on all windows** — Red / Black / Splatoon colors apply across Main, Dutch Sailors, Dodo Script, Map, settings, etc.
- **Gear cog = theme menu** — stays visible while connected; pick theme or open Configuration
- **Splatoon Joy-Con split** — left = pink, right = green (controller + window balance)
- **Debug log** — live `save\SPC-Debug.log`; on real crash auto-saves `SPC-LAST-CRASH.log` to Desktop (no button needed)
- **Send Debug Log** — optional while poker is still open
- **Close Gate aborts Dodo Restore** — stops restore so it won’t walk back in and re-open the gate
- **Theme stickiness** — buttons/tabs keep theme colors after clicks
- **False “crashed” popup fix** — recoverable UI errors no longer claim poker died

### From v1.5.0

- Dodo Script editor, OrvilleMacro.txt, Close Gate, Seaside Seating NHI fallback, Load NHI empty-file fix

### Staff setup

1. Extract zip on Windows 10/11
2. Install [.NET 9 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/9.0)
3. Run `win-x64\ACNHPokerCore.exe` inside the extracted folder
4. Follow wizard → see SETUP-STAFF.md

### Do not distribute

- Personal `ACNHSuperPoker-Red/Black/Splatoon` folders (contain host IP + anchors + image cache)
