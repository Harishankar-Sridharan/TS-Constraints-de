# Geschwindigkeitsgewichtung

Wenn die beobachteten Fahrzeiten im Allgemeinen zu kurz oder zu lang sind, kann der Benutzer sie anpassen, indem er für jede Ressource angibt, ob sie schneller oder langsamer als die in den Straßenstatistiken definierte Geschwindigkeit fährt. Dadurch kann der Benutzer Verkehrsdaten an die spezifischen Einschränkungen jeder Ressource anpassen und gleichzeitig Geschwindigkeitsvariationen nach Tageszeit und Fahrtrichtung erhalten.

Die **Normal** Wert ist der Standard und dient als Referenzgeschwindigkeit, die im Fahrzeugprofil definiert und/oder von Here-Karten (Straßenstatistiken) bereitgestellt wird.

**Format:** Nummer

**Beispiel:**\
Straßenstatistiken geben eine Geschwindigkeit von **50 km/h** auf der Avenue Aristide Briand in Bagneux an.

* Wenn der Benutzer diese Geschwindigkeit für zu hoch hält, weist er eine **Geschwindigkeitsgewichtung von 1,2 (langsamer)**&#x7A;u. Die Ressource fährt dann **20% langsamer**, mit **40 km/h** statt 50 km/h.
* Wenn der Benutzer diese Geschwindigkeit für zu niedrig hält, weist er eine **Geschwindigkeitsgewichtung von 1,2 (schneller)**&#x7A;u. Die Ressource fährt dann **20% schneller**, mit **60 km/h** statt 50 km/h.
