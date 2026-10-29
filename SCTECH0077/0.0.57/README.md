# SCTECH0077 — Firmware 0.0.57

- La playlist viene sospesa, senza essere cancellata, quando si seleziona
  lo scenario Statico; torna operativa solo dopo il ritorno a Dinamico.
- I cursori Statico usano una transizione locale continua e ravvicinata,
  anziché applicare salti di luminosità.
- Quando tutti i canali sono a zero il firmware trasmette due frame WS2801
  completamente nulli per consolidare lo spegnimento della catena LED.
