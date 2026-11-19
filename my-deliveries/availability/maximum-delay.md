# Maximale Verspätung

Diese Einschränkung ermöglicht es Ihnen, die **maximal zulässige Verspätung** über das Ende des Zeitfensters eines Besuchs hinaus.

Die **Verspätungsstrafe** Einschränkung muss gleichzeitig verwendet werden.

**Format:** HH:MM oder HH:MM:SS

**Abhängig von:**

* Öffnungszeit
* Schließzeit
* Strafe pro verspäteter Stunde

**Unvereinbar mit:**

* Verspätungstoleranz

**Beispiel**

Wenn das Zeitfenster eines Kunden um **17:00** und die **Maximale Verspätung** auf **00:10**, darf die Ressource bis zu **10 Minuten verspätet**, das heißt, nicht später als **17:10**.

Jede Ankunft nach **17:10** wird nicht akzeptiert, und Verzögerungen innerhalb dieses Limits werden gemäß der **Strafe pro verspäteter Stunde** Einschränkung angegeben ist.
