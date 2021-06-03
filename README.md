# iCalender_ics

Zum erstellen einer iCalander datei.ics für import in Kalenderprogramm
( System: Debian buster - LANG=de_DE.UTF-8 )

<code>
$ chmod +x create_termin_ics
  
$ ./create_termin_ics -h 
</code>

### Hinweis

Beim verwenden einer Import Datei sollte diese nach dem Format für
Google Kalender formatiert sein.

Beispiel: Beispiel_Google_Kalender_import.csv


 * Felder: Subject,Start Date,End Date,Start Time,End Time,Location,Description

 * Description: bei Bedarf als TEXT Feld setzen "..." 
             Zeilenumbruch im Text mit "\n" einfügen

 * Ganztagestermin: Felder "End Date,Start Time,End Time" können leer sein



  * Format: bei Termineingabe
    * Datum:   Jahr Monat Tag : YYYYmmdd
    * Zeit:    Stunde Minute  : HHMM

