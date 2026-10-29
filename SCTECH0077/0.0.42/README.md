# SCTECH0077 — Firmware 0.0.42

- Il follower riceve gli scenari personalizzati in un buffer separato e sostituisce la scena attiva solo dopo checksum e commit validi: elimina il flicker iniziale causato da dati parziali.
- Nuovo comando `SCENE_MEM`: riporta spazio SPIFFS libero/totale e slot scenari occupati per la pagina Generale dell'app.
