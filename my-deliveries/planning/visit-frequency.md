# Besuchshäufigkeit

Diese Einschränkung legt fest, wie oft ein Besuch innerhalb einer definierten Anzahl von Tagen erfolgen muss. TourSolver optimiert die Planung, indem die Besuche so gleichmäßig wie möglich verteilt werden, wobei alle anderen zutreffenden Einschränkungen berücksichtigt werden.\
Hinweis: Die Frequenz-Einschränkung dient als Planungsleitlinie, garantiert jedoch nicht die genaue Einhaltung der definierten Intervalle. Die TourSolver-Oberfläche zeigt einen Indikator an, der die Anzahl der Besuche darstellt, die die erwartete Frequenz nicht erfüllen.

**Format:** Zeichen 1/5

Wenn diese Einschränkung aktiviert ist, muss auch die **Geleistete Arbeitstage** Einschränkung für die Ressourcen definiert werden.

***

**Beispiele**

**Beispiel 1:**

* **Besuchshäufigkeit = 3/5**\
  Der Kunde muss besucht werden **3 Mal innerhalb von 5 Tagen**.\
  TourSolver versucht, einen **2-tägigen Abstand** zwischen jedem Besuch einzuhalten.

***

**Beispiel 2:**

* **Besuchshäufigkeit = 3/5\***\
  Der Kunde muss besucht werden **3 Mal innerhalb von 5 Tagen**.\
  TourSolver priorisiert die Zuweisung aller 3 Besuche an denselben **Ressource**.\
  In diesem Fall wird die gleichmäßige Verteilung der Besuche nebensächlich.

***

**Beispiel 3:**

* **Besuchshäufigkeit = 1/5**\
  Der Kunde muss besucht werden **einmal alle 5 Tage**.\
  Wenn **Gearbeitete Tage = 1–5**, wird der Kunde besucht:
  * einmal zwischen **Tagen 1–5**
  * einmal zwischen **Tagen 6–10**
  * einmal zwischen **Tagen 11–15**\
    Um einen bestimmten minimalen Abstand zwischen diesen Besuchen sicherzustellen, können Sie die **Mindestabstände zwischen Besuchen** Einschränkung angegeben ist.
