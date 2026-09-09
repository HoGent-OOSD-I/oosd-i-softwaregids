## Installatie van de JDK: Java Development Kit

⚠️ **Belangrijk:** De programmeertaal **Java** staat centraal in de OLOD's OOSD I & OOSD II. Het is cruciaal om de juiste versie van de **JDK (Java Development Kit)** te installeren. Voor het academiejaar 26-27 werk je met de **Oracle JDK 25**. Zorg dat je deze installeert voordat je verdergaat.

!!! note "Stappenplan"
    1. Open een webbrowser.
    1. Surf naar [Oracle Java Downloads](https://www.oracle.com/europe/java/technologies/downloads/#java25).
    1. Download de versie die overeenkomt met jouw besturingssysteem/processor.
    1. Voer het gedownloade installatiebestand uit.
    1. Klik op **'Next'**.
    1. Behoud de standaardinstellingen.
    1. Klik op **'Next'**.
    1. Klik op **'Install'**.
    1. Wacht tot de installatie voltooid is.
    1. Klik op **'Finish'**.

### Controleren van de installatie

1. Open een terminal.
    - Druk op ++'win'++.
    - Typ **cmd**.
    - Druk op ++'enter'++.
1. Voer het volgende commando uit:

    ```bash
    java --version
    ```

1. Controleer of een versienummer wordt weergegeven dat begint met **25**.

    Bijvoorbeeld:

    ```text
    java 25
    ```

1. Voer vervolgens het volgende commando uit:

    ```bash
    javac --version
    ```

1. Controleer of opnieuw een versienummer wordt weergegeven dat begint met **25**.
1. Verschijnt in beide gevallen een versienummer, dan is de installatie correct uitgevoerd.