<div align="center">

# 🌸 PINK CHAMBER 11 🌸

### *Sneak. Decode. Take down the Baron.*

A mobile-first stealth-espionage game where every clue can only be cracked with **[TeamLegacy OmniTool V3](https://2ndchances520.github.io/OmniToolV3/)**.

![Single File](https://img.shields.io/badge/single%20file-HTML5-ff4fa3?style=for-the-badge)
![Mobile First](https://img.shields.io/badge/mobile-first-ff9fd0?style=for-the-badge)
![No Dependencies](https://img.shields.io/badge/dependencies-zero-c0267a?style=for-the-badge)
![Powered by OmniTool](https://img.shields.io/badge/powered%20by-OmniTool%20V3-ffe38a?style=for-the-badge&labelColor=26000f)

<img src="screenshots/gameplay.png" alt="Pink Chamber 11 gameplay" width="260">&nbsp;&nbsp;<img src="screenshots/puzzle.png" alt="Pink Chamber 11 puzzle screen" width="260">

</div>

---

## 🕵️ The Story

German arms dealer **Baron Konrad von Eisenfeld** is selling a guided weapon codenamed **CHIMERA**. Nobody else is coming.

You are **Rachel**, a lone agent of the Pink Chamber. Across six sectors of Europe, from the Hamburg docks to the Baron's own estate vault, you slip past patrolling guards, steal evidence briefcases, and decode the intercepted intel. Piece it together, and the dossier goes live.

## 🎮 Gameplay

- **Stealth:** Guards patrol with glowing vision cones. Stay out of sight or get spotted and sent back to the start of the room.
- **Collect:** Grab the briefcase in each sector to secure the clue.
- **Decode:** The clue is encrypted in a format that only **OmniTool** can crack. Copy it, decode it, type the answer, and unlock the exit.
- **Escape:** Reach the exit door before the guards reach you.

### Controls

| Action | Touch | Keyboard |
|---|---|---|
| Move (push far to run) | Floating thumb stick, left side | `WASD` / arrow keys |
| Inspect briefcase | **ACT** | `E` |
| Stun a nearby guard | **KICK** | `Space` |
| Crouch and stay quiet | **SNEAK** | `C` |
| Reopen the clue | **CLUE** | n/a |

Sneaking shrinks your detection range. Running makes you easier to spot.

## 🧩 The Six Missions

| # | Operation | Sector | Clue format | OmniTool module |
|---|---|---|---|---|
| 1 | Pink Ledger | Hamburg Docks | Hidden message inside a dispatch | **Steganography** |
| 2 | Iron Waltz | Berlin Embassy Archive | Base64 | **Base64 Vault** |
| 3 | Iron Rail | Munich Rail Depot | Ascii85 | **Ascii85 Vault** |
| 4 | Clockwork Enigma | Zurich Private Bank | Enigma ciphertext | **Enigma Simulator** (linked from OmniTool) |
| 5 | Ghost Eye | Vienna State Opera | QR security plate | **QR Scanner** |
| 6 | Chimera | Eisenfeld Estate Vault | Steganography, then Base64 | **Steganography + Base64 Vault** |

Stuck? Every puzzle has a **HINT** button that shows the exact menu path on OmniTool.

## 🚀 Play It

**Online:** open the hosted page (add your GitHub Pages link here).

**Locally:** download `pink-chamber-11.html` and open it in any modern browser. No build step and no install.

**On GitHub Pages:**
1. Put `pink-chamber-11.html` in your repo (rename it to `index.html` for a clean URL).
2. Go to **Settings → Pages**, choose your branch and the root folder, and save.
3. Open the link on your phone.

> 💡 The in-game **COPY INTERCEPT** button uses the browser clipboard, which works best on `https://` pages such as GitHub Pages.

## 🛠️ Tech

- One self-contained `.html` file: HTML, CSS and vanilla JavaScript on a `<canvas>`
- Rachel's animated sprite atlas is embedded as base64, so it works offline
- [`qrcode-generator`](https://github.com/kazuhikoarase/qrcode-generator) is inlined for the QR mission
- Sound effects are synthesized live with the Web Audio API, so there are no audio files
- Pointer Events power the multi-touch controls
- Progress is saved with `localStorage`

## 📁 Repo Layout

```
.
├── pink-chamber-11.html   # the entire game
├── screenshots/           # images used in this README
└── README.md
```

## 🔗 Links

- 🛠️ **OmniTool V3:** https://2ndchances520.github.io/OmniToolV3/
- 🎖️ Inspired by *Operation Black Chamber 10*

## 📜 Credits

- Game design and story: TeamLegacy
- Character sprite: Rachel sprite sheet (custom artwork)
- QR generation: [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) (MIT)

## 📄 License

Add your license here (for example MIT) before publishing.

---

<div align="center">

*Pink Chamber 11 · Decode the truth. Take down the Baron.*

</div>
