# Gearbeitete Tage 1 bis 10

Diese Einschränkung gibt alle **Gearbeitete Tage** (bis zu 64 Tage) an, an denen die durch die **Arbeitszeit** Einschränkungen definierten Zeitfenster gelten.

\
**Format:** Zeichenwerte.

Gearbeitete Tage können einzeln eingegeben werden (z. B. _1,4_), als ganze Zahlen (_1 bis 64_), oder unter Verwendung von Datumsbereichen (z. B. _14/05/2016 => 17/07/2016_).

**Beispiel 1:**

* _Gearbeitete Tage = 1,2,5_ (oder _14/05/2016, 15/05/2016, 18/05/2016_) bedeutet, dass die Ressource innerhalb der durch die Arbeitszeit-Einschränkungen definierten Zeitfenster an den Tagen 1, 2 und 5 des Planungszeitraums (oder an den entsprechenden Daten) Besuche durchführen kann.
* _Gearbeitete Tage = 1–5_ (oder _14/05/2016 => 18/05/2016_) bedeutet, dass die Ressource innerhalb der definierten Arbeitszeitfenster an allen Tagen 1 bis 5 des Planungszeitraums (oder an allen Daten im Bereich) Besuche durchführen kann.

**Beispiel 2:**\
Eine Ressource arbeitet:

* Montags von 07:00 bis 17:00
* Mittwochs von 09:00 bis 18:00\
  Konfiguration:
* _Arbeitszeit = 07:00–17:00_, _Gearbeitete Tage = 1_
* _Arbeitszeit 2 = 09:00–18:00_, _Gearbeitete Tage 2 = 3_

**Beispiel 3:**\
Eine Ressource arbeitet:

* Montag bis Freitag von 07:00 bis 17:00
* Samstag von 09:00 bis 12:00\
  Konfiguration:
* _Arbeitszeit = 07:00–17:00_, _Gearbeitete Tage = 1–5_
* _Arbeitszeit 2 = 09:00–12:00_, _Gearbeitete Tage 2 = 6_
