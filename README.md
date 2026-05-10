# ⚡ High Voltage – AC/DC Fan PWA

## Dateien
- `index.html` – Die komplette App
- `manifest.json` – PWA Konfiguration
- `sw.js` – Service Worker (Offline-Support)
- `icon-192.svg` – App Icon klein
- `icon-512.svg` – App Icon groß

---

## 🚀 Schritt-für-Schritt: App auf Android installieren

### Option A: Netlify Drop (einfachster Weg, 2 Minuten)

1. Gehe auf **https://app.netlify.com/drop**
2. Ziehe den kompletten Ordner `acdc-pwa` per Drag & Drop ins Browserfenster
3. Netlify gibt dir eine URL wie `https://amazing-name-123.netlify.app`
4. Öffne diese URL in **Chrome** auf deinem Android-Gerät
5. Tippe auf die **drei Punkte** oben rechts
6. Wähle **„Zum Startbildschirm hinzufügen"**
7. ✅ Die App erscheint wie eine native App auf deinem Homescreen!

### Option B: GitHub Pages (kostenlos, dauerhaft)

1. Erstelle ein kostenloses Konto auf **https://github.com**
2. Erstelle ein neues Repository (z.B. `acdc-fan-app`)
3. Lade alle Dateien hoch (Upload files)
4. Gehe zu Settings → Pages → Source: main branch
5. Deine App ist live unter `https://DEINNAME.github.io/acdc-fan-app`
6. URL in Chrome Android öffnen → Zum Startbildschirm hinzufügen

---

## 🔑 Anthropic API Key einrichten

Für KI-Features (News, Quiz, Chat) brauchst du einen API Key:

1. Gehe auf **https://console.anthropic.com**
2. Registriere dich (kostenlos, Guthaben inklusive)
3. Unter API Keys → „Create Key"
4. Öffne `index.html` in einem Texteditor
5. Suche nach `https://api.anthropic.com/v1/messages`
6. Die App sendet den Key direkt – für eine öffentliche App empfiehlt sich ein Backend

**Hinweis:** Für den persönlichen Gebrauch reicht der direkte API-Aufruf.
Für eine öffentliche App einen kleinen Backend-Proxy aufsetzen.

---

## ✨ Features

- 📰 **News** – Archiv + KI-generierte Live-News via Claude
- 💿 **Diskographie** – 9 Alben mit Tracklisten + iTunes Hörvorschau
- 📖 **Geschichte** – Timeline + legendäre Konzerte
- ⚡ **Thunder Quiz** – KI-generierte Hardcore-Fragen via Claude
- 📣 **Fan-Wand** – Lokale Shoutout-Wall
- 🤖 **KI-Chat** – AC/DC Experte powered by Claude
- 🌙 **Dark/Light Mode** – Gespeichert im Browser
- 📱 **PWA** – Installierbar auf Android & iOS

---

## 📱 PWA auf iOS (iPhone/iPad)

1. URL in **Safari** öffnen (nicht Chrome!)
2. Teilen-Button (Rechteck mit Pfeil) antippen
3. „Zum Home-Bildschirm" wählen
4. ✅ Fertig!
