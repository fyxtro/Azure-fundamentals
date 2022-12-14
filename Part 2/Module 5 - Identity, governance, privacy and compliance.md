### Authenticatie vs authorization
Authenticatie verifieert of jij bent wie je zegt dat je bent dmv bijv username/password
Authorization bepaald waar je dan toegang toe hebt op basis van je authenticatie.
Op het vliegveld laat je je boarding pass zien en je passpoort dit is je authenticatie.
Hierna heb je alleen maar toegang tot 1 vliegtuig en 1 stoel. dit is je authorizatie.

### Azure MFA
Een extra laag beveiliging kan verschillende manieren geimplementeerd worden.
Iets dat je weet (wachtwoord)
Iets dat je hebt (app op je telefoon)
Iets dat je bent (vingerafdruk) (Deze optie bestaat (nog) niet in Azure)

### Azure Active Directory (AAD)
Cloud based identiteits en toegang beheer.
Regelt het volgende: Authenticatie dus een login scherm voor je sharepoint. Kan je eigen regels instellen voor wachtwoorden.
SSO zorgt ervoor dat je over in kan loggen met 1 gebruikersnaam en 1 wachtwoord. Als iemand uit dienst gaat hoef je dan maar 1 account te verwijderen.
Guest users kan je instellen om klanten of andere bedrijven toegang te geven tot bestanden

### Conditional Access
Wordt gebruikt door AAD en hierin kan je regels opstellen op basis van verschillende data zoals Gebruiker, groep, ip/locatie, device etc.
Op basis hiervan kan je bijv MFA afdwingen buiten het kantoor netwerk. Of kan je gehele toegang worden ontnomen in het buitenland of op een specifiek aparaat.

### Rolebased access control RBAC
Hiermee kan je bepaalde gebruikers verschillende rollen geven waarbij andere rechten komen kijken. Je kan een user rechten geven tot alleen vm's in een bepaald abonnement en een andere user mag alleen de Virtual Networks beheren in datzelfde abonnement. Zo kan je gebruikers alleen de rechten geven die ze nodig hebben om hun werk te kunnen doen.

### DEMO RBAC
In het abonnement onder Access Control
Owners kunnen andere owners eruitgooien.
Je kunt custom rollen maken en controleren of bepaalde user hierna de juiste rechten hebben.

### Resource locks
Sloten zetten op resources om per ongelijk verwijderen te voorkomen . Als iets namelijk is verwijderd dan is het permanent weg. 
2 soorten sloten, **CanNotDelete**, hiermee kan je nog wel aanpassingen maken en vm's enz deployen en **Read Only**, hiermee kan je alleen alles inzien maar niets wijzigen

### DEMO Resource locks
Locks kunnen gemaakt worden op resource groups of zelfs abonnement niveau
Bepaalde rollen kunnen Locks maken maar ook verwijderen.
Lock verwijderen vraagt niet om bevestiging

### Tags
Hiermee kan je inzichtelijk krijgen waar bepaalde kosten heen gaan.
Op basis van bepaalde teams of managers bijv.
Bestaan uit Naam:Waarde
Je kunt 50 tags per resource instellen

### Azure policy
Hiermee kan je standaarden instellen waarbij users maar uit een selectie van bijv. VM's, containers, storage kunnen kiezen. Er is een default policy maar er kunnen nieuwe aangemaakt worden. Hierbinnen kan je dit op userlevel aanpassen en bepaalde mensen wel toegang geven tot het deployen van bepaalde soorten vm's.

### Demo Azure Policy
Als je een policy maakt moet je zelf zorgen dat je daarna compliant bent op al bestaande resources. De nieuwe resources gaan wel automatisch. Zo hindert het niets wat al draait.
Kan bijvoorbeeld bepaalde regios wel permitteren om te deployen en anderen niet.

### Azure blueprints
Dit is een volledige blueprint van je azure omgeving.
Werkt met resource groepen, rollen, policies en ARM templates.

### Cloud adoption framework
Best practices, tools en hulp met de transitie van onprem naar de azure omgeving.

### Security, privacy en compliance
Security, altijd de meest up to date beveiliging
Privacy, Door transparant te zijn kan je zien wat zij doen met de data.
Compliance, altijd bezig met lokale wetten en voorschriften.

### Compliance Terms and Requirement
Meest omvattende compliance aanbod
![[Pasted image 20221214104247.png]]

### Azure compliance documentation
Je kan op docs.microsoft alle compliance documenten vinden voor jouw regio/locatie

### Privacy statement
Hierin staat transparant wat je zij doen met je data

### Trust center
Basis center voor alles wat te maken heeft met hoe microsoft de processen benadert.
microsoft.com/trustcenter

### DEMO trust center
Kan hier vinden wat ze doen met je data en waar het vandaan komt
Audit reports worden door onafhankelijke partijen uitgevoerd.

### Azure sovereign regions
(US government)
Staat volledig los van alle andere azure omgevingen.
(Azure China)
Eisen van China dat het via 21Vianet gaat zodat de data bij hun blijft.

