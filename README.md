# Testprojekt — statische Website

Ein schlichtes Grundgerüst aus HTML und CSS. Kein Build, keine Abhängigkeiten.

## Dateien

| Datei | Inhalt |
| --- | --- |
| `index.html` | Startseite |
| `ueber.html` | Über-Seite |
| `kontakt.html` | Kontaktseite |
| `style.css` | Gestaltung für alle Seiten |

## Lokal ansehen

`index.html` im Datei-Explorer doppelklicken — fertig. Ein Server wird nicht benötigt.

## Veröffentlichen über GitHub Pages

1. Auf [github.com](https://github.com) ein neues Repository anlegen (z. B. `testprojekt`), Sichtbarkeit **Public**.
2. Die vier Dateien oben ins Repository hochladen.
3. Im Repository: **Settings → Pages**.
4. Unter *Build and deployment* → *Source*: **Deploy from a branch**, Branch `main`, Ordner `/ (root)`, speichern.
5. Nach ein bis zwei Minuten ist die Seite erreichbar unter
   `https://<benutzername>.github.io/testprojekt/`

## Hinweis zum Kontaktformular

GitHub Pages liefert nur fertige Dateien aus und verarbeitet keine Formulare.
Das Formular auf `kontakt.html` ist deshalb reine Oberfläche; zum Versenden
bräuchte es später einen externen Dienst.
