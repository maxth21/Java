Detta projekt innehåller flera Java-klasser för att hantera talserier samt en synonymhanterare. Programmen inkluderar funktioner för att lagra, manipulera och analysera sekvenser av tal samt att hantera synonymrelationer från filer.

1. ArrayNumberSequence.java:

Implementerar en sekvens av reella tal med hjälp av en array.

Funktioner inkluderar att hämta längd, största och minsta värde, kontrollera om sekvensen är ökande eller minskande samt att lägga till och ta bort element.

2. LinkedNumberSequence.java:

Implementerar en sekvens av reella tal med hjälp av en länkad lista.

Liknande funktionalitet som ArrayNumberSequence, men med dynamisk minneshantering.

3. NumberSequenceTest.java:

Ett testprogram för ArrayNumberSequence och LinkedNumberSequence.

Demonstrerar funktionaliteten genom att skapa en sekvens, skriva ut värden och testa metoder.

4. SynonymHandler.java:

Hanterar en synonymdatabas lagrad i en fil.

Funktioner inkluderar att läsa och skriva synonymer, lägga till och ta bort synonymer samt att sortera dem alfabetiskt.

5. Temp1.java & Temperatures2.java:

Program för att hantera och analysera temperaturdata över flera veckor.

Beräknar och skriver ut minsta, största och genomsnittliga temperaturer.

Hur man kör programmen:

Kompilera Java-filerna: "javac Lab3/*.java" sedan Kör testprogrammet för talserier: "java Lab3.NumberSequenceTest"
