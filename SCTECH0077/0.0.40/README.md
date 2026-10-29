# SCTECH0077 — Firmware 0.0.40

- L'app comunica quanti controller del gruppo devono confermare il salvataggio.
- Il coordinatore conta gli ACK distinti dei follower.
- Se manca una conferma, ritrasmette automaticamente lo scenario fino a tre tentativi.
- L'ACK del follower viene ritardato e ripetuto cinque volte per separarlo dalla raffica dati.
