# 📺 WebTV Client

Ein minimalistischer, rein clientseitiger Web-Player für IPTV-Streams. Diese Anwendung läuft direkt im Browser und benötigt keine Installation von Zusatzsoftware. Perfekt geeignet, um IPTV-Playlists auf dem PC, Tablet, Smartphone oder Smart-TV abzuspielen.

🚀 **[Hier geht es zur Live-Anwendung](https://michdo93.github.io/webtv/)**

---

## ✨ Features

* **Zero-Setup:** Keine Installation nötig – läuft vollständig als statische Web-App auf GitHub Pages.
* **Immer aktuell:** Die Wiedergabelisten werden über die GitHub-API in Echtzeit geladen. Sobald das Quell-Repository aktualisiert wird, stehen die neuen Streams auch hier zur Verfügung.
* **HLS-Support:** Dank `hls.js` werden `.m3u8`-Streams nativ in fast allen modernen Browsern (Chrome, Firefox, Edge, Safari) unterstützt.
* **Dynamic Parsing:** Filtert automatisch Sendernamen direkt aus den geladenen Playlists.

---

## 📡 Datenquelle & Streams

Dieser Client stellt selbst keine Streams bereit. Er dient ausschließlich als Benutzeroberfläche für das großartige, öffentlich zugängliche IPTV-Projekt von **Free-TV**. 

Die Listen und Stream-URLs werden direkt aus folgendem Repository bezogen:
🔗 **[Free-TV / IPTV (GitHub)](https://github.com/Free-TV/IPTV/tree/master)**

Ein großes Dankeschön an die Maintainer des Free-TV-Projekts für die Pflege der Länder-Playlists!

---

## 🛠️ Technische Details

Da GitHub Pages rein statisches Hosting bietet, basiert die gesamte Anwendung auf:
* **HTML5 & CSS3** (inklusive responsivem Design für Mobilgeräte)
* **Vanilla JavaScript** (nutzt die GitHub REST API und Fetch-API)
* **[hls.js](https://github.com/video-dev/hls.js/)** (Media Source Extensions Bibliothek für das HLS-Streaming)

---

## 🚀 Eigenen Klon starten (Optional)

Wenn du dieses Projekt für dich selbst anpassen oder hosten möchtest, reicht ein einfacher Fork:

1. **Forke** dieses Repository.
2. Gehe in deinem geforkten Repo auf **Settings > Pages**.
3. Wähle unter *Build and deployment* deinen `main`- oder `master`-Branch aus und klicke auf **Save**.
4. Deine eigene TV-App ist in wenigen Minuten online!

---

## ⚖️ Rechtlicher Hinweis / Disclaimer

Dieses Projekt (`webtv`) ist ein reiner Streaming-Client (Player). Es hostet, speichert oder verbreitet keine eigenen Videos, Streams oder urheberrechtlich geschützten Inhalte. Alle Playlists werden dynamisch von externen, öffentlich zugänglichen Repositories geladen. Für die Legalität der gestreamten Inhalte sind ausschließlich die Betreiber der jeweiligen Streams oder die Bereitsteller der Playlists verantwortlich.
