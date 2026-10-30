# SCTECH0077 — Firmware 0.0.69

Ogni salvataggio di scenario registra il relativo ID in un indice persistente
del controller. La memoria e l'elenco nell'app leggono quindi gli scenari
effettivamente scritti in SPIFFS, senza dipendere dalla scansione della
directory.
