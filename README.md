# Testing

## A1 Unit-Test

Ich habe für mein Projekt SpieltagPLUS eine eigene Klasse TicketpreisRechner entwickelt, die den Ticketpreis berechnet aus der Multiplikation Ticketanzahl und Preis pro Ticket.
Mit JUnit wurden zwei Tests durchgeführt:
- Test der korrekten Preisbrechnung
- TEst auf IllegalArgumentException, wenn man eine ungültige Ticketanzahl eingibt

Die Tests wurden mit mvn test ausgeführt und bestanden.

### Projekt angelegt

![Maven Projekt](images/maven.png)

### Test

![Maven Test](images/maven_test.png)

### Test nach Erweiterung

![Maven Test 2](images/maven_test2.png)


## A2 TDD

## A3 Mocking

In meinem Projekt SpieltagPLUS ist der Bezahldienst eine unangenehme Methode, da ich eine zuverlässige Internetverbindung brauche, abhängig von von externen Anbietern etc.
