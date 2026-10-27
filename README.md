# Domain-Zuordnung H₂O Portal

Öffentliche Zuordnung der Root-Domain `ffw-wasser.github.io` zur Apple-App `VKL57X3H6F.de.feuerwehrwasser.h2o`.

Die Datei `.well-known/apple-app-site-association` erlaubt der App die Passkey-Anmeldung zur Domain sowie Universal Links für `/home/deckel.html` und `/home/termin.html`. Sie enthält ausschließlich öffentliche Kennungen. Anmeldung und Berechtigungen bleiben durch den bestehenden Server geschützt.

GitHub Pages: Branch `main`, Ordner `/ (root)`. `.nojekyll` stellt die unveränderte Auslieferung des `.well-known`-Ordners sicher. Nach Veröffentlichung müssen HTTPS, HTTP 200 ohne Weiterleitung und der exakte JSON-Inhalt geprüft werden. Geräteabnahme und Apples Zwischenspeicher sind zusätzliche Prüfungen.

Es werden keine Android-Zertifikate veröffentlicht, solange der echte App-Signaturfingerabdruck nicht vorliegt.
