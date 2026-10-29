# SCTECH0077 — Firmware 0.0.36

- Salvataggio distribuito degli scenari personalizzati in SPIFFS su coordinatore e follower.
- La scrittura su flash viene eseguita nel ciclo principale, mai nelle callback BLE o ESP-NOW.
- Ripristino dell'ultimo scenario salvato al riavvio del controller.
