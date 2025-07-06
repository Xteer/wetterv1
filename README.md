# 🌤️ Wetter App

Eine einfache, mobilfreundliche Wetter-App, die mit modernen Webtechnologien und kostenlosen APIs wie [Open-Meteo](https://open-meteo.com/ ) und [Nominatim OpenStreetMap](https://nominatim.openstreetmap.org/ ) arbeitet.

---

## 📋 Überblick

Diese App zeigt das aktuelle Wetter sowie den Temperaturverlauf der nächsten 24 Stunden an. Sie enthält:
- Eine Suchleiste für Orte (Geocoding)
- Eine dynamische SVG-Temperaturkurve
- Wettericons direkt im Diagramm
- Eine 3-Tagesvorhersage mit Höchst- und Tiefsttemperaturen
- Ein responsives Design – optimiert für mobile Geräte

Die App benötigt **keine API-Schlüssel** oder Anmeldung und ist als statische Seite konzipiert – ideal für GitHub Pages oder andere Hosting-Plattformen.

---

## 🛠️ Technologie & Abhängigkeiten

| Technologie | Verwendung |
|------------|-------------|
| HTML / CSS / JavaScript | Basisstruktur und Logik |
| TailwindCSS via CDN | Styling ohne Build-Prozess |
| Open-Meteo API | Wetterdaten ohne Limit |
| Nominatim OpenStreetMap API | Geocoding von Städtenamen |

> ⚠️ Hinweis: `cdn.tailwindcss.com` sollte in einer Produktionsumgebung nicht verwendet werden. Für eine stabile Bereitstellung solltest du Tailwind per CLI oder PostCSS lokal builden.

---

## 🧩 Lizenzen & Urheberrechte

### 📜 Code-Lizenz
Dieses Projekt steht unter der [MIT License](LICENSE). Du darfst den Code verwenden, modifizieren und weiterverteilen, solange die Lizenz beibehalten wird.

### 🎨 Grafiken & Icons
Die verwendeten Wetter-Symbole sind **Emojis** (öffentlich zugänglich) und fallen unter die Unicode Consortium Lizenz.  
Falls SVG-Icons hinzugefügt werden, gelten folgende Quellen:

- **Material Icons** von Google: [https://fonts.google.com/icons ](https://fonts.google.com/icons )  
  → Lizenz: [Apache 2.0 License](https://fonts.google.com/attribution )

- **Wettergrafiken (optional)** können aus der OpenWeatherMap Icon-Bibliothek stammen: [https://openweathermap.org/weather-conditions#Icon]( https://openweathermap.org/weather-conditions#Icon)  
  → Lizenz: [CC BY-SA 4.0]( https://creativecommons.org/licenses/by-sa/4.0/deed.en )

---

## 📥 Installation

1. **Lade `index.html` herunter**
2. Öffne sie lokal im Browser oder lade sie auf einen Server/GitHub Pages hoch.
3. Keine weitere Konfiguration erforderlich – die App funktioniert sofort.

---

## 🌐 Online Demo

Du kannst diese App direkt testen unter:  
👉 [GitHub Pages Link (coming soon)](https://dein-benutzername.github.io/wetter-app/ )

---

## 💡 Erweiterungsideen

- SVG-Wettericons statt Emojis einbetten
- Hover-Tooltips zur Anzeige der genauen Temperatur
- Dark Mode Toggle
- PWA-Unterstützung (installierbar, Offline-Caching)
- Sprachauswahl (de/en/fr)
- Audiofeedback bei Regen/Schnee

---

## 🧾 Rechtliche Hinweise

- Die verwendeten APIs (Open-Meteo, Nominatim) sind **kostenlos nutzbar**, jedoch gilt es, deren Nutzungsbedingungen zu beachten:
  - [Open-Meteo Terms of Service](https://open-meteo.com/en/docs )
  - [Nominatim Usage Policy](https://operations.osmfoundation.org/policies/nominatim/ )

- Die App speichert **keine Daten** außerhalb des Browsers (kein Tracking, keine Cookies).

- Die App verwendet **keine Fonts oder Ressourcen**, die urheberrechtlich geschützt sind, außer wo explizit genannt.

---

## 🧑‍💻 Mitwirken

Jeder ist willkommen, Fehler zu melden oder Verbesserungen vorzuschlagen.  
Bitte erstelle Issues oder Pull Requests über GitHub.

---

## ✅ Danksagung

Vielen Dank an:
- Das Open-Meteo Team für die kostenlose Wetter-API
- Die OpenStreetMap Community für den Geocoding-Service
- Den TailwindCSS Entwicklern für das flexible CSS-Framework

---

## 📄 MIT License
