# AAA-Tester
Version 09.03.2023
Der dem AATiS-Artikel zugehörige Sketch findet sich im Ordner "AAA_Tester_Automatik".

Auf der AATiS-Tagung in Goslar am 10.03.2023 wurde eine Prüfanlage mit einer Lichtschranke vorgeführt.
Der dazuugehörige Sketch findet sich im Ordner "AAA_Tester_Automatik_LightBarrier".

Empfehlungen bzw. Änderungen zum Artikel.
Das im Praxisheft auf Seite 81 Abb.12 dargestellte Schaltbild erfährt folgende Änderung:
Von der Stromversorgung des Arduino über den Vin-Eingang wird abgeraten, da kein Verpolungsschutz besteht.
Ich empfehle den Arduino über ein separates Netzteil an der DC-Buchse zu betreiben.
Hiermit wird die Stromversorgung über die USB-Leitung getrennt.

In jedem Fall sollte das Steckbrett mit den Sensoren und Aktoren eine separate Stromversorgung erfahren.
