# ⏱ Countdown Klok

Een strakke digitale countdown klok voor presentaties, quizzen en evenementen. Zelfde stijl als het Quiz Scorebord.

---

## 🚀 Live zetten via GitHub Pages

1. Upload `index.html` en `README.md` naar je repository
2. Ga naar **Settings → Pages**
3. Kies bij *Branch*: `main` → map: `/ (root)` → klik **Save**
4. Na een minuutje live op:
   ```
   https://<gebruikersnaam>.github.io/<repo-naam>/
   ```

---

## 🎮 Bediening

| Knop / Toets | Actie |
|---|---|
| **▶ Start** | Start de timer |
| **⏸ Pauze** | Pauzeer (tijd bevriest) |
| **▶ Hervat** | Hervat na pauze |
| **⏹ Stop** | Stop (timer blijft staan) |
| **↺ Reset** | Terugzetten naar ingestelde tijd |
| **Spatiebalk** | Start / Pauze toggle |
| **R** | Reset |

---

## 🎨 Visuele feedback

- **Wit** → normaal aftellen
- **Goud** → laatste 10 seconden
- **Rood + pulseren** → laatste 5 seconden
- **Flash + "Tijd is om!"** → timer bereikt nul
- **Cirkel-voortgangsbalk** op de achtergrond

---

## 💡 Tips

- Gebruik **volledig scherm** voor presentaties: `Cmd+Shift+F` (Mac) of `F11` (Windows)
- Aanpassen via de invoervelden (min : sec) — de klok toont meteen een preview
- Seconden worden automatisch begrensd op 0–59
