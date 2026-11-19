# Datum des letzten Besuchs

Diese Einschränkung gibt an **wie viele Tage zuvor der letzte Besuch stattgefunden hat** bevor die aktuelle Planung beginnt, um sicherzustellen, dass der Mindestabstand zwischen Besuchen eingehalten wird.

**Format:** Negative ganze Zahl

**Hinweis:** Wenn die Besuchsfrequenz mehr als eine Wiederholung hat, wird diese Einschränkung **nicht angewendet**.

**Beispiel:**

* **Besuchsfrequenz:** 1/5
* **Mindestabstand zwischen Besuchen:** 2 Tage
* **Datum des letzten Besuchs:** -1

In diesem Fall wird der Kunde ab besucht **Tag 2**, weil ein Besuch an Tag 1 den Mindestabstand von 2 Tagen zwischen Besuchen verletzen würde.

**Abhängig von:**

* Besuchshäufigkeit
* Mindestabstände zwischen Besuchen
