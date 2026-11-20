# Lernwerk als eigene App (GitHub Pages)

Der Ordner enthält die komplette App. Es ist keine KI und kein Konto bei einem KI-Dienst nötig.
Alles läuft auf deinem Gerät.

## 1. Bei GitHub veröffentlichen (am Computer, einmalig, kostenlos)
1. Auf github.com ein Konto anlegen oder einloggen.
2. Oben rechts "+" > "New repository". Name zum Beispiel "lernwerk". Auf "Public" stellen. "Create repository".
3. Auf der neuen Seite den Link "uploading an existing file" anklicken.
4. Den Inhalt des entpackten Ordners "lernwerk-app" ins Fenster ziehen: index.html, sw.js, manifest.webmanifest, alle PNG-Dateien und den Ordner "pdfjs". Nicht die ZIP-Datei selbst hochladen, GitHub entpackt sie nicht.
5. Warten, bis alles hochgeladen ist, dann unten "Commit changes".
6. "Settings" > links "Pages". Unter "Build and deployment" bei "Source" "Deploy from a branch" wählen, bei "Branch" "main" und "/ (root)", dann "Save".
7. Nach ein bis zwei Minuten Seite neu laden. Oben steht deine Adresse: https://DEINNAME.github.io/lernwerk/

## 2. Aufs Handy bringen
Android (Chrome): Adresse öffnen > Menü (drei Punkte) > "App installieren" oder "Zum Startbildschirm hinzufügen".
iPhone (Safari): Adresse öffnen > Teilen-Symbol > "Zum Home-Bildschirm".
Danach startet Lernwerk wie eine normale App und funktioniert auch ohne Internet.

## 3. Gut zu wissen
- Die neue Adresse ist eine neue App. Deine Themen aus der alten Netlify-Version sind dort nicht drin. Nimm sie über "Themen" > "Sicherung" mit: in der alten App "Als Datei speichern" oder "Text kopieren", in der neuen App "Sicherung aus Datei einlesen" oder den Text einfügen.
- Deine Themen liegen im Browser deines Handys. Browserdaten löschen entfernt sie auch.
- Updates: Im Repository auf die Datei klicken, Stift-Symbol, oder "Add file" > "Upload files" und gleichnamige Dateien ersetzen. Nach ein bis zwei Minuten holt sich die App die neue Version beim nächsten Start mit Internet.
- Nicht dabei: Chat, Wünsche und Bilder-Import (dafür wäre eine KI nötig).
