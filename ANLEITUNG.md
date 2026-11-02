# Putting-Tempo aufs iPhone bringen

Die App ist eine Web-App. Sie muss einmal im Internet liegen (kostenlos über GitHub Pages), danach legst du sie auf den Homescreen. Ab dann läuft sie im Vollbild und auch offline.

## 1. Online stellen (GitHub Pages, einmalig)

1. Auf github.com ein kostenloses Konto anlegen bzw. anmelden.
2. Oben rechts „+“ → „New repository“, Name z. B. `putting`, Sichtbarkeit „Public“, „Create repository“.
3. Auf der Repository-Seite „uploading an existing file“ anklicken und den **Inhalt** dieses Ordners hineinziehen (index.html, manifest.webmanifest, sw.js, die Ordner icons und lib). „Commit changes“.
4. „Settings“ → „Pages“ → bei „Branch“ `main` und `/ (root)` wählen → „Save“.
5. Nach ein bis zwei Minuten steht oben die Adresse, z. B. `https://DEINNAME.github.io/putting/`.

## 2. Auf den Homescreen legen

1. Die Adresse auf dem iPhone in **Safari** öffnen.
2. Teilen-Symbol → „Zum Home-Bildschirm“ → „Hinzufügen“.
3. Die App über das neue Symbol öffnen (nicht über Safari) – sonst sieht sie andere gespeicherte Daten.

## Gut zu wissen

- **Daten** (auch Journal und Fotos) liegen nur auf diesem iPhone. Unter Zahnrad → „Sicherung speichern“ legst du eine Datei an (z. B. in iCloud Drive); „Sicherung laden“ holt sie zurück.
- **Gefälle messen** funktioniert in dieser Version: Beim ersten Tippen auf „Messen“ fragt iOS nach dem Zugriff auf Bewegungsdaten – mit „Erlauben“ bestätigen.
- **PDF**: „Tabellen als PDF exportieren“ öffnet das Teilen-Menü – dort „Drucken“ oder „In Dateien sichern“.
- **Updates**: Neue Version einfach wieder in das Repository hochladen. Die App lädt sie beim nächsten Öffnen mit Internet.
- Die Daten aus der Claude-Version werden nicht automatisch übernommen. Trag deine Tabellen einmal neu ein.
