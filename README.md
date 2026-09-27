# Daily

Persönliche Web-App, mit der du deine tägliche Mobility- und Kräftigungsroutine planst und verfolgst. Läuft auf dem iPhone vom Home-Bildschirm, offline, ohne Login. Alle Daten bleiben auf dem Gerät.

## Auf GitHub Pages veröffentlichen (einmalig, ca. 5 Minuten)

1. Auf github.com einloggen und oben rechts auf **+ → New repository** gehen.
2. Name: `daily`. Sichtbarkeit: **Public** (für GitHub Pages im Gratis-Tarif nötig; im Repo liegt nur der App-Code, keine persönlichen Daten). Auf **Create repository** klicken.
3. Auf der leeren Repo-Seite **uploading an existing file** anklicken.
4. Den **Inhalt** des entpackten Ordners hineinziehen: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` und den Ordner `icons`. Dann **Commit changes**.
5. Im Repo **Settings → Pages** öffnen. Unter *Build and deployment* als Source **Deploy from a branch** wählen, Branch **main**, Ordner **/ (root)**, **Save**.
6. Nach etwa einer Minute ist die App erreichbar unter
   `https://<dein-github-name>.github.io/daily/`

## Auf dem iPhone installieren

1. Die URL in **Safari** öffnen.
2. **Teilen** antippen und **Zum Home-Bildschirm** wählen.
3. Daily ab jetzt immer über das Icon öffnen. Nur dann bleiben die Daten dauerhaft gespeichert.

## Updates einspielen

Geänderte Dateien im Repo erneut hochladen (gleiche Namen überschreiben). Bei Änderungen an der App in `sw.js` die Versionsnummer in `CACHE` erhöhen, damit das iPhone die neue Version lädt. Gegebenenfalls die App einmal schließen und neu öffnen.

## Backup

Unter **Mehr → Backup exportieren** speicherst du eine JSON-Datei, z. B. in iCloud Drive. Mit **Backup importieren** holst du sie auf einem neuen Gerät zurück.

## Planungsregeln

- Du wählst abends 15, 20 oder 30 Minuten, der Plan wird passend zusammengestellt.
- Kräftigung eines Körperbereichs frühestens nach einem Ruhetag.
- Pro Tag ein Kraft-Schwerpunkt (z. B. Beine oder Oberkörper), damit der andere Teil am nächsten Tag dran ist.
- Dehnen und Mobilisieren sind jeden Tag erlaubt. Was am längsten nicht dran war, kommt zuerst.
- Tauschen, Überspringen und Hinzufügen jederzeit möglich.
