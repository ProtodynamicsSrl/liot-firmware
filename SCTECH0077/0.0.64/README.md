# SCTECH0077 — Firmware 0.0.64

Spegnendo la lampada, il fade porta a zero solo i LED: il driver stepper resta
alimentato e il motore conserva la coppia di mantenimento. La correzione copre
anche i 320 ms della dissolvenza, durante i quali nelle versioni precedenti il
driver poteva essere brevemente disabilitato.
