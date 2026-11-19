# Typ

Diese Einschränkung gibt an, ob ein Besuch ein **Zustellung/Abgabe** oder ein **Rückgabe/Abholung**.

**Format:** Binär

* **0** – Die Route befindet sich im **Zustellmodus**.
* **1** – Die Route befindet sich im **Abholmodus**.
* **2** – Die Route befindet sich im **Zustellmodus**, der abgeschlossen sein muss **bevor irgendwelche Abholungen** stattfinden können.

**Abhängig von:** Menge

**Beispiel:**\
Wenn ein Ressourcen zuerst Artikel zustellen muss, bevor sie Rücksendungen einsammelt, setzen Sie den Wert auf `2`.\
Wenn der Besuch nur eine Abholung beinhaltet, setzen Sie den Wert auf `1`.
