# SCTECH0077 LIOT 0.0.80

Correzione della rimozione gruppo: ogni lampada arresta ESP-NOW e rilascia la
radio Wi-Fi quando riceve `GROUP:CONFIG:0`. Dopo la conferma il controller
torna immediatamente individuabile nel nuovo onboarding BLE.
