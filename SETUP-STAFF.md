# SPC Super Poker Custom — Staff Setup (5 minutes)

## Download

Get **SPC-SuperPoker-Custom** from [GitHub Releases](https://github.com/chAosTwizt/SPC/releases/latest).

Do **not** use a zip copied from someone else's full install folder (Black/Red/etc.) — those contain their IP and island anchors.

## Install

1. Extract anywhere (e.g. `C:\SuperPoker\`).
2. Install [.NET 9 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/9.0) (Desktop, not SDK).
3. Run **`win-x64\ACNHPokerCore.exe`** (not any `net9.0-windows` subfolder).
4. Complete the **setup wizard** (Switch IP + anchors + theme).
5. Wait for item images to download on first launch (~90 MB).

## Connect

1. Open ACNH on your Switch (overworld or title screen).
2. Enter **your** Switch IP → **Connect**.
3. If prompted, set **anchors** in Dutch Sailors:
   - Anchor **2** = airport entrance
   - Anchor **3** = in front of Orville

## Daily order workflow

| Step | Action |
|------|--------|
| 1 | **Load Order** → pick Strobe `.json` |
| 2 | **Run Dodo** (needs dodo code from order) |
| 3 | Click **Dutch Sailors** title bar (keyboard focus) |
| 4 | **`1`–`6`** chat presets · **`9`** start/pause dropper |

## Important

- **Your IP** is yours — never use a coworker's pre-filled IP.
- **Anchors are per island** — reset and set your own if anything teleports wrong.
- **Instant Text** turns off automatically after you get a dodo code (so visitors don't stick at the gate).

## Troubleshooting

| Problem | Fix |
|---------|-----|
| Keys do nothing | Click Dutch Sailors title bar |
| Run Dodo fails | Set anchors 2 & 3; game on overworld |
| Connect fails | Check IP; ACNH running; sys-botbase port 6000 |
| Wrong teleports | Reset anchors → set again on **your** island |
| Crash / sequence stops / dropper dies | After a crash: Desktop **`SPC-LAST-CRASH.log`** is written automatically — send that to chAos. If poker is still open, click **Send Debug Log**. |

Debug log also lives at `win-x64\save\SPC-Debug.log` while poker is running.

