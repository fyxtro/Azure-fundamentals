### Factors affecting costs
1. **Resource type**: Verschillende resources zorgen voor andere kosten zoals storage, vm's networks en hoeveel je ze gebruikt
2. **Services**: Verschillende soorten klanten: 
	1. Web Direct, gewoon signup op de homepage default pricing
	2. enterprise, vaak grote aantallen, betaalt jaarlijks en krijgt korting
	3. Cloud solution provider, Betaald hun en niet azure direct
3. **Locatie**: verschillende kosten per regio, ze kosten meer om een datacenter te hebben in bepaalde regio's
4. **Bandbreedte**: Als je buiten billing zones data verstuurd dan kan dat geld kosten, ookal gaat dit naar een ander azure datacenter
5. **Reserved instance**: Ipv Pay-as-you-go reserveer je voor langere tijd upfront. Hier kan je tot 72% op besparen. Je kunt hierbinnen nog wel op en afschalen.
6. **Hybrid use benefit**: als je al licenties hebt kun je die gebruiken en bespaart dit tot 47% op je maandelijkse kosten.

### Pricing calculator
Een tool waar je een voorspelling kan krijgen van wat je zou kunnen betalen. Er zijn nog een paar factoren die hier niet in gaan waardoor kosten nog iets hoger of lager kunnen uitpakken maar dit is een goede indicatie.

### DEMO Pricing calculator
Lijkt op het all services menu
Kunt meerdere resources tegelijkertijd toevoegen.
Kun het aantal running uren per maand aanpassen
Verschillende regio's zijn goedkoper dus dit is het vaak waard om te doen als dit niet teveel latency veroorzaakt.
Kan een export maken naar excel.

### Total Costs of Operation 
Calculator van Azure vs On-prem
Krijg een rapport op basis van de ingevulde gegevens zoals huur, werk uren/kosten etc.

### Azure cost management
Sorteren op basis van tags
Budgetten instellen
Alerts instellen als je boven bepaalde kosten gaat
Adviezen over waar je kosten kan besparen.

### Minimizing costs 
![[Pasted image 20221214111751.png]]
Perform - Kijk vooraf wat je waarschijnlijk gaat betalen
Monitor - Monitor het met advisor om te zien waar je kan besparen.
Use - Stel budgetten in om het te beperken
Use - Gebruik Reservations en Hybrid benefit waar mogelijk om zoveel te besparen
Choose - Kies goedkopere locaties waar dit mogelijk is.
Keep - Blijf up to date om te zien of er een goedkopere vm beschikbaar komt
Apply - Hang tags aan resources om in te zien waar de kosten heen gaan.

### Service Level Agreement(SLA)
Een SLA is een verplichting voor Microsoft om een service up en running te houden voor een X% per dienst. Free en preview items hebben geen SLA. Als ze niet gehaald worden dan kan het zijn dat je een percentage van je maandelijkse kosten terug krijgt in credit.
![[Pasted image 20221214112200.png]]

### Impact op je SLA
Als je meer services toevoegt wordt je SLA lager
Availability zones en replica's kunnen je SLA verhogen.
Je kunt je SLA berekenen door ze met elkaar te vermenigvuldigen.

### Azure preview program
Heeft GEEN SLA dus niet geschikt voor productie
Public preview 
Alle klanten kunnen dit inzien en evalueren maar deze opties kunnen ook nog verdwijnen
Generally available
Als het uit preview is en naar GA is kan iedereen het gebruiken afhankelijk van de regio.

### Monitoring service and features updates
Azure updates page: heeft een rss feed
Hier kan je ook zien of het in preview is en voor hoe lang nog.


Meer info:
aka.ms/azfunpath