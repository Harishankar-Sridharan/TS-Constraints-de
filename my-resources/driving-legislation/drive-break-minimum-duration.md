# Mindestdauer der Fahrpause

Diese Einschränkung definiert die Mindestdauer einer Fahrpause, damit sie während einer Fahrt als Ruhezeit gewertet wird.

\
**Format**: HH:MM

**Hinweis**:\
Fahrpausen werden von TourSolver nicht als Arbeitszeit betrachtet. Daher verlängert sich der gesamte Arbeitstag um die entsprechende Pausendauer.

**Beispiel**:\
Wenn eine Pause nur dann als Ruhezeit gilt, wenn sie mindestens 15 Minuten dauert, dann _Mindestdauer der Fahrpause = 00:15_.

Beispielszenario (Maximale Fahrdauer ohne Pause + Fahrpausendauer + Mindestdauer der Fahrpause)

* Maximale Fahrdauer ohne Pause = 04:30
* Fahrpausendauer = 00:45
* Mindestdauer der Fahrpause = 00:15

Das bedeutet, die Ressource darf 4 Stunden und 30 Minuten fahren, wenn sie insgesamt 45 Minuten Pause macht. Diese Pause kann beispielsweise in drei 15-minütige Pausen aufgeteilt werden oder in eine 30-minütige Pause gefolgt von einer 15-minütigen Pause.

Wenn die Ressource jedoch zwei 20-minütige Pausen und eine 10-minütige Pause genommen hat, muss sie dennoch eine zusätzliche Pause von mindestens 15 Minuten einlegen, um die erforderlichen 45 Minuten an anrechenbarer Ruhezeit zu erreichen, da die 10-minütige Pause die Mindestanforderung von 15 Minuten nicht erfüllt und daher nicht angerechnet wird.
