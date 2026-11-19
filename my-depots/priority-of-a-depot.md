# Priorität eines Depots

Diese Einschränkung ermöglicht es Ihnen, ein Depot im Vergleich zu anderen Standorten zu priorisieren.

* Befinden sich zwei Depots in unmittelbarer Nähe, priorisiert das System den Standort mit dem höheren Prioritätswert.
* Sind die Depots weiter voneinander entfernt, berücksichtigt das System weiterhin den Prioritätswert, bezieht jedoch auch die Entfernung zwischen der Ressource und den Depots mit ein.
* Ein Depot mit einem höheren Wert wird als höher priorisiert betrachtet.

**Format:** Zahl (Ganzzahl)

**Beispiel:**

* Depot A hat einen Prioritätswert von 8 und Depot B einen Prioritätswert von 5.
* Wenn sich beide Depots in der Nähe befinden, besucht das System zuerst Depot A.
* Ist Depot B weiter entfernt, kann das System dennoch Depot A priorisieren, abhängig von der Reisedistanz.
