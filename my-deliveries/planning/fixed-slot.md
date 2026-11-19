# Fester Zeitblock

Diese Einschränkung bezeichnet eine **prioritäre Besuch**, wobei die **Ressource, der Tag und die Uhrzeit** des Besuchs festgelegt werden, falls angegeben.

**Format:** Binär

* **0** – Der Besuch ist **nicht festgelegt**.
* **1** – Der Besuch ist **festgelegt** entsprechend den angegebenen Bedingungen.

**Standardwert:** 1

**Abhängig von:**

* Öffnungszeit
* Besuchsdauer

**Beispiel:**

* Ein Besuch wird mit einer Prioritätskennzeichnung von 1, einer Startzeit um 09:00 und einer Dauer von 2 Stunden geplant.
* Das System stellt sicher, dass die zugewiesene Ressource diesen Besuch **genau um 09:00** für 2 Stunden durchführt und dabei die Öffnungszeiten respektiert.
