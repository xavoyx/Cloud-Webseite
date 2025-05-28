# Persönliche Cloud-Webseite 🌐


Eine moderne, clientseitige Webanwendung, die als persönliche Cloud-Lösung dient. Benutzer können sich anmelden, beliebige Dateien hochladen, Notizen erstellen und löschen sowie ihre Daten als JSON exportieren. Die Anwendung nutzt ein dunkles Theme mit flüssigen Animationen und speichert alle Daten lokal im Browser mit `localStorage`.

## 🚀 Funktionen

- **🔒 Login und Registrierung**: Sichere Anmeldung und Registrierung mit Benutzername und Passwort.
- **📤 Datei-Upload**: Hochladen beliebiger Dateitypen (als Base64 codiert) für Cloud-ähnliche Speicherung.
- **📝 Notizen**: Erstellen und Löschen von Notizen mit einem Mülleimer-Symbol (🗑️).
- **🗑️ Datei-Löschen**: Einzelne Dateien können über ein Mülleimer-Symbol gelöscht werden.
- **💾 Daten-Export**: Export von Dateien und Notizen als `user_data_<username>.json`.
- **👥 Benutzerdaten-Export**: Alle Benutzeranmeldedaten als `all_users.json`.
- **🎨 Design**: Dunkles Theme mit sanften Animationen (Fade-In, Pulse, Hover-Effekte).
- **🌍 Clientseitig**: Kein Server erforderlich, alles läuft im Browser.

## 🛠️ Technologien

- **HTML/CSS**: Reines CSS für ein modernes, dunkles Design ohne Frameworks.
- **JavaScript**: Clientseitige Logik mit `localStorage` für Datenspeicherung.
- **Base64**: Dateien werden als Base64 codiert, um beliebige Dateitypen zu unterstützen.
