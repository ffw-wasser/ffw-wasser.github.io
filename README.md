# H₂O Webportal

Der aktive Mitgliederzugang ist die gemeinsame Web-App für iPhone und Android unter `/home/deckel.html`. Das Startsymbol ist optional; die persönliche Anmeldung und der serverseitig freigegebene Mitgliederzugang schützen die Daten.

Die native iPhone-App wird seit 27.10.2026 nicht weitergeführt. Die leeren Einträge in `.well-known/apple-app-site-association` nehmen die frühere Zuordnung für Universal Links und native Passkey-Anmeldung zurück. Bereits zwischengespeicherte Zuordnungen können bis zu Apples bzw. dem Geräte-Refresh weiterwirken. Noch installierte TestFlight-Apps können vom jeweiligen Nutzer entfernt werden.

Web-Passkeys, Passwortzugänge und Mitgliederdaten werden dadurch nicht verändert. Root-Seite und HTTPS-Veröffentlichung bleiben bestehen; sie führen zur vorhandenen Anwendung `/home/`. Keine Android-App-Zuordnung veröffentlicht.
