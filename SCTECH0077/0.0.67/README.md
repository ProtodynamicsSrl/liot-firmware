# SCTECH0077 — Firmware 0.0.67

La rimozione di tutti gli scenari personalizzati ora cancella in modo
affidabile ogni file SPIFFS: la directory viene riaperta dopo ogni rimozione,
evitando che gli scenari successivi vengano saltati durante la scansione.
