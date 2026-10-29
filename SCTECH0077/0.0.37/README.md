# SCTECH0077 — Firmware 0.0.37

- Conferma esplicita del salvataggio di uno scenario personalizzato sul coordinatore.
- Conferma di ritorno dal follower al coordinatore via ESP-NOW, quindi l'app può mostrare quanti controller hanno scritto lo scenario.
- Scrittura SPIFFS mantenuta fuori dalle callback radio per non interrompere la ricezione ESP-NOW.
