# All My Ex's Live In Texas – Website

Coverband-Website für GitHub Pages.

## Struktur

```
/
├── index.html          ← Hauptseite (alle Seiten als SPA)
├── assets/
│   ├── logo.png
│   ├── band_photo1.jpg
│   ├── band_photo2.jpg
│   ├── band_photo3.jpg
│   └── band_photo4.jpg
└── README.md
```

## Deployment auf GitHub Pages

1. Neues Repository auf GitHub anlegen (z. B. `allmyexs-website`)
2. Alle Dateien **exakt so** in das Repository hochladen (Ordnerstruktur beibehalten)
3. In den Repository-Einstellungen: **Settings → Pages → Source: Deploy from branch → main / (root)**
4. Nach ~1 Minute ist die Seite erreichbar unter:  
   `https://<dein-github-nutzername>.github.io/allmyexs-website/`

> **Tipp:** Eigene Domain (z. B. `allmyexs.de`) kann unter Settings → Pages → Custom domain eingetragen werden. Dazu beim Domain-Anbieter einen CNAME-Eintrag auf `<nutzername>.github.io` setzen.

## YouTube-Videos

Die Videos werden über `youtube-nocookie.com` eingebettet – das behebt den **Fehler 153**, der bei `youtube.com/embed` auftreten kann, wenn die Videos eingeschränkte Embed-Einstellungen haben. `youtube-nocookie.com` ist Googles datenschutzfreundlichere Embed-Variante und unterliegt weniger Restriktionen.

## Kontaktformular

Das Kontaktformular ist aktuell nur ein Frontend-Demo (zeigt eine Erfolgsmeldung an). Für echten E-Mail-Versand kann ein Dienst wie [Formspree](https://formspree.io) oder [Web3Forms](https://web3forms.com) kostenlos eingebunden werden.
