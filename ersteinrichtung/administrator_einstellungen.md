<div class="alert alert-info">
Der folgende Abschnitt gilt für <strong>nimmerland ownCloud friends & family | team</strong>
</div>

## Superadministrator Einstellungen

Die Liste deiner Einstellmöglichkeiten hängt von deinen aktivierten ownCloud Apps ab. In den meisten Fällen sind sie selbsterklärend. Falls nicht, schau in die Hilfe oder frag unseren Support.

![](nila-oc8-friends-ersteinrichtung-Dateien/img00017.PNG)

### Dokumente

Die MS Word Unterstützung ist in der nimmerland ownCloud team aktiviert.

### Serverseitige Verschlüsselung

Bei serverseitiger ownCloud-Verschlüsselung raten wir dir dringend, in deinen Administratoreinstellungen ein Wiederherstellungspasswort zu setzen. Diesen Eintrag findest du nach erneutem Login in deinen Superadmin-Einstellungen.

### Federated-Cloud-Sharing

Gibt es seit ownCloud 7\. Es ermöglicht, Dateien auf unterschiedlichen ownCloud-Servern zu teilen. In Deutschland bauen einige große Universitäten gerade ein solches Netz aus ownCoud-Servern auf. Wahrscheinlich wirst du diese Funktion nicht benutzen, aber du könntest es. z. B. wenn Freunde von dir ebenfalls eine nimmerland ownCloud benutzen.

### Teilen

Hier konfigurierst Du die Möglichkeiten und Einschränkungen des Teilens für deine Benutzer. Weitere Informationen hierzu findest du in der Hilfe.

**Ein paar Einstellungen haben wir optimiert und raten dir, sie nicht zu ändern:**

### E-Mail-Server

Die Benachrichtigungsmails werden von einem php-Script mit dem Absender noreply@nimmerland.de  versendet. **Du darfst diese Adresse nicht ändern**.

### Sicherheit

Die Transportverschlüsselung ist auf HTTPS erzwingen voreingestellt, sodass deine Daten auf dem Weg durch das Netz immer verschlüsselt sind.

### Cron

Bestimmte Aktionen muss deine ownCloud-Installation regelmäßig im Hintergrund ausführen. Wir haben einen Webcron installiert, der diese Aktionen alle 15 Minuten anstößt.

Info: Wenn du diese Einstellung änderst, werden einige Hintergrundaufgaben nicht mehr ordnungsgemäß funktionieren.