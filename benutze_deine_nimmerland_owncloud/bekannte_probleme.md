## **Bekannte Probleme** {#bekannte-probleme}

### **Umbenennen größerer Ordnerstukturen** {#umbenennen-gr-erer-ordnerstukturen}

Der alte Ordnername ist für die Cloud gelöscht. Daher werden ggf. Unmengen Daten in den internen Papierkorb verschoben. Was Zeit braucht. Zeitgleich wird der umbenannte Ordner neu hochgeladen. Auf anderen synchronisierenden Clients wird eine wahre Löschorgie in Gang gesetzt und man meint, die Dateien würden von der Cloud gelöscht. (Panik macht sich breit).

Zwar ist – wenn man nicht eingreift – nach ein paar Stunden wieder alles OK, besser vermeiden oder über das Web-Interface umbenennen.

### **Umlaute, Sonderzeichen in Datei/Ordnernamen (Mac)** {#umlaute-sonderzeichen-in-datei-ordnernamen-mac}

ownCloud benutzt den UTF-8 Standard, um mit allen möglichen Zeichensätzen konsistent umgehen zu können. Einige MAC-User berichten über das Verschwinden von Dateien beim Umbenennen, wenn diese Umlaute enthalten. Möglicherweise ist auf diesen Mac-Systemen der UTF-8 Zeichensatz nicht als Standard gesetzt. Die Dateien sind dann im Papierkorb zu finden.

### **Groß- und Kleinschreibung** {#gro-und-kleinschreibung}

Linux-Rechner und damit die Server des Internet, unterscheiden Groß- und Kleinschreibung. Bild01.JPG und bild01.JPG sind für die Serversoftwäre unterschiedliche Dateien. Windows und MacOs können oder wollen hier nicht unterscheiden. Wenn Benutzer Dateien gleichen Namens aber unterschiedlicher Kleinschreibung in einem geteilten Ordner anlegen, geht das für die ownCloud in Ordnung, führt aber beim Versuch der Synchronisation zu einer Fehlermeldung (es droht tatsächlich Datenverlust). Dasselbe gilt für die Groß- und Kleinschreibung von Ordnern.