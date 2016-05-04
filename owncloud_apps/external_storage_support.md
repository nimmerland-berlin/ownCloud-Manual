## External Storage Support {#external-storage-support}

Falls der ownCloud Superadministrator das  vorsieht, kannst du den Speicherplatz von externen Anbietern (Dropbox, Google-Drive, Amazon S3, SFTP und andere) in deine nimmerland ownCloud einbinden. So brauchst du nur den ownCloud-Desktop-Client um Daten auf allen deinen Cloudspeichern zu synchronisieren.

Falls du serverseitige Verschlüsselung einsetzt, werden so auch die Dateien in deiner Dropbox verschlüsselt. (Natürlich nur solche Daten, die du über deine nimmerland ownCloud anlegst.) Verschlüsselt sind deine Daten auch auf amerikanischen Servern sicher - die Schlüssel bleiben in deiner Cloud in Berlin.

Weil nur die Trennung von Schlüsseln und Dateien wirklich sicher ist, kannst du seit ownCloud 9 die serverseitige Verschlüsselung auf den externen Speicherplatz beschränken.

Der Superadministrator muss diese App aktivieren und bestimmt, welche Speicherdienste du nutzen kannst. Die App ist standardmäßig nicht aktiviert.

ACHTUNG!!! Für die Transportverschlüsselung zwischen deinem externen Datenspeicher und deiner nimmerland ownCloud bist du selbst verantwortlich. Benutze https/ssl.