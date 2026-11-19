# Automatische Startzeit

**Dieser Wert bestimmt, ob die Abfahrtszeit der Ressource basierend auf den Öffnungszeiten des ersten Besuchs angepasst werden soll.**\
Wenn aktiviert, trägt dies dazu bei, unnötige Wartezeiten zu minimieren und die Routeneffizienz zu verbessern.

* Wenn **Deaktiviert**, die Ressource beginnt zur in der **Arbeitszeit** Einschränkung definierten Zeit, auch wenn der erste Besuch später öffnet. Wartezeiten können auftreten.
* Wenn **Aktiviert**, die Abfahrtszeit der Ressource wird automatisch nach der Öffnungszeit des ersten Besuchs angepasst, um Wartezeiten zu reduzieren.

Die Ressource kann niemals früher beginnen als ihre definierte **Arbeitszeit**. Wenn sich die Abfahrtszeit ändert, verschiebt sich die Endzeit um denselben Betrag, außer wenn die **Tägliche Arbeitszeit** Einschränkung ebenfalls angewendet wird.

\
**Format:** Ja / Nein

**Beispiel**: Automatischer Startzeitpunkt - Ja

<figure><img src="../../.gitbook/assets/image (10).png" alt=""><figcaption></figcaption></figure>

