# Alle Fähigkeiten müssen kompatibel sein

Wenn die **Kompatibilität mit den Ressourcen** Einschränkung angewendet wird (insbesondere bei mehreren Werten), ermöglicht diese Einstellung festzulegen, ob **nur eine** Eigenschaft aus der Liste ausreicht oder ob **alle** aufgeführten Eigenschaften erforderlich sind.

**Format:** Binär

* **0** – Nur eine Eigenschaft aus der Liste ist erforderlich.
* **1** – Alle Eigenschaften in der Liste sind erforderlich.

**Standardwert:** 1

**Beispiel:**\
Wenn ein Besuch von einer Ressource durchgeführt werden kann, die **irgendeine** der aufgelisteten Eigenschaften erfüllt, setzen Sie den Wert auf `0`.\
Wenn der Besuch erfordert, dass eine Ressource **alle** Eigenschaften in der Liste erfüllt, lassen Sie den Wert auf `1`
