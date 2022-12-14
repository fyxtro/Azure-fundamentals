### Cloud models
Cloudcomputing - Efficient delivery of computing services over the internet. Hierdoor kan je flexibel op of afschalen en snel nieuwe machines opzetten

### Public cloud 
Eigendom van cloud/hosting provider
Fysieke resources en services worden gedeeld met meerdere bedrijven/gebruikers
Meestal mee te verbinden via een beveiligde verbinding.

### Private cloud
Bedrijven creëren een eigen cloud omgeving binnen hun eigen datacenter.
Ze zijn zelf de eigenaar maar ook verantwoordelijk voor de uptime en het onderhoud.
Is vaak niet bereikbaar buiten het bedrijf.

### Hybrid cloud
Combinatie van Public en Private waarbij sommige applicaties on-prem draaien die niet van buitenaf beschikbaar hoeven te zijn in de private cloud draaien en andere die dat wel moeten zijn in de public cloud omgeving draaien.
![[Pasted image 20221213093801.png]]
![image](https://github.com/fyxtro/Azure-fundamentals/raw/master/Images/Pasted%20image%2020221213093801.png)

---

### Cloud benefits and considerations
![[Pasted image 20221213093912.png]]

**High availability** - weinig downtime
**Scalability** - Gemakkelijk om extra machines/containers bij te laten draaien om de lading te verdelen/op te schalen.
**Global Reach** - Door data te verdelen over de wereld is het altijd dichtbij met weinig vertraging
**Agility** - Gemakkelijk om tijdelijk op te schalen als er meer resources nodig zijn door een zware workload

**Fault tolerance** - Alles draait op enterprise hardware en heeft een hoge uptime garantie (99.9%+)
**Elasticity** - Makkelijke up en af schalen in bursts op basis van gebruik. Bijv. een webserver die af en toe een zware berekening moet maken.
**Customer Latency Capabilities** - Resources door de wereld heel plaatsen zodat er altijd een server in de buurt is en de latency laag blijft.
**Predictive Cost Considerations** - Kosten zijn voorspelbaar met een duidelijk overzicht vooraf

### CapEx vs OpEx
![[Pasted image 20221213094125.png]]
CapEx - Capital Expenditure
Koopt de hele server in één keer en blijf daarna deze hardware gebruiken totdat je een nieuwe koopt/upgradët.

OpEx - Operational Expenditure
Betaald voor de diensten en de resources die je gebruikt en niet voor de volledige mogelijkheden van de server. Vaak in een maandelijks of jaarlijks tarief.

### Comsumption based model
Vooraf zijn de kosten voorspelbaar op basis van het gebruik
Betaal voor alle diensten los van elkaar ipv voor één server.
Betaal voor daadwerkelijk gebruik en niet voor het mogelijke gebruik.

### Cloud services
**IaaS**
Pay-as-you-go voor firewall, servers, storage, networks.
Voorbeeld: Azure

**Paas**
Provider beheerd firewall, servers, storage, networks, jij beheert alleen de applicatie die hierop draait.
Voorbeeld: App-services/Azure Docker containers

**SaaS**
Jij gebruikt alleen de applicatie die door de SaaS-provider wordt geleverd en bent niet verantwoordelijk voor de server, firewall, beschikbaarheid, uptime en onderhoud.
Voorbeeld: Office 365/teams
![[Pasted image 20221213094518.png]]

![[Pasted image 20221213094605.png]]

