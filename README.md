# H₂O Webportal

Der aktive Mitgliederzugang ist die gemeinsame Web-App für iPhone und Android unter `/home/deckel.html`. Das Startsymbol ist optional; die persönliche Anmeldung und der serverseitig freigegebene Mitgliederzugang schützen die Daten.

Für den privaten iPhone-Mitgliederpilot wird die Zuordnung zur bestehenden App `VKL57X3H6F.de.feuerwehrwasser.h2o` vorbereitet. Universal Links gelten ausschließlich für `/home/deckel.html` und `/home/termin.html`; Webcredentials ordnet die vorhandene Web-Anmeldedomain der signierten App zu. Diese Datei enthält keine Zugangsdaten und erteilt keine Mitgliedsrechte. Jeder Portalzugriff bleibt serverseitig geschützt.

Vor Übernahme müssen der echte Mitglieder-Build mit Associated-Domains-Berechtigung und die beiden Apple-Profile geprüft sein. Nach Veröffentlichung den HTTP-200-Abruf ohne Weiterleitung und Apples Domain-Cache sowie Passkey-Anmeldung und Einladungslinks auf dem echten iPhone prüfen. Ein erfolgreicher GitHub-Pages-Build allein bestätigt keine native Anmeldung. Die Demo bleibt auf ihrer eigenen Domain getrennt.

Web-Passkeys, Passwortzugänge und Mitgliederdaten werden dadurch nicht verändert. Root-Seite und HTTPS-Veröffentlichung bleiben bestehen; sie führen zur vorhandenen Anwendung `/home/`. Keine Android-App-Zuordnung veröffentlicht.
