### Regions
Meer dan 60 regions over de wereld heen, op dit moment de meeste van alle cloud-providers  
Dit zorgt ervoor dat je altijd een server in de buurt kan huren.  

### Region pairs
Minstens 300 mijl uit elkaar  
Automatische replica's tussen 2 locaties  
Deze zijn voor azure het belangrijkste om 1 van de 2 altijd draaiende te houden.   
Updates worden sequentieel uitgerold om downtime te voorkomen.  
![[Pasted image 20221213094943.png]]

### Availability zones
Voorkomt downtime door meerdere datacenters in een regio te hebben.  
Als de ene down gaat blijft de rest up doordat ze een onafhankelijke toevoer van stroom, koeling en internet hebben.  
Zijn met elkaar verbonden door een eigen privé fiber verbinding.  

### Fysieke beveiliging
Hekwerk, rotonde, drempeld en scherpe bochten  
Gebouwen zijn color coded tussen de 3 gebouwen en zijn volledig los van elkaar up en running te houden.  

### Availability options
VM SLA - 99.9% 1 enkele VM met premium storage  
VM SLA  - 99.99% availability zones, Hierbij kan een heel datacenter kapot gaan zonder downtime  
Multi region disaster Recovery - Region pairs in 2 data centers welke 300 mijl apart van elkaar staan zodat een gehele regio down kan gaan zonder volledige downtime.  

### Azure resources
Zijn de componenten die Azure aanbied zoals:   
Virtual Machines, Storage accounts, Virtual networks, App services, (SQL) Databases en Functions  

### Resource groups
Bundeld resources samen zodat ze makkelijker te beheren zijn op groepniveau ipv per instance.  
![[Pasted image 20221213095547.png]]
Alles kan maar 1 keer in een groep zitten maar kunnen wel over verschillende regio's verdeeld worden. Ze kunnen tussen groepen worden verplaatst en applicaties kunnen gebruik maken van meerdere groepen tegelijkertijd.  

### Azure Resource manager (ARM)
Kan automatisch de resources benaderen, aanmaken en verwijderen met azure portal, powershell, cli en rest api's.  

### Azure subscriptions
Verschillende soorten abonnementen met limieten en aparte facturen bijv. voor verschillende teams binnen een organisatie.  
Per account kun je toegang tot één of meerdere subscriptions hebben.  

### Azure compute services
On demand diensten draaien zoals Storage, processors, memory, networking en operating systems.  
Voorbeeld: Virtual Machines, App services, Containers, Azure kubernetes Services (AKS), Windows virtual machine(AVD)  

### Azure vm's -IaaS
Softwarematige emulatie van een Fysieke computer  
Virtual processor, geheugen, opslag en netwerk  
Kan automatisch meeschalen op basis van usage in de vorm van bursts  

### DEMO VM opzetten
Availability Zone vs Set  
**Zone** is in een ander datacenter  
**Set** zit in hetzelfde datacenter maar bijv. op andere hardware in een ander rack   
Verschillende storage options geven een verschillende uptime garantie   
Als je al een Windows server licentie hebt kun je flinke korting krijgen.(tot 49%)  

### Azure App services
Managed platform om webapps en API's te ontwikkelen  
Werkt met .Net, .NetC Core, Node.js, Java, Python of PHP.  
PaaS oplossing met enterprise performance, security en compliance  

### Serverless computing
Azure functions - Stukjes code die geactiveerd wordt op basis van bepaalde triggers, zoals opschalen als usage lange tijd boven een percentage zit.  
Azure Logic Apps - Automatiseren van taken, processen en werkzaamheden zoals meerdere vm's in een bepaalde volgorde opstarten.  
Ze zijn instant en draaien altijd maar erg kort.  

### Azure container services
Azure Containers Instances(ACI) zijn PaaS optie, goedkoop en zijn snel op te starten zonder de vm in beheer te moeten hebben. Images kunnen public en private zijn.   
Azure Kubernetes Service (AKS) bijvoorbeeld voor Rolling upgrades en automatische scaling. Is gemaakt om veel containers tegelijk te beheren en ze naadloos te laten samenwerken.  

### DEMO Container Opzetten
Quickstart images, azure container registry en Docker Hub or other registry.  
Krijgt een publiek [region].azurecontainer.io DNS/FQDN  

### Windows virtual desktop
Volledig virtueel desktop omgeving zonder dat er een broker nodig is.  
Kan oneindig ver opschalen om erg intense workload te handelen  
Kosten worden verminderd omdat de resources voor de sessies worden gedeeld tussen elkaar.  

### Azure networking services
**Virtual networks** linken resources met elkaar maar deze moeten wel binnen één regio staan.  
**VPN** Verbinding voor beveiligd verkeer tussen azure en on-prem netwerken over het publieke internet  
**Express route** Is een premium alternatief voor een VPN waarbij de verbinding naar de On-prem server volledig privé is.  

### DEMO Virtual network aanmaken
Virtual network geef je een lokaal IP subnet  
VM's moeten aan dezelfde resource groep als het virtual network toegevoegd worden  
VM's Krijgen wel hun eigen publieke ip.  
VM's binnen de VN zijn alle vm's automatish bereikbaar voor elkaar met hun hostnaam dus de DNS wordt hierdoor ook geregeld.  
![[Pasted image 20221213103916.png]]

### Database services
**Cosmos Database** non sql globally distributes 99.999% uptime  
**Azure sql Database** is DaaS mssql en draait op altijd op de laatste stabiele versie hiervan  
**Azure Database for mysql** is DaaS mysql en draait op altijd op de laatste stabiele versie hiervan  
**Azure Database for postgreSQL** is DaaS postgreSQL en draait op altijd op de laatste stabiele versie hiervan  
Azure bied ook een Migration service aan om de on-prem database naar de cloud te verplaatsen.  

### Azure sql managed instance
Fully managed PaaS  
Azure zorgt voor de patching, availability, updates en backups.  
Zorgt voor minimale aanpassingen terwijl je toch je apps naar de cloud kan verplaatsen  

### Azure marketplace
Find, try an purchase en provisions apps.  
Verschillende prebuilt vm's/containers en logic apps.  
Kant-en-klaar oplossingen voor AI, Databases, blockchain, development, webapps ed.  


