# SCTECH0077 — Firmware 0.0.61

Corregge la transizione tra scenari personalizzati in playlist. Le copie di
sicurezza del comando ESP-NOW usano ora la stessa sequenza: la follower ne
applica una sola e non riavvia il fade mentre sta già dissolvendo la scena
precedente. Questo elimina la sovrapposizione e il flicker causati dall'avvio
prematuro dello scenario successivo.
