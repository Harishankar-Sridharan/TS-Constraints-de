# Öffnungs-/Schließzeiten 1 bis 10

### Öffnungs-/Schließzeiten

Diese Einschränkungen ermöglichen es Ihnen, das Zeitfenster anzugeben, während dessen ein Besuch stattfinden kann.\
**Öffnungszeit 1** gibt die früheste Zeit an, zu der der Besuch beginnen kann, und **Schließzeit 1** gibt an, zu welcher spätesten Zeit er beginnen kann. Dieses Zeitfenster gilt für alle Tage, sofern nicht **Öffnungstage 1** definiert sind; in diesem Fall gilt das Zeitfenster nur für die angegebenen Tage.

Wenn kein Zeitfenster für einen Besuch definiert ist, kann er jederzeit an den erlaubten Öffnungstagen und innerhalb der Arbeitszeiten der Ressource durchgeführt werden. Sie können bis zu vier verschiedene Zeitfenster (jeweils mit den zugehörigen Tagen) für einen einzelnen Besuch konfigurieren.

**Format:** HH:MM:SS

**Beispiel 1:**\
Öffnungszeit 1 = 07:30:00 und Schließzeit 1 = 11:30:00 erzeugen ein vierstündiges Zeitfenster, während dessen der Kunde besucht werden kann.

**Beispiel 2:**\
Für einen Kunden, der eine Lieferung zwischen 23:00 Uhr und 03:00 Uhr benötigt, müssen die Zeiten so verschoben werden, dass sie innerhalb desselben Tages liegen. Dadurch kann die Reihenfolge der Besuche korrekt ermittelt werden.\
Zum Beispiel:\
Öffnungszeit 1 = 19:00:00 und Schließzeit 1 = 23:00:00 definieren ein vierstündiges Fenster.\
Nach der Optimierung müssen die geplanten Besuchszeiten wieder in den ursprünglichen Zeitraum zurückverschoben werden.\
Wenn TourSolver den Besuch um 21:00 Uhr einplant, findet der tatsächliche Besuch um 01:00 Uhr statt (= 23:00:00 + 2 Stunden).

Zeitfenster, die sich über mehrere Tage erstrecken, werden nicht unterstützt. Beispielsweise kann ein Zeitfenster von 23:00:00 bis 03:00:00 nicht verwendet werden, ohne die Zeiten anzupassen.

Ein Besuch kann nicht vor der Öffnungszeit beginnen. Standardmäßig darf ein Besuch, der innerhalb des Zeitfensters beginnt, über die Schließzeit hinaus andauern. Wenn der Besuch vor der Schließzeit enden soll, aktivieren Sie die **Option Besuch vor Schließzeit beenden** Option.

### Öffnungs-/Schließzeiten 2 bis 10

**Öffnungs- und Schließzeiten 2**

Diese Einschränkungen erlauben es Ihnen, ein zweites Zeitfenster zu definieren, das für die in **Mögliche Besuchstage 2**.\
**Öffnungszeit 2** die früheste Zeit angibt, zu der ein Besuch beginnen kann, während **Schließzeit 2** die späteste Zeit angibt, zu der er beginnen kann.

**Format:** HH:MM:SS

**Beispiel 1:**\
Ein Kunde ist für die Lieferung während zweier separater Zeiträume verfügbar:

* Morgen: 09:00 bis 12:00 Uhr
* Nachmittag: 14:00 bis 17:00 Uhr

**Um dies zu konfigurieren, setzen Sie**:

* Öffnungszeit 1 = 09:00:00
* Schließzeit 1 = 12:00:00
* Öffnungszeit 2 = 14:00:00
* Schließzeit 2 = 17:00:00

**Beispiel 2:**\
Ein Kunde kann an folgenden Tagen besucht werden:

* Montag von 07:00 bis 17:00 Uhr
* Mittwoch von 09:00 bis 18:00 Uhr

**Die Konfiguration wäre:**

* Öffnungszeit 1 = 07:00:00
* Schließzeit 1 = 17:00:00
* Öffnungstage 1 = 1 (Montag)
* Öffnungszeit 2 = 09:00:00
* Schließzeit 2 = 18:00:00
* Öffnungstage 2 = 3 (Mittwoch)

**Öffnungs- und Schließzeiten 3**

Diese Einschränkungen erlauben es Ihnen, ein drittes Zeitfenster festzulegen, das für die in **Mögliche Besuchstage 3**.\
**Öffnungszeit 3** angibt, wann der Besuch beginnen kann, und **Schließzeit 3** gibt die späteste Zeit an, zu der der Besuch beginnen kann.

**Format:** HH:MM:SS

**Öffnungs- und Schließzeiten 4**

Diese Einschränkungen erlauben es Ihnen, einen zweiten Zeitabschnitt zu definieren, der für die unter\
Mögliche Besuchstage 4 definierten Besuchstage gilt. Öffnungszeit 4 entspricht der Zeit, ab der der Besuch durchgeführt werden kann.\
Schließzeit 4 entspricht der Zeit, nach der der Besuch nicht mehr durchgeführt werden kann.
