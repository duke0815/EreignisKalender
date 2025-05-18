# Ereigniskalender

## Projekt unterstützen
Wenn dir **Ereigniskalender** eine Hilfe ist, freue ich mich über eine kleine Spende.

[![Buy me a coffee](https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png)](https://buymeacoffee.com/duke0815)

**Neu in Version 0.6 (Mai 2025)** 

- **Live-Filter** im Verwaltungsfenster (Suche nach Name/Kommentar)  
- **CSV-Export** über „Weitere Funktionen → Daten exportieren“  
- **CSV-Import & Merge** (Duplikat-Check per Name + Datum)  
- **„Weitere Funktionen“-Menü** (Import, Export, Ordner öffnen, App-Info)  
- **Warnung bei ungespeicherten Änderungen** beim Schließen  
- **Dirty-Flag** (bearbeitete Zeilen bis zum Speichern gelb markiert)  

**Version 0.5 (Mai 2025)**  
Eine schlanke Desktop-Anwendung zum Verwalten von Geburtstagen, Jubiläen und anderen jährlich wiederkehrenden Ereignissen.

![grafik](https://github.com/user-attachments/assets/18fbf90a-0af6-4b89-90db-0173b98fb437)

![grafik](https://github.com/user-attachments/assets/51f48b91-dcf0-456c-89aa-ec9857151554)


## Funktionen

- Anzeige aller bevorstehenden Ereignisse der nächsten drei Monate  
- Hinzufügen, Bearbeiten oder Löschen beliebiger Ereignisse (Geburtstage, Hochzeitsjubiläen, Meilensteine…)  
- Anzeige des aktuellen Alters sowie der verbleibenden Tage bis zum Ereignis  
- Sortierung nach Name, Datum, Alter oder verbleibenden Tagen  

## Installation

1. Lade den aktuellen Windows-Build herunter.  
2. Speichere die Dateien in einen Ordner deiner Wahl.  
3. Doppelklicke auf **Ereigniskalender.exe**, um die Anwendung zu starten.

## Nutzung

- **Hauptfenster**: Zeigt alle Ereignisse innerhalb der nächsten 3 Monate.  
- **Verwaltungsfenster**: Klicke auf **Alle Einträge**, um Ereignisse und Kommentare hinzuzufügen, zu bearbeiten oder zu löschen.  
- Änderungen werden automatisch in der Datei `birthdays.csv` im gleichen Verzeichnis wie die EXE gespeichert.

## Roadmap

- **ICS-Export**  
  – Termine als iCalendar-Datei (.ics) exportieren, importierbar in Outlook/Google Calendar  
- **Automatisches Backup**  
  – Vor jedem Speichern automatische Sicherung von `birthdays.csv` im Unterordner `Backup\`  
- **Statusleiste**  
  – Zeigt Gesamtanzahl Einträge und nächstes bevorstehendes Event  
- **Tray-Icon & Minimieren**  
  – App läuft im Systray, erinnert per Toast
- **Autostart-Option**  
  – Eintrag in `HKCU\…\Run` per Klick aktivieren/deaktivieren  
- **Filter erweitern**  

*ToDos können sich je nach Nutzerfeedback und Aufwand anpassen.* 

