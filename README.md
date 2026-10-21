# UniStudy – Downloads

Hier gibt es die fertige Windows-App **UniStudy**: Vorlesungsfolien hochladen, automatisch zusammenfassen lassen und mit Quellenangaben Fragen dazu stellen.

## Installieren

1. Unter [**Releases**](https://github.com/Trollmate/uni-study-releases/releases/latest) die Datei `UniStudy-Setup-<version>.exe` herunterladen.
2. Ausführen. Windows zeigt eine SmartScreen-Warnung, weil die App nicht signiert ist: **„Weitere Informationen“ → „Trotzdem ausführen“**.
3. Beim ersten Start führt dich ein kurzer Assistent durch die Einrichtung.

Updates kommen danach automatisch: Die App lädt neue Versionen im Hintergrund und installiert sie beim nächsten Neustart.

## Erste Schritte

- **Datenordner:** Wähle einen Ordner in OneDrive, Dropbox oder Google Drive, wenn du PC und Laptop nutzt. Dann haben beide Geräte denselben Stand. Öffne dasselbe Fach nicht gleichzeitig auf beiden Geräten.
- **KI lokal (kostenlos):** [Ollama](https://ollama.com/download) installieren und starten. Die App empfiehlt ein Modell passend zu deinem Gerät und lädt es auf Knopfdruck herunter.
- **KI in der Cloud (bessere Antworten):** Einen API-Schlüssel von [Anthropic (Claude)](https://console.anthropic.com/settings/keys) oder [OpenAI](https://platform.openai.com/api-keys) in den Einstellungen eintragen. Der Schlüssel wird verschlüsselt nur auf deinem Gerät gespeichert.
- Beim ersten Hochladen lädt die App einmalig ein Suchmodell (~280 MB) und Sprachdaten für die Texterkennung.

## Systemanforderungen

Windows 10 oder 11 (64 Bit). Für lokale KI empfohlen: 16 GB RAM oder eine NVIDIA-Grafikkarte mit 8 GB+.
