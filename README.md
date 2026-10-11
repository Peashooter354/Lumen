# Lumen Launcher

Konsolen-Launcher mit Lichtkegel, Sternen, Sounds und Controller-Steuerung.

## Starten
1. Node.js installieren (https://nodejs.org, LTS-Version)
2. `Start.bat` doppelklicken (installiert beim ersten Mal alles automatisch)

## Eigene .exe zum Starten bauen
`npm install` und danach `npm run dist` erzeugt eine portable Lumen.exe im Ordner `dist`.

## Bedienung
- Spiele hinzufügen: Plus-Kachel, oder .exe einfach ins Fenster ziehen
- Pfeiltasten / Controller (D-Pad, Stick) navigieren, Enter / A wählt, Esc / B geht zurück
- F11: Vollbild
- Doppelklick auf eine Kachel startet das Spiel direkt
- Daten liegen unter %APPDATA%\lumen-launcher\launcher-data.json

## Discord
- Unten gibt es eine **Schnellzugriff-Leiste** (wie das Control Center der PS5): Hauptmenü, Meine Spiele, Discord, Einstellungen, Vollbild, Beenden. Mit den Pfeiltasten oder dem Controller kommst du aus dem Menü nach unten in die Leiste.
- Das **Discord-Symbol** in der Leiste öffnet darüber ein Panel mit Seitenleiste. Im Panel: Neu laden, Vergrößern/Verkleinern (Vollbild) und Schließen. Ein Klick neben das Panel oder erneut auf das Symbol schließt es ebenfalls.
- Es ist der offizielle Discord-Web-Client direkt im Launcher, ein externer Browser ist nicht nötig. Discord sieht dabei eine normale Browser-Sitzung (Chrome), nicht den Desktop-Client.
- Links aus Chats öffnen sich im Standardbrowser.
- Anmelden wie gewohnt auf der Discord-Seite (Passwort, QR-Code oder 2FA). Die Anmeldung bleibt gespeichert, ohne dass der Launcher dein Passwort zu sehen bekommt.
- Zurück zum Launcher: **X** oben rechts im Panel, ein Klick neben das Panel oder Esc (wenn der Fokus nicht in Discord liegt). F11 für Vollbild geht auch in Discord.
- Neue Nachrichten zeigt ein Abzeichen am Discord-Symbol an. Windows-Benachrichtigungen kommen von Discord selbst.
- Die Menümusik pausiert, solange Discord offen ist.
- Abmelden: in Discord unten links auf das Zahnrad, dann „Abmelden“. Die Anmeldedaten liegen unter `%APPDATA%\lumen-launcher\Partitions\discord`.

 **Mit Microsoft anmelden** → Lumen zeigt einen Code und öffnet den Browser → Code eingeben → fertig. Die Anmeldung bleibt gespeichert (verschlüsselt über Windows).

### Mods
- Mods brauchen den **Fabric-Loader** (bei der Versionswahl einschalten). Pro Version und Loader gibt es einen eigenen Spielordner, damit sich Mods nicht in die Quere kommen.
- **Modrinth** funktioniert ohne Schlüssel. Pflicht-Abhängigkeiten (z. B. Fabric API) werden automatisch mitinstalliert.
- **CurseForge** braucht einen kostenlosen API-Key von https://console.curseforge.com (in den Minecraft-Einstellungen eintragen). Erlaubt ein Autor keinen Download außerhalb von CurseForge, öffnet Lumen stattdessen die Mod-Seite im Browser.
- Nicht enthalten: Forge/NeoForge/Quilt, Modpacks, Skins.

### Dateien
Alles liegt unter `%APPDATA%\lumen-launcher\minecraft\` (Spielordner unter `instances\`, Startprotokoll `lumen-start.log` für Fehlersuche).
