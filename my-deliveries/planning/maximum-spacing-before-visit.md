# Maximaler Abstand bis zum Besuch

Diese Einschränkung definiert das **maximal zulässige Zeitlücke** zwischen zwei verketteten Besuchen.

**Format:** HH:MM

**Technischer Feldname:** `tsOrderBeforeMaxTimeSpacing`

**Abhängig von:** Beginnt nach

**Beispiel:**

* Besuch A und Besuch B sind verkettet.
* Maximale Zeitspanne zwischen ihnen ist festgelegt auf `01:30:00`.

In diesem Fall, **muss Besuch B innerhalb von 1 Stunde 30 Minuten nach Besuch A beginnen**; andernfalls kann die Verkettung nicht geplant werden.
