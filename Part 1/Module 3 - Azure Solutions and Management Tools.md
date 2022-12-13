### Azure IoT
**IoT central** - Fully managed SaaS oplossing waarbij je alleen je apparaten hoeft te verbinden
**IoT Hub** - Central message hub voor verbinding tussen de server en de apparaten. Hier heb je dus wel de server in eigen beheer.
**Sphere** - premium oplossing van de IoT hub die erg gericht is op de security en opgebouwd is met specifieke hardware hiervoor.

### Big data and analytics
**Azure Synapse analytics** - Cloud based data warehouse voor het opslaan van alle data die je daarna zelf moet verwerken
**Azure HDInsight** - Fully managed analytics service om grote hoeveelheden data te verwerken en op te slaan
**Azure databricks** - Apache spark based analytics service

### AI en ML
**Azure machine learning** - cloud based om te developen, trainen en ML modellen uit te rollen of te genereren.
**Cognitive services** - gebruikt AI om te lezen, luisten en kijken en handelen op acties van gebruikers (chat bots, gezichtsherkenning en fotoherkenning)
**Azure bot services** - Automatiseren van het verkrijgen van data of het voorzien van data aan andere applicaties.

### Develop apps met DevOps en GitHub
**DevOps** - Tools om samen te werken zoals: pipelines, kanban schema's en automatische load testing
**Github** - Software developing met version control, bug/task management en source code management
**Github actions for Azure** - Automatisch compilen, testen en uitrollen van applicaties in de cloud
**Azure DevTest Labs** - Snel volledige omgevingen aanmaken om applicaties te kunnen testen zoals een eindgebruiker dat zou doen.

### Azure management tools
![[Pasted image 20221213110020.png]]
Automatiseren van handelingen op resources, zoals reboot, start stop, op/afschalen etc.
Hier zijn cmdlets voor die geïnstalleerd kunnen worden in powershell en een applicatie voor op Linux. Daarnaast zijn er custom applicaties te bouwen door de REST API te gebruiken.

### ARM templates
Versnellen het deployen van vm's, containers en apps.
Zo zijn ze altijd hetzelfde en kun je deze uitrollen met bijvoorbeeld powershell.

### DEMO VM aanmaken met powershell in de azure omgeving
Storageaccount is hiervoor nodig omdat de code opgeslagen wordt. (kost geld)
Kan via powershell met simpele commands een vm maken, status opvragen en stoppen met create-azvm, get-azvm en stop-azvm.

### Azure Advisor
Adviezen voor Kosten, reliability, performance en security.
Wordt aangegeven wat je kan doen om het op te lossen en sommige hebben quick fix knoppen om dit voor je te doen.

### Service Health
Kan per subscription zien of er problemen zijn met de services die je gebruikt voor de zones waar je die gebruikt en of er issues zijn geweest of maintenance geplanned is.

### Azure monitor
Inzichten in de performance en logs van de apps en services.
Alerts als er ineens een spike is in usage.
Terug te zien in aangepaste dashboards