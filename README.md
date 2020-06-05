# sfgz_foyer
Shows Course-Datas on a screen with js clock
Substitutes ~~sfgz_display.~~

----


Zeigt Kursdaten in enem Display

Seit sfgz_kursverwaltung 9.1.08 wurde dieser Teil ausgelagert und mit dieser neuen Extension **sfgz_display** relaisiert.

## Import-Funktionen
Die Kurse werden automatisch angezeigt, die Belegungen müssen erfasst/ausgewählt werden.

*Wenn die Extension **fgz_kurs** nicht installiert ist, müssen alle Einträge als »Belegung« erfolgen.*

### Kurse
Importiert Kurse ab Kursverwaltung Extension **fgz_kurs** (Aktuell)
### Belegungen
Importiert Vorgabe-Belegungen ab 3 möglichen Quellen und kombiniert sie.
- Raumplanung-DB Extension **mffrps** (veraltet)
- Raumplanung-Kalender url raumplanung @sfgz.ch (Aktuell)
- hochgeladener Datei XLSX, CSV... (Zukunft)


## Zeit-Funktionen

### Datenhygiene
Löscht automatisch alle alten Belegungen, das Alter wird in der Extension-Configuration angegeben (Einstellungen / Extension Configuration).

### Permacontent
Wenn eine **Endzeit** angegeben wurde, wird der Text bis zu jenem Datum angezeigt. Er wird an eventuell bestehenenden Text angehängt. Es werden alle Belegung- und Kurseinträge ausgeblendet.


