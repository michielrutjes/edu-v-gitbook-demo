# Change- en releasemanagement

| | |
|---|---|
| **Status** | Final - Recommended |
| **Versie** | 1.0 |
| **Beheer** | Stichting Edu-V |
| **Ingangsdatum** | Augustus 2024 |

De wijze waarop afspraken die vastgelegd zijn in afsprakenstelsel Edu-V kunnen worden gewijzigd is vastgelegd in het Change- en releasemanagementbeleid en het daarbij behorende [Change- en releasemanagement proces](proces.md).

## Change- en releasemanagementbeleid

### Uitgangspunten beleid

- In een voortdurend veranderende omgeving met een grote afhankelijkheid van nieuwe technologie is het noodzakelijk nieuwe oplossingen en functionaliteiten in de markt te blijven faciliteren, waarbij risico's en verstoringen zo min mogelijk optreden
- Change- en release management beschrijft het tot stand komen van nieuwe versies van het afsprakenstelsel.
- Het versiebeleid verbetert planning en controle van implementaties van wijzigingen en updates in de live-omgeving van het stelsel.
- Voor het uitrollen van nieuwe versies van het afsprakenstelsel wordt een meerjaren releasekalender gehanteerd.
- Het bestuur stelt één keer per jaar een (update van de) meerjaren releasekalender vast op basis van en inclusief het advies van de CAB.
- Indien een urgente wijziging noodzakelijk is kan afgeweken worden van de meerjaren releasekalender.
- RFC's worden afgehandeld conform het [Change- en releasemanagement proces](proces.md)
- Goedgekeurde wijzigingen worden gebundeld in een nieuwe versie van het afsprakenstelsel.

Voor wijzigingen die een technische aanpassing vereisen wordt een termijn aangegeven waarbinnen de wijziging doorgevoerd moet worden. In verband met de jaarcyclus van het onderwijs, belasting van de deelnemers (laagdrempeligheid) en de efficiency van het beheer is het streven om geen kritische, technische wijzigingen door te voeren tussen 15 juli en 1 oktober tenzij wetgeving of een urgente reden dit noodzakelijk maken.

Aanpassingen die geen API's inclusief verplichte datavelden raken, kunnen vaker worden doorgevoerd (bijvoorbeeld wijzigingen op het gebied van afspraken privacy (als gevolg van regelgeving) of beleid (toetreding, naleving, e.a.)).

Voor wijzigingen van API's gelden de volgende uitgangspunten:

- De stelregel is dat partijen tenminste de vorige versie (t-1) en binnen de voorgeschreven termijn de meest actuele (t) van de API ondersteunen. Alle versies ervoor (t-2 en eerder) worden niet ondersteund. Dit maakt het mogelijk voor partijen om tijdig, maar ook op een moment dat voor de partij past, de wijziging te implementeren.
- Indien de wijziging kritisch is voor het correct functioneren van Edu-V, kan van deze stelregel worden afgeweken. In dit geval wordt aan alle partijen gevraagd om tenminste ook de meest actuele versie te ondersteunen.

In het EDU-V architectuurkader zijn de uitgangspunten voor het versiebeheer van de API's uitgewerkt.

{% hint style="info" %}
NB. De nieuwe architectuur biedt meer mogelijkheden om de koppelingen los van elkaar te herzien en te implementeren. In de huidige ECK keten is het gebruikelijk om de keten jaarlijks te herzien waarbij 1 of meerdere services worden aangepast. De nieuwe versie wordt dan in zijn geheel geïmplementeerd (waarbij ook een aantal services hetzelfde blijven)
{% endhint %}

### Communicatie Release

- De goedgekeurde release van het afsprakenstelsel wordt gepubliceerd op Confluence. De wijzigingen ten opzichte van de vorige release worden daarbij apart toegelicht.
- Alle Deelnemers en belangstellenden worden op de hoogte gesteld van de nieuwe versie en de belangrijkste wijzigingen.

### Afwegingskader Wijzigingen

- In het [Afwegingskader Wijzigingen](../afwegingskader-wijzigingen.md) zijn de criteria uitgewerkt op basis waarvan een voorgestelde RFC beoordeeld wordt door het Change & Advisoryboard (CAB).
- Het vastgestelde afwegingskader wordt gehanteerd bij het adviseren over nieuwe releases en de hierin opgenomen changes.
