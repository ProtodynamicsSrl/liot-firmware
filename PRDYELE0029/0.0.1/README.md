# PRDYELE0029 · LIOT BLE · firmware 0.0.1

Pacchetto di prova per l'aggiornamento OTA via Bluetooth Low Energy.

LIOT scarica il file binario solo se il modello e il checksum SHA-256 dichiarati
in `../latest.json` corrispondono. Il controller deve essere stato prima
inizializzato via USB con il firmware `0.0.0` dotato di supporto OTA.
