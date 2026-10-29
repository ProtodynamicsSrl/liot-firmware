# SCTECH0077 — Firmware 0.0.35

- Ogni controller salva fino a 8 scenari personalizzati nella propria partizione SPIFFS.
- Il coordinatore replica il salvataggio completo alle follower con ESP-NOW; non serve mantenere l'app aperta per conservare lo scenario.
- Al riavvio viene ripristinato l'ultimo scenario salvato e attivo.
- La partizione SPIFFS esistente offre circa 832 KB: circa 4 KB per scenario, oltre 200 scenari teorici; l'app espone per ora 8 slot sicuri.
