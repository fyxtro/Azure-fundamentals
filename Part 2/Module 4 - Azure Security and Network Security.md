### Azure security center(ASC)
Monitoring service die threat protection aanbied. Dit is ook uit te rollen op onprem oplossingen.
Levert ook oplossingen aan om de zwakke plekken op te lossen.
Heeft een gratis tier - assesments and recommendations
Standard tier - continuous monitoring and threat detection

### DEMO Security portal showcase
Kan zien wat er aan de hand is per resource
Sommige hebben een quick fix knop die het automatisch oplost voor je.
Is gebaseerd op de best practices van Microsoft.

### ASC capabilities
![[Pasted image 20221214094034.png]]

### Azure sentinel
Is een **SIEM** en **SOAR** oplossing met AI die automatisch handelt op basis van gevonden data in bijv. o365, Azure Active Directory, Azure Advanced Threat Protection. 

### Azure key vault
Bestaat uit:
1. Secrets management
2. Key management
3. Certificate management
4. Secrets die beveiligd zijn door hardware security modules(HSM) (premium tier)
Kan gebruikt worden om een key aan te maken waarin de gebruikersnaam en wachtwoorden staan voor templates zodat deze niet in de daadwerkelijke json template staat voor vm's.

### DEMO Key vault
Key vault namen moeten globally unique zijn.
Wordt bijgehouden wie waar en wanneer een key zichtbaar wordt gemaakt.

### Azure dedicated host
Dedicated server huren. Hier krijg je de gehele server dedicated aan jouw organisatie.
Geeft isolatie van de andere servers omdat niemand die hardware gebruikt. Hier krijg je korting op als je ze voor langere tijd vooruit reserveert.

### Defense in depth
Verschillende lagen zodat een aanvaller veel tijd nodig heeft.
![[Pasted image 20221214095337.png]]

### Shared security
Security wordt verdeeld op basis van wat je afneemt bij azure.
![[Pasted image 20221214095519.png]]

### Network security groups(NSGs)
Zorgt ervoor dat je verkeer op je Virtuele netwerk kan filteren. Bijv verkeer naar bepaalde ip's, poorten, of bepaalde protocollen.
Je kunt meerdere regels maken met verschillende prio's
Defaults worden uitgerold maar kunnen niet verwijderd worden. Ze kunnen we overruled worden door een andere met een hogere prio.

### DEMO NSGs
lagere prio is een hogere prioriteit.

### Azure firewall (FaaS)
Geeft toegang op basis van IP en logt alle requests.
Werkt zowel inbound als outbound.


### Azure ddos protection
Kijkt naar ongewenst verkeer voordat het impact op je service heeft.
**Basic** tier is automatisch ingeschakeld.
**Standard** tier kost meer maar geeft toegang tot extra features die specifiek op jouw VN resources worden toegepast. Kan vrij duur worden.

### Defense in depth reviewed
![[Pasted image 20221214100440.png]]
