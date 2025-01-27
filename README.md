# Scrum - individuell uppgift

**1. Redogör för de olika momenten i en SCRUM sprint:** 
I början av ett projekt när man vet vilken produkt man vill skapa/vilken produkt beställaren vill att man ska skapa, så skapar man en product backlog med user stories. 
User stories beskriver oftast vad en användare vill kunna göra och varför. En beskrivning på vad som kan vara användbart/värdefullt för användaren att ha med helt enkelt. 

Sedan så prioriterar man (oftast produktägaren) vilka user stories som måste vara med när appen är klar, och vilka som är mindre viktiga (ofta efter vad beställaren kräver för funktioner). Man kan t.ex. använda MOSCOW-tekniken där man delar in det i ”Must have”, ”Should have”, ”Could have”, och ”Will not have”. 
Om det inte finns ett team än så väljer Scrum Mastern och produktägaren ut ett team. Här kan man vilja tidestimera funktioner med abstrakta mått som till exempel story points för att ha en någorlunda överblick om hur mycket arbete man har framför sig. Det kan man göra med planning poker, där varje teammedlem kan få vara med och ge sin input.

Sedan börjar man med sprint planeringen, teamet sätter då ut mål för sin kommande sprint genom att välja ut user stories från product backloggen. Produktägaren kan ge förslag baserat på beställarens krav på vad som ska vara med. 
När man har valt vad man vill bli klar med i första sprinten så bryter man ner de user storiesarna i mindre 'tasks' och man tidsestimerar dem ännu en gång inför sprinten, t.ex. med planning poker här igen. 
En task bör inte ta mer än en dag, är en task för stor kan man bryta ner den i mindre delar. Sedan är man ”klar” med sin sprint backlog för denna sprint.

Varje dag har teamet ett scrum möte (daily scrum/daily stand up) där man snabbt går igenom vad man har jobbat på, vad man ska jobba på den dagen, och om man har några blockers/hinder. 
Utvecklaren väljer ut en task man vill jobba på utifrån sprint backloggen och jobbar på den under dagen. Sedan så fortsättar sprinten så till den är över (vanligtvis är en sprint 2-4 veckor), under processens gång så testar man och fixar även buggar som dyker upp.

Efter en sprint är över utförs en sprint review, där visar utvecklingsteamet vad de har åstakommit med under sprinten för produktägaren, och där kan även beställaren vara med. Feedbacken man får ifrån dem används till att planera ut nästa sprint. 
Det kan innebära att man uppdaterar product backloggen eller väljer ut specifika user stories.

I slutet av varje sprint görs även en sprint retrospective. Där diskuterar man vad som gick bra, och vad som gick mindre bra. Man tar med sig feedbacken till nästa sprint planering och in i nästa sprint så att arbetsprocessen kan förbättras.

Sprintplaneringen, själva arbetet under sprintens gång, retrospective och sprint review upprepas tills appen är ”färdig” (när beställaren är nöjd med resultatet, kan va när man har nått MVP till exempel).

**2. Reflektera över hur ni i teamet skapade och rangordnade user-stories, vad fungerade bra? Vad skulle kunna fungera ännu bättre?:** 
Appen började som en stegräknare men utvecklades till en app för hundägare. För att prioritera så använde vi oss av MOSCOW. Vi ville ha kvar stegräknaren som en must have och sen så utgick vi från det och gjorde även ruttspårning och promenadpåminnelse till must haves. 
Efter det tänkte vi vad som är viktigast för hundägarens perspektiv att kunna ha koll på i appen. T.ex. potty reminder kan va viktig för en med valp så att det inte sker olyckor, och att kunna tracka en bortsprungen hund med GPS etc. 

Vi hade bra team work från början, vi kom snabbt överens om vad för sorts app vi ville göra. Temat på appen var bred nog att det var lätt att lägga till funktioner man ville ha. 
Jag är inte säker på om det är en bra eller dålig grej, men vi skrev upp funktioner innan vi skrev user stories. Jag kan tänka mig att vi kan ha missat en del när vi ”översatte” dem. 

En del som inte funkade så bra var att vi jobbade lite för fort, jag tror vi kan ha missat en del bitar på vägen. Jag och en till i gruppen var mest fokuserade på mockuppen, vi var med i planeringsstadierna men jag själv jobbade mest på mockuppen. 
Jag tror att det hade funkat bättre, i alla fall som ett skolprojekt, att alla fokuserade främst på user stories och backlog istället för att dela upp oss, eftersom det kändes som jag inte hade 100% koll på vad som hamnade i vår slutgiltiga backlog. Även om det var kul att jobba mer i Figma.
 
**3. Hur skulle din process från user stories till faktisk funktionalitet i en app se ut? Använd någon av era user stories som exempel. Hur skulle du bryta ner en user stories i moment att arbeta med. När vet du om du är klar med en user story?:** 
Jag väljer vår user story: ”As a puppy owner, I want reminders to take my puppy outside to go potty, so I can avoid accidents at home.” (står under _Notification for puppy walks_ i Trello). Definition of done på den tänker jag att det kan vara när man kan skriva in hur lång tid till remindern man vill ha, när man kan se vad man har skrivit in och hur långt det är kvar tills man behöver gå ut, sedan ska man också få en notifikation när tiden gått ut, timern ska då också resettas. 

Hade det vart ett riktigt team hade jag delat upp tasks i för olika discipliner, t.ex. programmerare, QA, UI-designers etc. Man börjar med en aktivitet eller ett fragment, eller en design/mockup beroende på om den är gjord innan eller inte. 
Man kanske vill koppla den till någon tidigare klass som hanterar timers eller så gör man en egen sådan. Sedan ett fält eller en knapp man kan fylla i hur lång timern ska vara. 
Man behöver också tasks för UI, typ layouten på sidan, och en visuell representation av timern, t.ex. en klocka som tickar ner eller en cirkel som sluts och programmeraren/utvecklaren ska kunna koppla den till timer funktionen. 
Om det inte redan finns så måste man fixa så att remindern ger ifrån sig ett alarm, då krävs det också att appen har tillgång till mobilens ljudsystem och att användaren kan välja att godkänna det eller ej. 
Om QA är med i teamet så kan man ha en task att testa de andra tasksen/features och ge feedback på design.
Det ger en ganska barebones men fungerande potty reminder, sedan om man vill t.ex. kunna lägga till fler alarm för olika valpar kan man lägga till det i framtida sprints om det behövs.
