# Lizenz-Generator Anleitung und Erklärung 

Ein benutzerfreundliches Windows-Programm zum Erstellen und Überprüfen eindeutiger Lizenzschlüssel im Format `Lizenz=xxxxxxxxxxxxxxxxxxxxxx` (22 Ziffern). Schlüssel werden zusammen mit einem Namen in einer SQLite-Datenbank (`keys.db`) gespeichert. Generierte Schlüssel werden automatisch in die Zwischenablage kopiert. Das Programm bietet ein modernes, intuitives GUI.


>  **Generiere eindeutige Schlüssel**: Erstelle Lizenzschlüssel mit einem Namen (unterstützt Buchstaben, Zahlen, Sonderzeichen).
>  **Automatisches Kopieren**: Generierte Schlüssel werden direkt in die Zwischenablage kopiert (STRG+V zum Einfügen).
>  **Schlüssel überprüfen**: Prüfe, ob ein Schlüssel existiert, und zeige den zugehörigen Namen an.
>  **Datenbank**: Speichert Schlüssel und Namen in einer portablen Datei (`keys.db`).
>  **Modernes GUI**: Elegantes, dunkles Design für einfache Bedienung.


> [!IMPORTANT]
> Wie bleibe ich auf dem neusten Stand?
1. **Neueste Version herunterladen**:
   - Gehe zu den [Releases](https://github.com/Fryxz66/LizenzGenerator-ByFryxz/releases).
   - Lade die neueste `.exe`-Datei herunter (z. B. `LizenzGenerator-ByFryxz-v1.x.x.exe`).
   - **Wichtig**: Verwende immer die neueste Release-Version, um die aktuellsten Features und Fehlerkorrekturen zu erhalten.
2. Speichere die `.exe` in einem Ordner deiner Wahl (z. B. `C:\Users\DeinName\Dokumente\LizenzGenerator-ByFryxz`).
3. Doppelklicke auf `LizenzGenerator-ByFryxz-v1.x.x.exe`, um das Programm zu starten.


> [!TIP]
> Nutzung von dem Lizenz Generator.
1. **Key generieren**:
   - Gib einen Namen ein (z. B. „Max Mustermann!@#“).
   - Klicke auf „Key generieren & speichern“.
   - Der Schlüssel (z. B. `Lizenz=1234567890123456789012`) wird in `keys.db` gespeichert, automatisch in die Zwischenablage kopiert (STRG+V zum Einfügen) und im GUI angezeigt.
   - Ein Pop-up bestätigt: „Key gespeichert und kopiert“.

2. **Key überprüfen**:
   - Gib einen Schlüssel ein (z. B. `Lizenz=1234567890123456789012`).
   - Klicke auf „Key überprüfen“.
   - Das GUI zeigt, ob der Schlüssel existiert und welchem Namen er zugeordnet ist.


> [!WARNING]
> Dringende Informationen, die sofortige Aufmerksamkeit des Benutzers erfordern, um Probleme zu vermeiden.
- **Datenbank**: Die Datei `keys.db` wird im selben Ordner wie die `.exe` erstellt. Kopiere sie mit, wenn du die `.exe` verschiebst, um bestehende Schlüssel zu behalten.
- **Schreibrechte**: Stelle sicher, dass der Ordner Schreibrechte hat (z. B. nicht in `C:\Programme` speichern).
- **Windows-Kompatibilität**: Die `.exe` funktioniert auf Windows 10/11. Kein Python oder zusätzliche Software nötig.
- **Fehlerbehebung**: Falls die `.exe` nicht startet, prüfe, ob der Ordner schreibbar ist, oder lade die neueste Version aus den Releases herunter.


> [!NOTE]
> Information für Entwickler!
- Der Quellcode ist nicht enthalten, da das Programm als `.exe` verteilt wird.
- Möchtest du den Quellcode oder neue Features? Erstelle ein [Issue](https://github.com/Fryxz66/LizenzGenerator-ByFryxz66/issues).

## Lizenz
Dieses Programm wird unter einer Endbenutzer-Lizenzvereinbarung (EULA) bereitgestellt. 
Bitte lesen Sie die [LICENSE](LICENSE.md) -Datei für die genauen Nutzungsbedingungen. 
Kurzfassung: 
Sie dürfen das Programm für persönliche Zwecke nutzen, aber nicht verändern, kopieren oder verkaufen.

## Kontakt
Bei Fragen oder Problemen erstelle ein [Issue](https://github.com/Fryxz66/LizenzGenerator-ByFryxz66/issues) oder kontaktiere den Entwickler.

© 2025 Lizenz-Generator powered by Fryxz66
