# Systemutveckling i praktiken + GitHub

## 1. Vattenfallsmodellen och agil metodik

**Beskriv skillnaden mellan vattenfallsmodellen och agil metodik.**
När bör man använda vilken, och varför?

Skillnaden mellan vattenfallsmodellen och agil metodik är att vattenfallsmodellen följer en bestämd plan där varje steg görs i ordning, till exempel från steg 1–10. När man är klar med ett steg går man vidare till nästa och följer planen hela vägen utan att göra några större förändringar. Det gör att man behöver ha en tydlig bild av vad man ska bygga från början och tydliga instruktioner. Denna typ av metod kräver mycket planering där man behöver bryta ner varje del noggrant. Agil metodik är en mer flexibel metod där projektet delas upp i kortare perioder som kallas sprintar. Under varje sprint testar man det man har gjort, får feedback och kan ändra saker om det behövs under projektets gång. På så sätt behöver inte allting vara bestämt från början och man kan förbättra projektet efter hand. Med denna typ av metod kan man ständigt förbättra projektet men även uppdatera det kontinuerligt med bättre funktioner och anpassa det till den som ska använda till exempel appen. 

Vattenfallsmodellen passar bäst när man vet vad man ska bygga eller vad kunden behöver. Då kan man planera projektet noggrant innan man börjar och säkerställa att det är just det kunden är ute efter. Ska man till exempel bygga ett system för ett flygplan så är vattenfallsmodellen bäst eftersom säkerheten måste vara extremt högt prioriterad. Kraven för systemet behöver vara tydliga från början och varje del måste planeras och kontrolleras noggrant innan man går vidare till nästa steg. 

Agila metoden passar bäst när man inte riktigt vet exakt hur projektet kommer att se ut från början eller när man behöver kunna ändra saker under projektets gång. Ett exempel är om man ska bygga en app som Facebook eller Instagram där man lägger mycket tyngd på att få användarna att gilla appen. Då kan man få feedback från användarna och se vad som fungerar bra eller vad som behöver förbättras. Då kan man lägga till nya funktioner och fixa buggar samtidigt som man anpassar appen efter vad användarna behöver. 


## 2. Git-commit

**Vad är ett Git-commit och varför är det viktigt?**
Beskriv ett verkligt scenario där Git hjälper dig undvika problem.

En Git-commit är en sparad del av projektet där man sparar de ändringar man har gjort. Sitter man och utvecklar en funktion i en app till exempel en knapp och är klar med koden så commitar man den och pushar upp den. Då blir den delen som en version som sparas på Git med ett meddelande så man vet vad man har utvecklat och kan alltid komma tillbaka till den delen. Fortsätter man att koda och märker att det har blivit något strul och man behöver gå tillbaka till sin kod där man utvecklade något sen innan, så kan man se sina tidigare commits och läsa meddelandet och snabbt gå tillbaka och göra de ändringar man behöver. Det är viktigt att man sparar sitt arbete steg för steg så man kan gå tillbaka snabbt om något går snett och se vilka ändringar som har gjorts. 

### Scenario: 

Jag har precis börjat programmera en inloggningssida på en app och är klar med inloggningen. Jag gör en commit så att jag har sparat den delen där allt fungerar, skriver ett meddelande "Lagt till inloggning" och sedan pushar den till Github. Nu går jag vidare till nästa steg där jag ska lägga till funktionen att skapa ett konto och råkar ändra på något som gör att inloggningen slutar fungera. Då kan jag gå tillbaka till mina tidigare commits där jag vet att inloggningen fungerade och på så sätt undvika att behöva göra om allt från början. 
