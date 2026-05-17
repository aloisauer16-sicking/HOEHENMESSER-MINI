# HOEHENMESSER-MINI
hoehenmesser_mini

Altimeter Web App Variante nur Große Anzeige absolute Höhe über gesamte Bildschirmbreite, die man dann als verkleinertes Fenster über oder mit anderer App anzeigen kann.09:47Claude hat geantwortet: Klare Anforderung: maximale Höhenanzeige, ganzer Bildschirm, für Picture-in-Picture / verkleinertes Fenster.Check frontend-design skillCheck frontend-design skillKlare Anforderung: maximale Höhenanzeige, ganzer Bildschirm, für Picture-in-Picture / verkleinertes Fenster. Ich baue das als eigenständige minimalistische App — große Ziffer, nichts Überflüssiges.Datei erstellt, datei lesenDatei erstellt, datei lesenDie Datei ist bereit. Design-Entscheidungen:

Riesige Ziffer füllt die gesamte Bildschirmbreite (fluid, skaliert automatisch)
Militärisch-instrumentales Look — schwarz, Phosphorgrün, Monospace-Details, Scanline-Textur
Minimalinformation — nur Höhe, Trendpfeil (↑↓—), GPS-Status, Genauigkeit, Min/Max
Screen Wake Lock — Bildschirm bleibt an (kein Auto-Sleep)
Lang drücken → Reset / Neustart GPS

Als verkleinertes Fenster über Google Maps nutzen:
Auf Android gibt es dafür zwei Wege:

Chrome Custom Tab / Split Screen — App in Chrome öffnen, dann Android-Splitscreen aktivieren (zwei Apps nebeneinander oder übereinander)
Floating Browser App — z.B. Floating Apps Free oder Overlays aus dem Play Store: dort die URL der GitHub Pages laden → erscheint als frei verschiebbares, skalierbares Fenster über jeder anderen App — genau wie ein PiP-Fenster
