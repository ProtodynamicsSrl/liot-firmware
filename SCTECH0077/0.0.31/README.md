# SCTECH0077 — Firmware 0.0.31

- Corretto l'invio degli scenari personalizzati: il coordinatore distribuisce ora l'intero frame a tutte le lampade del gruppo.
- La lampada follower aggiorna la catena WS2801 solo dopo aver ricevuto il frame locale completo, evitando frame intermedi e flicker durante i fade.
- Eliminato lo stato residuo che poteva lasciare la lampada secondaria accesa.
