# ACNH SuperPoker — Share Pack

Fixed **SuperPoker** build for Strobe/Nookmart order delivery (Run Dodo, order JSON, dropper). Images are **not** included — the app downloads them on first launch (~90 MB).

## Download

**Get the zip from [Releases](https://github.com/YOUR_USERNAME/ACNHSuperPoker-Share/releases/latest)** → `ACNHSuperPoker-Share-2026-07-04.zip`

## Requirements

- **Windows 10/11**
- **[.NET 9 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/9.0)** (Desktop, not SDK)
- Switch on CFW with **sys-botbase 2.x** (port **6000**)
- ACNH running on the Switch

## First-time setup

1. Extract the zip anywhere (e.g. `C:\SuperPoker\`).
2. Run **`win-x64\ACNHPokerCore.exe`** — wait for item images to download.
3. Enter your Switch **IP** → click **Connect**.
4. Open **Dutch Sailors** (Dodo Helper button on main window) once and **click its title bar** so keyboard control works.
5. In Dutch Sailors, set **anchors** (airport = slot 2, Orville = slot 3) using the anchor test buttons — one-time setup.

---

## Custom features (vs stock SuperPoker)

| Feature | What it does |
|---------|----------------|
| **Crash fix** | Run Dodo / teleport no longer hard-crash on bad sys-botbase data |
| **Load Order** | Loads Strobe `order.json` → fills drop queue + dodo code |
| **Run Dodo** | Auto-travel to airport, talk to Orville, enter dodo code |
| **Import Pockets** | Builds drop queue from items already in Switch pocket RAM |
| **Dropper** | Auto-drops loaded queue on the island (respects pause-after-9) |
| **Dutch Sailors** | Renamed Dodo Helper window with **keyboard-first** controls |
| **Chat presets** | Keys **1–6** send canned messages (editable in `strobe\_chat_presets.json`) |
| **Window linking** | Main + Dutch Sailors + Chat windows move together |
| **Instant Text** toggle | Speeds up Orville dialog during Run Dodo |
| **In Airport** toggle | Skip airport entry if you're already inside |
| **A→Z sort** toggle | Sort loaded order items alphabetically |
| **Resume drop index** | Start dropper from item N (box + **Set Start**) |
| **Themes** | Default / Red / Black / Splatoon (config `DodoTheme`) |

---

## Keyboard reference (Dutch Sailors window)

**Click the Dutch Sailors window once** so it has focus. Title bar shows:  
`Dutch Sailors -> Click here to allow keyboard control <-`

### Order workflow (minimal mouse)

| Step | Mouse? | Action |
|------|--------|--------|
| Connect | Once | Main window → IP → Connect |
| Load order | Once | Main → **Load Order** → pick `.json` |
| Run Dodo | Once | Main → **Run Dodo** (needs dodo code in box from order) |
| Drop items | **Keyboard only** | Dutch Sailors focused → **`9`** toggles dropper |
| Chat customer | **Keyboard only** | **`1`–`6`** presets, or chat mode below |

### Hotkeys (Dutch Sailors focused)

| Key | Action |
|-----|--------|
| **`9`** | Start / pause **dropper** |
| **`1`–`6`** | Send chat preset 1–6 |
| **Right Ctrl** or **Right Shift** | Toggle **chat typing mode** |
| **Enter** | Send chat message (in chat mode) |
| **Backspace** | Delete in chat box (in chat mode) |
| **`W` `A` `S` `D`** | Move (hold) |
| **`I` `J` `K` `L`** | Camera / look (hold) |
| **`R`** | Minus (−) |
| **`Y`** | Plus (+) |
| **`Q`** | ZL |
| **`O`** | ZR |

---

## Typical order (keyboard-heavy)

1. **Connect** (mouse once).
2. **Load Order** → select Strobe JSON. Dodo code fills automatically.
3. **Run Dodo** (mouse once). Leave **Instant Text** on.
4. Click **Dutch Sailors** title bar (focus).
5. **`1`** greet → **`9`** dropper → **`2`–`6`** chat as needed.

**Tip:** Enable **Pause after 9** — auto-pauses every 9 drops.

---

## Troubleshooting

| Problem | Fix |
|---------|-----|
| Keys do nothing | Click **Dutch Sailors** title bar first |
| Run Dodo fails | Set anchors 2 & 3; connected; on overworld |
| No item icons | Wait for first-boot image download |

Based on [ACNHPokerCore](https://github.com/MyShiLingStar/ACNHPokerCore) / ACNHSuperPoker order fork.
