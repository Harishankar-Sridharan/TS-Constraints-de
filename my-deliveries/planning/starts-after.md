# Beginnt nach

Diese Einschränkung erlaubt es Ihnen, **Besuche zu verketten**, wodurch sichergestellt wird, dass zwei Besuche am **gleichen Tag vom gleichen Fahrer durchgeführt werden**.

Der Besuch, auf den diese Einschränkung angewendet wird, wird geplant **nach dem Besuch, mit dem er verknüpft ist**. Wenn irgendein Besuch in der Kette nicht geplant werden kann, **wird keiner der Besuche in der Kette platziert**.

Falls verwendet, sollte der Wert der **Kunden-ID** des Besuchs entsprechen, mit dem verknüpft werden soll.

**Format:** Ganzzahl (entsprechend der Kunden-ID)

**Beispiel:**

* Besuch A hat die Kunden-ID 101
* Besuch B hat diese Einschränkung auf 101 gesetzt

In diesem Fall wird Besuch B geplant **nach Besuch A am selben Tag vom gleichen Fahrer**.

**Abhängig von:** Kunden-ID\
**Unvereinbar mit:** Besuchshäufigkeit
