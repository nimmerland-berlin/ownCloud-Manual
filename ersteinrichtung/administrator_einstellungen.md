## **Administrator Einstellungen** {#administrator-einstellungen}

Die Liste deiner Einstellmöglichkeiten hängt von deinen aktivierten ownCloud Apps ab. In den meisten Fällen sind sie selbsterklärend. Falls nicht, schau in die Hilfe oder frag unseren Support.

![](nila-oc8-friends-ersteinrichtung-Dateien/img00017.PNG)

### **Dokumente** {#dokumente}

Die MS Word Unterstützung ist auf unseren Servern deaktiviert.

### **Serverseitige Verschlüsselung** {#serverseitige-verschl-sselung}

Bei serverseitiger ownCloud-Verschlüsselung raten wir dir dringend, in deinen Administratoreinstellungen ein Wiederherstellungspasswort zu setzen. Diesen Eintrag findest du nach erneutem Log-in in deinen Einstellungen.

### **Federated-Cloud-Sharing** {#federated-cloud-sharing}

Gibt es seit ownCloud 7\. Es ermöglicht, Dateien auf unterschiedlichen ownCloud-Servern zu teilen. In Deutschland bauen einige große Universitäten gerade ein solches Netz aus ownCoud-Servern auf. Wahrscheinlich wirst du diese Funktion nicht benutzen, aber du könntest es. z. B. wenn Freunde von dir ebenfalls eine nimmerland ownCloud benutzen.

### **Mailvorlagen** {#mailvorlagen}

ownCloud bringt für alle Benachrichtigungsmails englische Vorlagen mit. Nur wenn du dich mit HTML und PHP auskennst, kannst Du hier eine Vorlage ändern. Du musst das aber nicht tun.

### **Teilen** {#teilen}

Hier konfigurierst Du die Möglichkeiten und Einschränkungen für das Teilen für deine Benutzer. Weitere Informationen hierzu findest du in der Hilfe.

### **E-Mail-Server** {#e-mail-server}

Die Benachrichtigungsmails werden von einem php-Script versendet. Du kannst die Absenderadresse ändern, wenn du die Mitglieder deiner Cloud persönlich ansprechen möchtest.

**Ein paar Einstellungen haben wir optimiert und raten dir, sie nicht zu ändern:**

### **Sicherheit** {#sicherheit}

Die Transportverschlüsselung ist auf HTTPS erzwingen voreingestellt, sodass deine Daten auf dem Weg durch das Netz immer verschlüsselt sind.

### **Cron** {#cron}

Bestimmte Aktionen muss deine ownCloud-Installation regelmäßig im Hintergrund ausführen. Wir haben einen Webcron installiert, der diese Aktionen alle 15 Minuten anstößt.

Info: Wenn du diese Einstellung änderst, werden einige Hintergrundaufgaben nicht mehr ordnungsgemäß funktionieren.