# Dauer eines ausgeschnittenen Teils einer Lieferung

Diese Einschränkung legt das fest **minimale Dauer, die erforderlich ist, um einen Besuch aufzuteilen** in mehrere Abschnitte. Ein Besuch kann über verschiedene Tage oder um eine Mittagspause herum aufgeteilt werden. Dieser Wert steht in engem Zusammenhang mit dem **Besuchsdauer** Einschränkung angegeben ist.

**Format:**  HH:MM

**Beispiel:**

* Besuch A hat eine **Besuchsdauer** von 4 Stunden.
* Besuch B hat eine **Besuchsdauer** von 30 Minuten.
* Die **Dauer eines Abschnitts eines aufgeteilten Besuchs** ist auf 01:00 gesetzt

Das bedeutet, dass **nur Besuche länger als 1 Stunde** aufgeteilt werden können:

* Besuch A kann bei Bedarf in mehrere Abschnitte unterteilt werden.
* Besuch B kann nicht aufgeteilt werden, da er kürzer als die minimale Abschnittsdauer ist.

Die **minimale Dauer für jeden aufgeteilten Abschnitt** wird durch das **Schwellendauer für das Teilen von Besuchen** Einschränkung angegeben ist.

**Zusätzliche Regel:** Ein Besuch **kann nicht in mehr als 16 Blöcke aufgeteilt werden**.

**Abhängig von:**

* Besuchsdauer
* Schwellendauer für das Teilen von Besuchen
