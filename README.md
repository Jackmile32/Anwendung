# Meine Testanwendung

Eine kleine Webanwendung mit interaktivem Zähler und Status-Endpunkt.
Benötigt Python 3.10 oder neuer; keine externen Pakete oder Zugangsdaten.

## Starten

Im Repository-Verzeichnis:

```sh
python3 app.py
```

Der lokale Server verwendet Port 8000. Ein anderer Port kann mit
`python3 app.py --port 8080` gewählt werden. Mit Strg+C beenden.

## Tests

```sh
python3 -m unittest -v
```

Die Tests prüfen die Startseite, `/health` und unbekannte Routen über einen
echten HTTP-Server auf einem freien lokalen Port.
