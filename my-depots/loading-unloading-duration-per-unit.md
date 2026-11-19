# Lade-/Entladedauer pro Einheit

Diese Einschränkung legt das fest **Zeit, die am Depot benötigt wird, um eine Einheit Produkt zu laden oder zu entladen**. Der Wert wird multipliziert mit dem **Produktmenge** zum Laden oder Entladen, abhängig vom Routentyp.

> **Hinweis:** Dies gilt **nur** für die **Menge 1** Einschränkung der Besuche und **nicht** für die anderen 23 möglichen Mengen.

**Format:** HH:MM

**Beispiel:**

* **Feste Lade-/Entlademauerzeit:** 00:3:00
* **Lade-/Entladezeit pro Einheit:** 120 Sekunden (2 Minuten pro Einheit)
* **Zu ladende Menge:** 8 Einheiten

Berechnung:

* Zeit für Einheiten = 120 Sek × 8 = 960 Sek = 16 Minuten
* Gesamtdauer im Depot = 30 Min (fest) + 16 Min = **46 Minuten**

**Abhängig von:** Menge (Lieferungen)
