# Rebar310.github.io

Detta repo innehåller min **personliga hemsida / online-CV**, byggd med  
**GitHub Pages** och **Jekyll** med temat **Minima**.

Sidan är en **one-page resume** där all information visas på samma sida.

🌐 Live-sida: https://rebar310.github.io

---

## 🧱 Teknik
- **GitHub Pages**
- **Jekyll**
- **Minima theme**
- **Markdown + HTML/CSS**

Jag använder Markdown för innehåll och lite HTML/CSS för layout (t.ex. bild + text i kolumner).

---

## 📄 Innehåll på sidan
Startsidan (`index.md`) innehåller:

- Profilbild
- “Om mig”-sektion
- Länk till mitt CV (PDF)
- Länkar till projekt
- Kontaktuppgifter (placerade i footern)

Allt visas på **en och samma sida**, utan extra flikar.

---

## 📁 Mappstruktur
```text
.
├── _config.yml          # Jekyll-konfiguration (tema, titel m.m.)
├── index.md             # Själva webbsidan (one-page resume)
├── README.md            # Denna fil
├── assets/
│   └── img/
│       └── profile.jpg # Profilbild
├── files/
│   └── cv.pdf           # CV (PDF)
├── projects/
│   └── project1.pdf     # Projektfiler
└── _includes/
    └── footer.html      # Egen footer med kontaktlänkar

