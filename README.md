# mittago

Was gibt's heute in Erfurts Kantinen? Alle Speisepläne an einem Ort, mit Suche und Filtern (vegetarisch, Fisch, ohne Schwein …).

**Kantinen:** Casino im Justizzentrum, Sparkasse Kantine, Kantine am Bergstrom, Mensa Altonaer Straße (FH), Mensa Nordhäuser Straße (Uni), Cafeterias Schlüterstraße und Leipziger Straße (FH).

## So funktioniert's

Die Seite ist eine einzelne statische HTML-Datei ohne Build. Sie lädt die Gerichte direkt im Browser aus der Such-API der [Quasiris Search Cloud](https://www.quasiris.de) (SearchApp `mittago`). Die Speisepläne werden werktags morgens eingelesen und dorthin übertragen.

Angaben ohne Gewähr. „vermutlich vegetarisch“ heißt: Im Namen des Gerichts wurde kein Fleisch erkannt. Allergene bitte vor Ort prüfen.

## Lokal ansehen

```bash
python3 -m http.server 8000
# http://localhost:8000
```
