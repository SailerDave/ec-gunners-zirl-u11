EC Gunners Zirl U10/U11 – Version 6.0

UPLOAD AUF GITHUB
1. ZIP lokal entpacken.
2. Im GitHub-Repository den Branch öffnen, den Cloudflare verwendet (meist main).
3. Die vorhandene index.html durch die neue index.html ersetzen.
4. Die Ordner bilder/ UND logos/ vollständig hochladen. Beide Ordner müssen direkt neben index.html liegen.
5. Commit changes anklicken.
6. Warten, bis Cloudflare den neuen Commit deployed hat.
7. Homepage anschließend mit Strg+F5 (Windows) bzw. Cmd+Shift+R (Mac) neu laden.

RICHTIGE STRUKTUR
index.html
bilder/
  ...Spielerbilder...
logos/
  gunners.png
  telfs.png
  silz.jpg
  ehrwald.png
  fuessen.png
  imst.jpg
  peiting.png
  riessersee.png
  riverkings.png
  ...weitere vorhandene Platzhalter...

IN V6.0 EINGEBAUTE VEREINSABZEICHEN
- EC Gunners Zirl: Gunners.png
- EC Telfs / Kuppelarena Telfs: Telfs.png
- Silz Bulls: Silz.jpg
- EC Ehrwald: Ehrwald.png
- EV Füssen: Füssen.png
- IEC Scorpions Imst: Imst.jpg
- EC Peiting / kombinierte Peiting-Schongau-Termine: Peiting.png
- SC Riessersee / kombinierte Peißenberg-Riessersee-Termine: Riessersee.png
- HC Landsberg Riverkings: Riverkings.png

Für Vereine, für die noch kein offizielles Logo hochgeladen wurde (z.B. Götzens und Montafon), bleibt vorerst das vorhandene lokale Ersatzabzeichen bestehen.


V6.1: Logos werden ausschließlich relativ aus dem Ordner logos/ geladen. In den Spielkarten steht das Logo oben und der Vereinsname direkt darunter. Beim lokalen Test muss der Ordner logos direkt neben index.html liegen.


V6.5: Bei Auswahl U10 werden die Liga-Buttons Bayernliga und Phase II ausgeblendet. Reguläre U10-Spiele sind als Landesliga eingeordnet; Turniere bleiben unter Turnier.


V6.6: U10/U11 Landesliga-Termine werden als Turnierkarten dargestellt: Veranstalter oben, darunter die bekannten teilnehmenden Mannschaften mit Logo und Namen. HCI Team Rot Logo: logos/hci_team_rot.png.


V7.0: Die Logos der Landesliga-Vereine sind anklickbar und führen zur jeweiligen Vereins-Homepage. Die Links öffnen in einem neuen Tab.

V7.1: Veranstalter-Logo und Vereinsname wieder untereinander; Seitentitel auf „Parents-Page der Zirler U11“ geändert.

V7.2
----
- Bei U11-Landesliga steht der Veranstalter wieder sauber untereinander:
  VERANSTALTER → Logo → Vereinsname. Die Logo-Verlinkung bleibt erhalten.
- Die Spielfilter sind auf Desktop dauerhaft links am Bildschirm fixiert und
  können auch nach langem Scrollen jederzeit geändert werden.
- Auf kleineren Displays bleibt der Filter als Sticky-Leiste oben erreichbar.

V8.1 – stabile Basis V7.2
-------------------------
Diese Version wurde erneut direkt aus V7.2 erstellt.
Keine der mobilen Filter-Experimente aus V7.3 bis V8.0 wurde übernommen.

Filterkorrekturen:
- Phase 2 als eigener Filter entfernt.
- Bei U10 wird Bayernliga ausgeblendet.
- Wechselt man von Bayernliga auf U10, springt der Liga-Filter automatisch auf Alle.
- U10 Landesliga/Turnier bleiben verfügbar.
- Desktop- und Mobile-Layout entsprechen ansonsten V7.2.

V8.2: Im aufgeklappten U11-Kader stehen nun oberhalb der Spieler mittig die Trainerporträts Clemens und Hannes. Dateien: bilder/Trainer_Clemens.png und bilder/Trainer_Hannes.png.

V8.3
----
Nur mobile Kaderkorrektur gegenüber V8.2:
- Trainer Clemens und Hannes werden im U11-Kader auf Mobilgeräten explizit sichtbar gehalten.
- Beide Porträts stehen nebeneinander und skalieren auf die verfügbare Bildschirmbreite.
- Keine Änderungen an Spielen, Filtern oder Desktop-Layout.

V8.4
----
Im U11-Kader wurde Markus als dritter Trainer neben Clemens und Hannes ergänzt.
Bilddatei: bilder/Trainer_Markus.png
Desktop und Mobil: alle drei Trainer werden mittig in einer Reihe dargestellt.
\nV9.1: ASKÖ 24.10.2026 09:00 als nächster Termin; U11 Freundschaftsturnier Kundl 10.10.2026 mit Kundl/Wattens-Logos; Schalter abgeschlossene Spiele im Desktop- und Mobilfilter.\n