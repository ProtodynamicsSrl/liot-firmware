# SCTECH0077 — Firmware 0.0.39

- Trasferimento di salvataggio ridondante: due copie complete dello scenario al follower.
- Checksum della scena: il follower non salva e non conferma una copia incompleta.
- Clock di fase dal coordinatore ogni 40 ms: i passaggi animati restano allineati fra coordinatore e follower.
