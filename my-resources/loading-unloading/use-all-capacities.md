# Alle Kapazitäten verwenden

* Wenn die Option auf **Deaktiviert**, nur die **Globale Kapazität** wird berücksichtigt.
* Wenn die Option auf **Aktiviert**, **alle Kapazitäten**, einschließlich der Globalen Kapazität, werden berücksichtigt.

**Format:** Binär

**Beispiel:**\
Für eine Lieferung von Gemüse hat die Ressource die folgenden Kapazitäten:

* Fahrzeugkapazität 1: **150 kg** (Karotten)
* Fahrzeugkapazität 2: **50 kg** (Kürbisse)
* Fahrzeugkapazität 3: **100 kg** (Kartoffeln)
* Globale Kapazität: **200 kg**

Wenn **Alle Kapazitäten verwenden = Deaktiviert**, gilt nur die Globale Kapazität von **200 kg** und individuelle Kapazitäten werden ignoriert. In diesem Fall kann die Ressource tragen **30 kg Karotten, 60 kg Kürbisse und 110 kg Kartoffeln**.

Wenn **Alle Kapazitäten verwenden = Aktiviert**, müssen alle individuellen Kapazitäten und die Globale Kapazität eingehalten werden. Die Ressource kann dann tragen **50 kg Karotten, 50 kg Kürbisse und 100 kg Kartoffeln**.
