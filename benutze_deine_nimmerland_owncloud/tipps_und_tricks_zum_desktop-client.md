## **Tipps und Tricks zum Desktop-Client** {#tipps-und-tricks-zum-desktop-client}

### **Datei- und Ordnernamen** {#datei-und-ordnernamen}

Ein leidiges Thema: Cloud-Dateien liegen auf unterschiedlichen Rechnern oder mobilen Geräten mit unterschiedlichen Betriebs- und Dateisystemen. Nicht alle halten sich an den globalen Standard UTF-8. Es mag alles glattgehen, besser ist: Keine Leerzeichen, Sonderzeichen oder Umlaute in Datei- und Ordnernamen.

### **Löschen großer Datenmengen** {#l-schen-gro-er-datenmengen}

ownCloud Server löscht Dateien nicht, sondern kopiert sie in einen Papierkorb, damit du sie bei Bedarf wieder herstellen kannst. (Siehe Geduld)

### **Synchronisation mehrerer Geräte** {#synchronisation-mehrerer-ger-te}

Läuft problemlos, wenn die Uhren in etwa gleich gestellt sind. Nach der Erstinstallation aber, solltest du erst ein Gerät und dann streng nacheinander alle weiteren Geräte synchronisieren. Es kann sonst vorkommen, das die Clients gegeneinander arbeiten und gerade hoch geladene Dateien wieder verschwinden.

### **Geduld** {#geduld}

Du kannst flüssig mit deinen Daten arbeiten. Die Synchronisation über das Netz brauch aber Zeit. Gerade bei großen Dateien. Erwarte nicht, dass eine Änderung, die du gerade gemacht hast, sofort bei deinen Kollegen angezeigt wird.

### **Synchronisationsfehler** {#synchronisationsfehler}

Können unterschiedliche Ursachen haben. Oft ist eine instabile oder schwache Internetverbindung schuld, gerade wenn sehr große Dateien synchronisiert werden sollen. Damit zumindest die kleineren Dateien aktualisiert werden, blacklistet der Client Files mit mehr als drei gescheiterten Synchronisationsversuchen: Er schließt sie von der zukünftigen Synchronisation aus. Der Activity-Report deines Clients zeigt eine Fehlermeldung.

![](nila-oc8-friends-ersteinrichtung-Dateien/img00034.PNG) 

Um eine ausgeschlosse Datei wieder zu synchronisieren, aktivierst du sie und klickst 'Synchronisation wiederholen.

![](nila-oc8-friends-ersteinrichtung-Dateien/img00035.PNG) 

Vielleicht siehst du einmal die Meldung 'Datei wurde nicht synchronisiert, weil sie auf der Ignorierliste geführt ist'. Hierbei handelt es sich meist um versteckte, oder Systemdateien, die nicht synchronisiert werden sollen.