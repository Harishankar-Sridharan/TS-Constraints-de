# Öffnungstage 1 bis 10

**Öffnungstage 1**

Diese Einschränkung listet alle möglichen Besuchstage (bis zu 64) auf, während denen das durch **Öffnungszeit 1** und **Schließzeit 1** definierte Zeitfenster gilt.\
**Format:** numerisch oder datum.

Sie können diese Tage einzeln angeben (z. B. 1,4), als Bereich (z. B. 1–4), als ganze Zahlen (1 bis 64) oder mit Datumsformaten (z. B. 14/05/2016 ⇒ 17/07/2016).

**Beispiel 1:**\
**Öffnungstage 1 = 1,2,5** (oder **14/05/2016, 15/05/2016, 18/05/2016**)\
Das bedeutet, der Besuch kann nur an den Tagen 1, 2 und 5 im Zeitplan (oder am 14.05.2016, 15.05.2016 und 18.05.2016) innerhalb des durch **Öffnungszeit 1** und **Schließzeit 1**.

**Beispiel 2:**\
**Öffnungstage 1 = 1–5** (oder **14/05/2016 ⇒ 18/05/2016**)\
Das bedeutet, der Besuch kann an jedem Tag von 1 bis 5 (oder zwischen dem 14.05.2016 und dem 18.05.2016) innerhalb des durch **Öffnungszeit 1** und **Schließzeit 1**

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

**Öffnungstage 2**

Diese Einschränkung definiert die Menge der Öffnungstage (bis zu 64), während der das durch **Öffnungszeit 2** und **Schließzeit 2** angegebene Zeitfenster gilt.\
Diese Tage können einzeln oder als Bereich aufgeführt werden und folgen demselben Format wie in **Öffnungstage 1**.

**Beispiel 1:**\
Der Kunde kann eine Lieferung annehmen am:

* **Montag** zwischen **07:00 Uhr und 17:00 Uhr**, und
* **Mittwoch** zwischen **09:00 Uhr und 18:00 Uhr**.

**Konfiguration**:

* Öffnungszeit 1 = 07:00:00
* Schließzeit 1 = 17:00:00
* Öffnungstage 1 = 1
* Öffnungszeit 2 = 09:00:00
* Schließzeit 2 = 18:00:00
* Öffnungstage 2 = 3

**Beispiel 2:**\
Der Kunde kann eine Lieferung erhalten:

* Von **Montag bis Freitag** zwischen **07:00 Uhr und 17:00 Uhr**, und
* Am **Samstag** zwischen **09:00 Uhr und 12:00 Uhr**.

**Konfiguration**:

* Öffnungszeit 1 = 07:00:00
* Schließzeit 1 = 17:00:00
* Öffnungstage 1 = 1–5
* Öffnungszeit 2 = 09:00:00
* Schließzeit 2 = 12:00:00
* Öffnungstage 2 = 6

**Öffnungstage 3**

Diese Einschränkung listet alle Öffnungstage (bis zu 64) auf, für die das durch **Öffnungszeit 3** und **Schließzeit 3** definierte Zeitfenster gilt. Diese Tage können einzeln oder als Bereich angegeben werden und verwenden dasselbe Format wie **Öffnungstage 1**.

**Öffnungstage 4**

Diese Einschränkung gibt alle Öffnungstage (bis zu 64) an, für die das durch **Öffnungszeit 4** und **Schließzeit 4** gilt. Diese Tage können einzeln oder als Bereich eingegeben werden und folgen demselben Format wie **Öffnungstage 1**.
