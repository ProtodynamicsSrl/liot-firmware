# PRDYELE0048 · LIOT · firmware 0.0.2

Aggiornamento OTA per controller PRDYELE0048 con ESP32-D0WDR2-V3 e flash da
8 MB. Mantiene il protocollo BLE dell'app LIOT e abilita aggiornamento sicuro
via hotspot Wi-Fi, con trasferimento BLE come fallback.

Il binario usa 1.617.136 byte: rientra nello slot OTA di 2.097.152 byte.
L'aggiornamento conserva la configurazione dell'utente in NVS e le scene in
SPIFFS. Le uscite seguono il cablaggio PRDYELE0047: `R, B, G, W, NC, NC`; il
GPIO 25 abilita la 24 V della scheda LED.

L'app verifica dimensione e SHA-256 dichiarati in `../latest.json` prima del
trasferimento. Pubblicare binario e manifest nel repository `liot-firmware`
prima di proporre l'aggiornamento agli utenti.
