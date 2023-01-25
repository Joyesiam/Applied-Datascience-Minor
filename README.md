# Applied-Datascience-Minor
Student: Joanne Pals  
Studentennummer: 20189186
https://markdownlivepreview.com/

- container project met of zonder hoofdletter?
- koppen grootte
- titels bij grafiek
- episode/ games/ epoch recht trekken
- naar elk bestand/ plaatje verwijzen
- Lp model 
- links proberen

https://datascience.hhs.nl:8888/user/20189176/notebooks/ads5/FoodBoost%20eerste%206%20weken/Stap%205%20Lp%20model%20v3.ipynb
- bronnen rl toevoegen
- q learning 
- starr leerdoelen controleren
- literatuuronderzoek uitbereiden 
- termologie 
- hoofdstuk overig 

# Inhoud
- [Verplichte criteria](#Verplichte-criteria)  
  - [DataCamp](#DataCamp)
  - [Mijn bijdrage aan het project](#Mijn-bijdrage-aan-het-project)
  - [Mijn leerdoelen](#Mijn-leerdoelen)
  - [Evaluatie van de groep](#Evaluatie-van-de-groep)
- [Onderzoek naar het project](#Onderzoek-naar-het-projec)
  - [Definiëren van de taken](#Definiëren-van-de-taken)
  - [Evaluatie](#Evaluatie)
  - [Conclusies](#Conclusies)
  - [Planning](#Planning)
- [Voorspellende analyses](#Voorspellende-analyses)
  - [Foodboost](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/README.md#foodboost-4)
  - [Container](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/README.md#container-4)
- [Domeinkennis](#Domeinkennis)
  - [Introductie](#Introductie)
  - [Literatuuronderzoek](#Literatuuronderzoek)
  - [Terminologie](#Terminologie)
- [Data voorbereiding](#Data-voorbereiding)
  - [Foodboost](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/README.md#foodboost-8)
  - [Container](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/README.md#container-8)
- [Communicatie](#Communicatie)
  - [Presentaties](#Presentaties)
  - [Paper](#Paper)
- [Overige dingen](#Overige-dingen)


# Verplichte criteria

## DataCamp
![DataCamp](/Afbeeldingen/DataCamp.png "This is a sample image.")

[Terug naar de inhoud](#inhoud)

## Mijn bijdrage aan het project

Tijdens het de minor heb ik de rol van voorzitter op me genomen. Zo was ik de voorzitter tijdens de vergaderingen en maakte ik de agenda voor de vergaderingen.  Tijdens het maken van de agenda keek ik altijd vooruit naar toekomstige taken, bijvoorbeeld een presentatie, zodat we die als groep konden bespreken en niet vergeten. We dwaalden als groep vaak af van het onderwerp van de vergadering en haalde ons dan weer terug. Vanaf week elf was ik er op maandag tijdens de vergaderingen niet wegens de colleges van een tweedejaars vak. Het was de bedoeling dat de groep nog steeds op maandag ging vergaderen, daarvoor had ik aangeboden om een agenda te maken, dat hadden ze afgeslagen. In week elf hadden ze erg kort vergaderd en de weken erna hebben ze niet vergaderd. Daarom hadden we besloten om vanaf week 12 maar één keer per week te vergaderen met mij als voorzitter. Hierdoor denk ik dat ik de juiste persoon was om de voorzitter te zijn.

Tijdens het Foodboost project heb ik vooral bijgedragen aan het Lineair programmeer model en de koppeling tussen bestanden. Zo heb ik bijvoorbeeld de koppeling tussen het LP-model en de Decision Tree Classifier gemaakt. Daarnaast heb ik de aanbevolen aanvaardbare calorieën voor lunch en diner opgezocht, deze heb ik samen met Jesse onderzocht. De verschillende noten heb ik ook opgezocht. Ik heb de data gefilterd zodat we alleen lunch en diner recepten gebruikten voor het voorspellen van een recept. 

Mijn bijdrage aan het container project waren de restricties van de kade en een eigen Reinfocement Learning model. Daarnaast heb ik tijdens de hele minor andere geholpen waar nodig. 

Mijn bijdrage aan de paper was de inleiding, spellingscontrole, opmaak en het verbeteren van toekomstig werk. Ook heb ik een aantal presentaties gegeven. 

| STARR | Uitleg |
| --- | --- |
| S | Iedereen van de groep moest een Reinfocement Learning model maken. |
| T | Mijn taak was om zelf een Reinfocement Learning model te maken. |
| A | Eerst heb ik online een voorbeelden van Reinfocement Learning opgezocht. Toen kwam ik er achter dat ik een environment en een agent moest maken. Als eerste heb ik een speelveld gemaakt waar de containers opgezet konden worden. Dat heb ik gedaan met een driedimensionale matrix. Vervolgens heb ik controles gemaakt voor de restricties op de kade op basis van deze matrix. Het speelveld en de controles heb ik getest en aangepast waar nodig. Daarna heb ik een environment gemaakt met daarin de controles en het speelveld. Daarvoor heb ik verschillende voorbeelden van een environment in Python opgezocht. Het makkelijkste environment heb ik aangepast naar ons probleem en op basis van de andere heb ik in mijn environment aangepast/ uitbereid. Daarna heb ik test code geschreven om te kijken of alles in mijn environment werkt. <br> <br> Om een agent te maken heb ik dezelfde stappen doorlopen als bij die van een environment. Daarna heb ik mijn environment gekoppeld aan mijn agent en getest of dat werkte. <br> <br> Daarna ging ik een neuraal netwerk aan mijn environment en agent koppelen. Dat lukte erg lang niet, maar uiteindelijk is het gelukt. Ik dacht dat ik Deep Q-learning aan mijn agent had gekoppeld maar later kwam ik er achter dat het Q-learning was. Het Q-learning heb ik getraind op mijn environment. Vervolgens heb ik mijn code van het Q-learning omgeschreven naar Deep Q-learning met behulp van voorbeelden op het internet. Deep Q-learning heb ik ook getraind op de agent. |
| R | Als resultaat heb ik een agent en een environment waarop zowel het Q-learning algoritme als het Deep Q-learning algoritme op is getraind. Deze algoritmes voldoen ook aan de restricties van de kade. |
| R | De volgende keer moet ik meer uitzoeken wat Deep Q-learning is en of er niet iets bijna hetzelfde is met ongeveer dezelfde naam, zodat ik de volgende keer niet weer de fout maak van iets proberen te maken maar dan toch net iets anders maak. <br> <br> Daarnaast moet ik de volgende keer eerder om hulp vragen aan anderen als ik vast zit. Want nu heb erg lang op een bepaald stuk vast gezeten en mogelijk kon iemand anders redelijk snel het probleem vinden en een mogelijke oplossing vinden. |

[Terug naar de inhoud](#inhoud)

## Mijn leerdoelen

Aan het begin van de minor wilde ik graag kennis maken met Machine Learning en neurale netwerken. Tijdens de minor heb ik dat gedaan door de colleges te volgen, Datacamp te maken en online bronnen te gebruiken tijdens het programmeren. 

Ik wist niet dat er zo veel verschillend dingen waren waar je op moet letten als je een model wil trainen. Ik wist bijvoorbeeld wel dat de data eerst voorbereid moest zijn maar niet dat je ook moest kijken of het gebalanceerd was. Met de meeste evaluatie metrieken had ik al ervaring maar ik heb er nu meer inhoudelijke kennis over op gedaan. Ik dacht dat een model zelf trainen veel lasteriger zou zijn, maar nu ik het gedaan heb valt het allemaal mee. Want de meeste tijd zit in de data voorbereiden en het model evalueren. 

Nu weet ik waar ik neurale netwerk allemaal voor kan gebruiken, zal ik het later sneller nog een keer gebruiken. 

| STARR | Uitleg |
| --- | --- |
| S | Tijdens het Foodboost project moesten er modellen getraind worden. |
| T | Mijn taak was om een model te maken en te trainen om de voedingsstof vet te voorspellen op basis van de andere voedingsstoffen. |
| A | Als eerste had ik de dataset nutritions op geschoond. Daarna heb ik gekeken welke andere voedingsstoffen sterke correlatie hadden met vet. Daar kwam de voedingsstof energie uit. Vervolgens heb ik gekozen wel model ik wil gebruiken; Lineaire Regressie. <br> Om een model te trainen heb ik eerst de data gesplitst. Daarna kwam ik er achter dan ik eerst moest kijken of de data normaal verdeeld is of niet. Met histogrammen heb ik daar naar gekeken. De data was niet normaal verdeeld, dat heb ik opgelost door de wortel te trekken van de data. Daarna moest ik ook uitzoeken of de data geen uitschieters bevat. Van de originele data heb ik boxplotten gemaakt. Daar was één uitschieter te zien, die heb ik uit de data gehaald. <br> Daarna kon ik het model gaan trainen met de data. Vervolgens moest ik een evaluatie metriek kiezen. Daarvoor heb ik de R2-score gekozen. De uitkomsten uit het model moest ik eerst naast de originele waardes zetten zodat ik ze kon vergelijken, dus dat heb ik gedaan. Ook moest ik de uitkomsten van het model kwadrateren. Daarna heb ik de R2-score berekend en kon in het model daarmee evalueren. |
| R | Als resultaat van de R2-score kwam een score van 0.6617. Dus ik heb een werkend Lineair Regressie model gemaakt. |
| R | De volgende keer moet ik misschien Cross-validation op het model uitvoeren om zo een nog beter beeld te krijgen hoe goed het model werkt. Daarnaast weet ik voor de volgende keer dat ik genoeg tijd moet nemen om de data voor te bereiden voordat ik het model zelf kan train. Ik had zelf namelijk verwacht dat het trainen van het model langer zou duren dan de data voorbereiden. | 

[Terug naar de inhoud](#inhoud)

## Evaluatie van de groep

Ik vond het erg fijn om met mijn groepsgenoten samen te werken. We hadden respect voor elkaar en naar de mening van iedereen werd geluisterd. In de eerste week van de minor hadden we onze sterkte en zwakte punten besproken zodat we daar rekening mee konden houden en elkaar daar mee helpen. Om hulp vragen ging naar mijn idee erg goed in de groep, vaak boden we het ook aan als we een onderwerp introduceerden waar niet iedereen kennis over had. Ik merk ook dat we steeds meer een groep werden door dat we elkaar leerden kennen, daardoor hebben we veel plezier gehad. Ik zal nu reflecteren per groepslid.

Ayrton: Een zin dit hem omschrijft: "Het maakt mij niet zo veel uit". Dat hebben we hem vaak horen zeggen. Daarnaast zei hij niet zo veel. Ik merkte dat hij soms achterliep op de groep qua kennis, wat niet erg is. Maar als we hem vroegen of hij uitleg er over nodig had, zei hij van niet, maar als we hem een vraag over het onderwerp stelden om te controleren of we het duidelijk hadden uitgelegd dan begreep hij het niet. Het leek als of hij sommige dingen niet wilde begrijpen, doordat hij niet over onderwerpen door vroeg als hij het niet begreep. Een leerdoel voor hem is om hulp vragen als hij dat nodig heeft, wij vinden het niet erg om je te helpen.

Voor mijn gevoel heeft hij niet zo veel bijgedragen aan de groep en het project. Zo heeft hij wekenlang literatuuronderzoek gedaan zonder dat wij er resultaten van zagen, ook als we er naar vroegen terwijl de deadline al was geweest.

Eric: Met Eric heb ik al vaker projecten gedaan en deze ik ben ik weer blij dat ik het met hem heb mogen doen. Hij heeft vaak veel goede input over hoe we een probleem kunnen oplossen. Daarnaast kon ik hem altijd om hulp vragen en dan gaf hij een duidelijk antwoord zodat ik weer verder kon. Zijn taken voerde hij grondig uit, niet alles is in de eindproducten gekomen, maar hij heeft het toch gedaan.

Jesse: Ook met Jesse heb ik vaker samengewerkt en ook nu weer is hij erg fijn om mee te werken. Hij was altijd enthousiast over de projecten, waardoor de rest van de groep en ik gemotiveerd werden om een mooi eindresultaat te hebben. Naast de minor volgde hij ook vierdejaars vakken van Toegepaste Wiskunde waar we als groep ook wat aan hadden, zo kwam hij bijvoorbeeld met Optuna studies.

Martti: Een gezellige jongen die altijd in was voor een praatje. Daarnaast was hij ook erg serieus als het over de projecten ging. Hij had altijd wel een idee over hoe we het konden aanpakken en geen aanpak wat de moeilijk voor hem en anders vroeg hij op tijd hulp. Ik denk dat we enorm veel aan hem hadden tijden de minor. Als we hem een taak gaven dan was hij er meestal snel mee klaar.

Sefa: Ook een gezellige jongen, fijn om mee samen te werken. Hij had nog geen ervaring met Python, maar dat heeft hij goed opgepakt in de eerste paar weken. Maar ik merkte wel dat hij soms moeite had met de groep bijhouden qua kennis, wat niet erg is. Op zulke moment vroeg hij dan om uitleg en blijf doorvragen tot hij het snapte. Ik denk dat hij grote stappen heeft gemaakt tijdens de minor op de gebieden van Machine Learning en neurale netwerken en ik denk dat hij trots mag zijn op wat hij heeft bereikt.

| STARR | Uitleg |
| --- | --- |
| S | Er moest een taakverdeling gemaakt worden, dit gebeurde elke vergadering. |
| T | Mijn taak als voorzitter is een taakverdeling maken waarmee iedereen het eens is. Daarnaast moet het ook duidelijk zijn wie wat moet gaan doen en wanneer het af moet zijn. |
| A | Mijn aanpak begin altijd al tijdens het maken van een agenda, daar zet ik al de nieuwe taken op die besproken moeten worden. Tijdens de vergadering zelf bespreken we de voortgang van de taken van iedereen. Aan het eind van de vergadering staat er altijd het punt taakverdeling op de agenda. Eerst bespreken welke taken er allemaal zijn, en daarna kan iedereen zijn voorkeur aangeven voor een taak. Vaak laat zich als eerst horen Martti, daarna ik als ik een voorkeur heb en vervolgens zeggen Eric en Jesse dat ze een bepaalde taak wel op zich kunnen nemen. De taken staan dan nog niet vast, want ik vraag dan eerst aan de rest van de groep of zijn het er mee eens zijn of de persoon met de voorkeur die taak gaat doen. Hierna geeft Sefa vaak ook aan wat hij zou willen doen. Als ik geen voorkeur had dan is dit het moment dat ik aangeeft dat ik nog geen taak had. Ook heeft Ayrton nog geen taak op dit moment, maar dat geeft hij niet aan. Ik moet dan specifiek vragen aan hem wat hij graag zou willen doen, zijn antwoord is dan meestal: Het maakt mij niet zo veel uit. Daardoor krijgt hij vaak de taken waar niemand echt zin in heeft of hij wordt bij iemand anders bij een taak gezet zodat ze er samen aan kunnen werken. Hier na vraag ik aan de groep of het zo duidelijk is en of er nog aanpassingen nodig zijn. Daarna bespreken we als groep per taak wanneer het af moet zijn, hierbij geeft de persoon met deze taak aan wanneer hij het af kan hebben en vaak wordt dat dan de deadline. |
| R | Hierdoor hebben we een taakverdeling waarbij iedereen een taak heeft en de duidelijk wanneer het af moet zijn. |
| R | Ik denk dat ik het zo goed gaat en dat ik het volgende keer weer zo zou aanpakken. Mogelijk zal ik er de volgende keer opletten dat iedereen wel eens een andere soort taak doet dan altijd, bijvoorbeeld niet alleen programmeertaken maar ook literatuuronderzoek. |

[Terug naar de inhoud](#inhoud)

# Onderzoek naar het projec

## Definiëren van de taken

### Foodboost

Voor het Foodboost project wilden we een voor mensen met een notenallergie een aanbeveling maken. We kwamen er snel achter dat een aanbeveling voor alle maaltijden en snacks erg veel zou zijn. Daarom hebben we gekozen om alleen een aanbeveling te doen voor de lunch en het diner. Om te kunnen controleren of aanbevelingen variërend zijn moet de aanbeveling meer dan één lunch- en diner recept bevatten en dus langer dan één dag zijn. Daarom hebben we gekozen dat de aanbeveling een menu van een week lang is. 

Naast de notenallergie wilden we ook rekening houden met de aanbevolen dagelijkse calorieën. Eerst wilden we de aanbevolen dagelijkse calorieën apart voor lunch en diner gebruiken voor het menu. Maar we kwamen er achter dat er dan minder mogelijkheden zijn. Ook bedachten we dat als een lunch wat minder calorieën heeft en het diner wat meer, dat dat ook nog goed is of andersom. Zolang het totaal maar rond de som van de aanbevolen dagelijkse calorieën voor lunch en diner is. 

Voor dit project hebben we een hoofdvraag en deelvragen opgesteld:

---
**Met welke methode(s) kunnen we een wekelijks menu voor lunch en diner, rekening houdend met een noten allergie en het gemiddeld aantal aanvaardbare calorieën, aanbevelen?**

1. Welke ingrediënten bevatten noten?
2. Hoeveel is de aanbevolen dagelijkse calorieën voor lunch en diner samen? 
3. Welke methode kan gebruikt worden om te voorspellen of iemand een recept lekker vindt?
4. Welke methode kan gebruikt worden voor een weekmenu met zo veel mogelijk variatie?

---

[Terug naar de inhoud](#inhoud)

### Container

De opdrachtgever van het container project is Cofano. De vraag van hen was hoe de containers met zo min mogelijk stappen van een schip naar de kade en dan naar een ander schip verplaatst kunnen worden. Dat zijn veel verschillende onderdelen om rekening mee te houden. Daarom hebben wij specifiek gekeken naar het uitladingsdeel van het probleem: een container vanaf het schip op de kade neerzetten. Ook houden we rekening met welk schip de container weer mee moet; de prioriteit. De prioriteit is een nummer en hoe lager het nummer hoe sneller de container weer op het volgende schip moet worden gezet. 

Toen we de lay-out van de kade zagen wisten we meteen dat we die niet gingen gebruiken omdat er enorm veel containers zijn. Om een model te maken is het makkelijker om klein te beginnen. Daardoor maakte we onze eigen kade opstelling en eigen restricties daarvan. De containers zelf hebben ook restricties waar we rekening meer willen houden. 

Nadat we onze kade opstelling hadden gemaakt was het probleem nog steeds groot door de verschillende vervoersmiddelen die containers kunnen verplaatsten. Wij hebben er voor gekozen om één reachstacker te gebruiken. Ook vullen we de kade met containers die van één schip komen. 

Ook voor dit project hebben we hoofdvraag en deelvragen opgesteld: 

---
**Met welke methode(s) kunnen we het uitladingsdeel van het Container Stacking Probleem oplossen, gebruik makend van één reachstacker en één schip met een random lading?**

1.	Welke methoden zijn mogelijk bij het Container Stacking Probleem?  
2.	Wat is een move en wat zijn de restricties? 
3.	Welke containers zijn er en welke gaan we gebruiken?
4.	Hoe is de haven ingericht?
5.	Hoe kunnen we de container data simuleren? 

---

[Terug naar de inhoud](#inhoud)

## Evaluatie

### Foodboost

Als iemand verdergaat met ons Foodboost project dan zijn er een aantal punten die een beter model kunnen opleveren. Zoals een ander model dan een Logistic Regression, een Decision Tree Classifier of een K- nearest Neighbors Classifier gebruiken. Want dit is een relatief makkelijk model en mogelijk zijn er andere (ingewikkeldere) modellen die het beter doen om een voorspelling te maken of iemand een recept wel of niet lekker vindt. 

Daarnaast is het handig om de data die we hebben gegenereerd te balanceren. Voor deze data hebben we een groepsgenoot laten aangeven of hij de honderd recepten wel of niet lekker vond met een 0 of 1. Later bleek dat hij veel meer recepten wel lekker vond dan niet lekker. Door dit meer te balanceren is een model eerder geneigd om meer naar de input van het model zelf te kijken dan alle recepten als lekker te voorspellen omdat dat voor de meeste recepten geldt. 

Bij Lineair Programmeren andere restricties op de calorieën zetten. Dit kan zowel door een minimum en een maximum aantal calorieën per dag te zetten zodat de verspreiding van de calorieën van het weekmenu meer gelijk wordt. Of door te zeggen dat iemand maximaal 1040 X 7 calorieën mag eten in een week, met een minimum per dag, zodat er meer variatie mogelijk is tussen de recepten. Als iemand dan iets minder calorieën eet op een dag en op een andere dag wat meer, dan komt het gemiddeld aantal calorieën per dag nog steeds overeen met het aantal aanvaardbare calorieën per dag voor lunch en diner. 

[Terug naar de inhoud](#inhoud)

### Container
  
Bij het container project zijn er ook een aantal punten waaraan gedacht kan worden om onze oplossing te verbeteren of uit te bereiden. Bijvoorbeeld het aantal container per prioriteit op het schip als input geven aan ons model, wat tot betere resultaten kan leiden. Nu heeft het model als input de prioriteit van de huidige container en de huidige opstelling van de kade (state). Ook kan het model niet één container als input hebben maar meerdere containers, zodat de agent de beste container kan kiezen om die neer te zetten op de kade. Dit lijkt meer op de realiteit bij het uitladen van schip kunnen de containers in verschillende volgordes van het schip af.  

Andere en/of meerdere vervoersmiddelen gebruiken om het meer op de werkelijkheid te laten lijken. In ons model gebruiken we één reachstacker maar in de haven van Rotterdam maken ze bijvoorbeeld ook gebruik van kranen om de containers te verplaatsen. Andere vervoersmiddelen kunnen container dan soms ook vanaf boven oppakken waardoor er meer mogelijkheden zijn om container te plaatsen. 

De kade uitbreiden naar een werkelijke opstelling van een haven, hiermee kan onderzocht worden of ons model ook voor zo’n grote kade werkt. 
Tijdens het uitladen van een schip rekening houden met het evenwicht van het schip. Een uitbereiding daarvan is de containers zelf een gewicht geven. In de realiteit zijn niet alle containers even zwaar beladen en sommige zijn ook leeg. Dit levert ook meer restricties op tijdens het stapelen van de containers. 

[Terug naar de inhoud](#inhoud)

## Conclusies

### Foodboost

Met welke methode(s) kunnen we een wekelijks menu voor lunch en diner, rekening houdend met een noten allergie en het gemiddeld aantal aanvaardbare calorieën, aanbevelen?

1. **Welke ingrediënten bevatten noten?**

Om de ingrediënten te vinden die noten bevatten hebben we eerst gekeken welke noten, waar mensen met notenallergie allergisch voor zijn, er allemaal zijn. Om de recepten te vinden die geen noten bevatten hebben we voor elk ingrediënt van het recept gekeken of er minimaal één noot, uit de notenlijst, in voorkwam of niet. Die recepten die een ingrediënt hebben met noten hebben we weg gefilterd. Toen we die lijst zagen, kwamen we er achter dat de recepten met nootmuskaat en kokosnoot ook weg waren gefilterd maar dat hoeft niet. Daar hebben we het filteren op aangepast. 

Dus de ingrediënten die noten bevatten zijn de ingrediënten die het volgende bevatten:

<details>
  <summary>De notenlijst</summary>
  
  - noot
  - pinda
  - eikel
  - amandel
  - cashew
  - hazelno
  - hican
  - hickory
  - kemirie
  - macadamia
  - nangaino
  - parano
  - pecan
  - pistache
  - kastanje
  - walnoot
  - betelno
  - beukenno
  
</details>

Maar ze bevatten niet:

<details>
  <summary>Delen die de ingrediënten met noten niet bevatten</summary>
  
  - Muskaat
  - peper
  - kokos
  
</details>

2. **Hoeveel is aanbevolen dagelijkse calorieën voor lunch en diner samen?**

Hiervoor heb ik eerst literatuuronderzoek gedaan naar het aantal aanbevolen calorieën voor lunch en diner. De resultaten ik samen met Jesse verwerkt tot een boxplot en twee histogrammen:

<details>
  <summary>Lunch en diner kcal boxplot en histogrammen</summary>
  <img src="Afbeeldingen/Statistiek op calorieën1.png" />
  <img src="Afbeeldingen/Statistiek%20op%20calorieën2.png" />
  <img src="Afbeeldingen/Statistiek%20op%20calorieën3.png" />
</details>

Op basis van de histogrammen en boxplot hebben we bepaald dan het diner maximaal 570 calorieën moet bevatten en de lunch 470 calorieën. Samen is dat 1040 calorieën, voor meer uitleg zie paragraaf [Calorieën](#Calorieën).

3. **Welke methode kan gebruikt worden om te voorspellen of iemand een recept lekker vindt?**

Om te bepalen welke methode het beste is om te voorspellen of iemand een recept lekker vindt of niet hebben we drie modellen met elkaar vergeleken: Logistic Regression, Decision Tree Classifier en K- nearest Neighbors Classifier. Voor de vergelijking hebben we de metrieken recall, precision, accuracy en de f1 score berekend. Voor het voorspellen of iemand een recept lekker vindt, kijken we vooral naar de metriek precision. Want precision geeft aan hoeveel van voorspelde lekkere recepten de persoon ook echt lekker vindt. Het nadeel hiervan is dat de persoon hier door misschien minder recepten aangeraden wordt maar de kans is dan wel groter dat de aangeraden recepten ook echt lekker zijn. 

<details>
  <summary>Modellen vergelijken</summary>
  <img src="/Afbeeldingen/modellen%20vergelijken%20lekker%20voorspellen.png" />
</details>

Uit de tabel hierboven blijkt dat de Decision Tree Classifier het hoogst van de drie modellen scoort op precision. Daarom is de Decision Tree Classifier van de drie methodes de best om te voorspellen of iemand een recept lekker vindt of niet. 

4.  **Welke methode kan gebruikt worden voor een weekmenu met zo veel mogelijk variatie?**

Om de recepten zonder noten die alleen een lunch of diner zijn om te zetten naar een weekmenu, rekening houdend met variatie hebben we Lineair Programmeren gebruikt. De libary die we hebben gebruikt is ortools.linear_solver. De restricties hier van zijn:
-	Elke dag staat er één lunch en één diner op het menu
-	Elke dag staan er maximaal 1040 calorieën op het menu 
-	Elk recept mag maar één keer voorkomen tijdens de week

Op basis van deze restricties wordt er een week menu gemaakt waarbij de calorieën gemaximaliseerd worden. Een voorbeeld van een weekmenu en de verdeling van de calorieën:

<details>
  <summary>Weekmenu</summary>
  <img src="/Afbeeldingen/weekmenu.png" />
</details>

<details>
  <summary>Verspreiding van de calorieën per week</summary>
  <img src="/Afbeeldingen/weekmenu%20calorieen.png" />
</details>

[Terug naar de inhoud](#inhoud)

### Container

Met welke methode(s) kunnen we het uitladingsdeel van het Container Stacking Probleem oplossen, gebruik makend van één reachstacker en één schip met een random lading?

1. **Welke methoden zijn mogelijk bij het Container Stacking Probleem?**

Voor het oplossen van dit probleem hebben Reinforcement Learning gebruikt, specifiek het Deep Q-Network algoritme. De agent vult steeds de kade (het environment) opnieuw en krijgt een beloning of straf voor wat hij doet, daar leert het model van. 

Ook kan het probleem opgelost worden met Lineair Programmeren of andere Operations Research algoritmes of heuristieken. 

2. **Wat is een move en wat zijn de restricties?**

Een move is een container oppakken en ergens anders weer neerzetten. Er zijn vijf restricties daaraan: 
- Een container mag geplaatst worden op een plaats waar al een container staat want dat is niet mogelijk.

  <details>
    <summary>Afbeelding restrictie 1</summary>
    <img src="/Afbeeldingen/Restrictie1.png" />
  </details>

- Een container mag niet geplaatste worden als er geen container onder zit. Dan zweeft de container en dat is niet mogelijk.

  <details>
    <summary>Afbeelding restrictie 2</summary>
    <img src="/Afbeeldingen/Restrictie2.png" />
  </details>

- Een container mag niet op een stapel geplaatst worden die al de maximale hoogte heeft bereikt. De maximale hoogte is vijf containers hoog. Deze regel is er voor de veiligheid.

  <details>
    <summary>Afbeelding restrictie 3</summary>
    <img src="/Afbeeldingen/Restrictie3.png" />
  </details>

- Een container mag niet buiten de gebieden voor containers staan. Dit is wederom voor de veiligheid.

  <details>
    <summary>Afbeelding restrictie 4</summary>
    <img src="/Afbeeldingen/Restrictie4.png" />
  </details>

- Een container mag niet tussen twee stapels worden geplaats via de korte kant van de container. Dit is omdat een reachstacker een container alleen van de lange kant kan oppakken. Als er dan twee stapels van containers aan beide lange kanten van die plek al staan dan kan de container er niet tussen gezet worden. 

  <details>
    <summary>Afbeelding restrictie 5</summary>
    <img src="/Afbeeldingen/Restrictie5.png" />
  </details>

3. **Welke containers zijn er en welke gaan we gebruiken?**

Er zijn veel verschillende soorten containers. De meest gebruikte zijn die van 20 en 40 feet. We hadden gekozen voor de 20ft container maar later hebben we het niet gebruikt omdat de containers in ons model altijd dezelfde afmetingen hebben. 

4. **Hoe is de haven ingericht?**

Van Cofano, de opdrachtgever, hebben we drie satellietbeelden gekregen van de kade:

  <details>
    <summary>Satelliet aanzichten van de kades</summary>
    <img src="/Afbeeldingen/kade%20alles.png" />
  </details>

Ook hebben we kaarten gekregen met iets meer informatie over de indeling van de kade.

  <details>
    <summary>Kaarten van de kade</summary>
    <img src="/Afbeeldingen/indeling%20kade.png" />
    <img src="/Afbeeldingen/indeling%20kade2.png" />
  </details>

Op deze beelden staan enorm veel containers, om de kade klein te houden hebben we zelf een kade bedacht. Die kade is vier containers breed, vier lang en vijf hoog. Vijf containers hoog omdat dat het maximale aantal op elkaar te zetten container is. Vier breed en vier lang zodat er ook containers tussen andere containers neergezet kunnen worden, zodat het meer op de werkelijkheid lijkt. Ook is dat omdat het model dan getraind wordt ervan uitgaande dat een container alleen vanaf de lange kant opgepakt en neergezet kan worden door een reachstacker.

Dus we hebben uiteindelijk niks gedaan met de informatie op de kade die we van Cofano hadden gekregen.

5. **Hoe kunnen we de container data simuleren?**

Zelf heb ik code geschreven die drie verschillende soorten schepen willekeurig indeelt met containers. Per container is het bekend op welk schip hij staat, op welke plek hij zich op datzelfde schip bevind en welke prioriteit de container heeft. Voor meer informatie, zie paragraaf [Scheepsdata simuleren](#Scheepsdata-simuleren).

Bij ons Reinforcement model hebben we de data gesimuleerd door een lijst te maken, met daarin de volgorde hoe de containers van het schip af gaan. In die lijst staan de prioriteiten van de containers. Deze lijst is willekeuring gegenereerd. 

[Terug naar de inhoud](#inhoud)

## Planning 

### Foodboost
Voor het Foodboost project hebben we een Trello bord gemaakt als groep zijnde. Elke vergadering opende we dit bord en bespraken we de voortang en knelpunten van deze taken. Dan was ook het moment dat we we ook nieuwe taken toevoegden als dat nodig was. Het bord vergaten we wel eens, maar tijdens de vergadering bespraken we altijd de voortgang van de taken en nieuwe taken/deadlines voor de volgende vergadering. Dat was soms ook: ga door met waar je nu mee bezig bent. Door deze vergaderingen was het duidelijk waar iedereen mee bezig was en wisten we de vervolgstappen.

<details>
  <summary>Trello bord Foodboost</summary>
  <img src="/Afbeeldingen/Trello1.png" />
</details>

[Terug naar de inhoud](#inhoud)

### Container

Aan het begin van het container project wilden we echt een planning. Die heb ik toen samen met Jesse gemaakt. Hoe verder we ons in het project doken hoe meer we er achter kwamen dat de planning niet realistisch was. Ook hadden we van tevoren een aanpak bedacht die we later niet gebruikten omdat er andere beter waren. De projectplanning staat hieronder als afbeelding, voor een duidelijkere weergave: [Projectplanning](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/Projectplanning.xlsx) als een MS Excel bestand want als PDF bestand is het niet goed leesbaar.

<details>
  <summary>Projectplanning Container</summary>
  <img src="/Afbeeldingen/Projectplanning.png" />
</details>

Voor dit project hebben we ook een Trello bord gemaakt. Wederom hebben we dit een paar weken gebruikt en daarna niet meer. Maar door de vergaderingen hadden we een overzicht van wat iedereen aan het doen was. 

<details>
  <summary>Trello bord Containers</summary>
  <img src="/Afbeeldingen/Trello2.png" />
</details>

[Terug naar de inhoud](#inhoud)

# Voorspellende analyses

## Foodboost

Voor het Foodboost project heb ik het aantal gram vet geprobeerd te voorspellen. Dit heb ik gedaan met de nutritions dataset. Daar heb ik eerst een pivot tabel van gemaakt. Vervolgens heb ik die opgeschoond door de eenheden van de verschillen voedingsstoffen weggehaald, de eiwitten staan bijvoorbeeld als “2 g” (2 gram). Eerst heb ik de data gesplitst in een train- en een testset. Met de trainset heb ik de correlatie tussen vet en de andere voedingsstoffen berekend: 

| Voedingsstof | Correlatie met vet |
| --- | --- |
| Vezels | 0.1850 |
| Natrium  | 0.3032|
| Koolhydraten| 0.3002 |
| Energie | 0.8218 |
| Eiwit  | 0.5199 |

In de tabel is te zien dat vezels de minste correlatie heeft met vet en energie de meeste. Daarom heb ik twee modellen gemaakt om vet te voorspellen op basis van energie: Ridge en Lineaire Regressie. Ik heb deze modellen gekozen omdat zo wel de feature als de target variable numerieke waardes zijn.

Eerst heb ik gekeken of er uitschieters in de trainingset zitten. Daarvoor heb ik twee boxplotten gemaakt, weer een voor vet en een voor energie. Uit de boxplot met vet komen geen duidelijke uitschieters, maar in die van energie komt er een duidelijke uitschieter. Ik heb daarom gekeken welk recept de uitschieter was; Roggebrood met noten en bessen. Dat recept heeft de voedingswaardes van het hele brood in plaatst van per portie, zoals de andere recepten. Daarom heb ik dat recept uit de trainset gehaald. 

<details>
  <summary>Boxplotten vet en energie</summary>
  <img src="/Afbeeldingen/boxplot%20vet.png" />
  <img src="/Afbeeldingen/boxplot%20energie.png" />
</details>

Voor de Lineaire Regressie heb ik eerste gekeken op de data normaal verdeeld was of niet. Daarvoor heb ik twee histogrammen gemaakt; een voor vet en een voor energie. 

<details>
  <summary>Histogrammen vet en energie</summary>
  <img src="/Afbeeldingen/hist%20vet%201.png" />
  <img src="/Afbeeldingen/hist%20energie%201.png" />
</details>

Uit beide histogrammen blijkt dat dat ze allebei niet normaal verdeeld zijn. Daarom heb ik van de waardes de wortelgetrokken. Uit de nieuwe histogrammen blijkt dat de voedingsstoffen daardoor meer normaal verdeeld zijn dan eerst. 

<details>
  <summary>Histogrammen vet en energie na het normaliseren</summary>
  <img src="/Afbeeldingen/hist%20vet%202.png" />
  <img src="/Afbeeldingen/hist%20energie%202.png" />
</details>

Het worteltrekken heb ik ook de testset gedaan. Hierna heb ik de trainset gesplitst en het lineaire regressie model gemaakt en getraind. Vervolgens heb ik met de testset een voorspelling gemaakt. Om te kunnen beredeneren hoe goed het model is, moeten de waardes weer gekwadrateerd worden. Daarna heb ik de voorspelde waardes vergeleken met de originele vetwaardes met een R2-score. 

Als input van het Ridge model heb ik dezelfde trainset gebruikt als voor Lineaire Regressie, maar niet genormaliseerd. Daarna heb ik het model op getraind. Met het getrainde model heb ik de vetwaardes voorspeld op basis van de originele energie waardes. Met een R2-score heb ik weer de originele vetwaardes vergeleken met de voorspelde waarden uit het model.

Om beide modellen te kunnen vergelijken heb ik de volgende tabel gemaakt:

| Model| R2-score |
| --- | --- |
| Ridge | 0.6588 |
| Lineaire Regressie | 0.6617|

De R2 scores van het Ridge en het Lineaire regressie model liggen erg dichtbij elkaar. Maar het lineaire regressie model is net een klein beetje beter. 

De hele code staat in dit [notebook](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Notebooks/Ridge%20en%20lineaire%20regressie%20Foodboost(1).ipynb).

[Terug naar de inhoud](#inhoud)

## Container
https://towardsdatascience.com/deep-q-learning-tutorial-mindqn-2a4c855abffc

Voor het container probleem heb ik Reinforcement Learning gebruikt omdat er geen beste uitkomst bestaat. Dat is omdat het niet duidelijk is wat de beste oplossing is. Daarnaast is er ook niet echt data over, waardoor dit geen Supervised of Unsupervised Learning is. Bij Reinforcement Learning genereert het model zelf data door spelletjes te spelen. Met de die data leert het model. In mijn geval is een spelletje één keer een kade van drie breed bij drie lang bij één hoog vullen. 

Voor mijn Reinforcement model heb ik een Deep Q-Network gebruikt. Hiervoor heb ik eerst een environment en een agent gemaakt. Daarnaast heb ik de controles gemaakt die controleren of een move mag of niet. Voor deze controles wordt het platte speelbord vervormt naar een driedimensionale matrix.

Mijn environment heeft een discrete action space want er zijn maar negen plekken om een container neer te zetten. In de step wordt een container aan het speelveld toegevoegd als dat mag, daarvoor krijgt de agent een reward van 1. Als de container niet wordt toegevoegd aan het speelveld, omdat dat niet mag, dan krijgt de agent een reward van -1. Als de laatste container wordt toegevoegd aan het speelveld dan krijgt de agent een bonus van 10. De episode is afgelopen als de kade volstaat of als er te veel pogingen zijn gedaan om de container te plaatsen. 

Als resultaat uit het model heb ik een learning curve gemaakt met daarin de maximale score en de mediaan en het maximum van de games. In de plot is duidelijk te zien dat de blauwe lijn het hardste omhoog gaat, maar de mediaan (oranje) is de lijn waar ik het meest naar kijk, want dat is de meest voorkomende waarde per 100 games. Het is  duidelijk te zien dat die lijn ook het maximum bereikt bij ongeveer 1100 games.

<details>
  <summary>Reinforcement learning curve</summary>
  <img src="Afbeeldingen/RL%203x3x1.png" />
</details>

Mijn de hele code van het Reinforcement Learning staat in dit [notebook](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Notebooks/RL%20Joanne.ipynb).

[Terug naar de inhoud](#inhoud)

# Domeinkennis

## Introductie

### Foodboost 

Het foodboost project behoort tot de zorg- en welzijn sector en dan specifiek eten en diëten. Ook behoort het tot Data Science. De recepten die we gebruiken komen van Allerhande en zullen daardoor al gecontroleerd zijn op de eetbaarheid van de recepten. Wij hebben als groep de recepten daaruit gefilterd die geen noten bevatten want ons model genereerd recepten voor mensen die allergisch voor noten zijn. Dat is een risico want het kan erge gevolgen hebben als we een recept aanraden waar toch noten inzitten. Daarnaast zijn er geen strikte regels in deze sectoren. Het ergste wat kan gebeuren is dat ons model een recept aanraadt die de gebruiker niet lekker vindt. 

### Container 
Het container project behoort tot de transport en logistieke sector. Hierbij gelden veel regels. Wij houden vooral rekening met de regels over het stapelen van containers. Zo mag een stapel van containers bijvoorbeeld niet hoger zijn dan vijf containers. Ook mogen containers niet worden neergezet buiten de toebedeelde plekken. Deze regels en vele andere zijn er voor de veiligheid. Tijdens dit project hebben we het probleem moeten versimpelen maar toch kijken we voor elke oplossing of het ook echt kan in de werkelijkheid. Het doel van dit project was om een indeling op de kade te vinden waarbij de containers zo efficiënt mogelijk op de kade worden neergezet, rekening houdend met dat de containers ook weer makkelijk op een andere schepen gezet moeten worden. Het voordeel hiervan is dat schepen minder lang stil aan de kade hoeven te liggen, wat geld kost. 

[Terug naar de inhoud](#inhoud)

## Literatuuronderzoek

### Foodboost
```diff
-   bestanden/ videos 
```
### Container
- [A decision support system for managing combinatorial problems in container terminals](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/A%20decision%20support%20system%20for%20managing%20combinatorial%20problems%20in%20container%20terminals.pdf)
- [An optimization model for the container pre-marshalling problem](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/An%20optimization%20model%20for%20the%20container%20pre-marshalling%20problem.pdf)
- [Two-stage search algorithm for the inbound container unloading and stacking problem](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/Two-stage%20search%20algorithm%20for%20the%20inbound%20container%20unloading%20and%20stacking%20problem.pdf)

[Terug naar de inhoud](#inhoud)

## Terminologie 

```diff
-meer begrippen
```

### Foodboost
- Allergie: Als iemand in aanraking komt met een bepaalde stof en daarop een reactie krijgt (overgevoeligheid).
- Calorie: Hoeveel energie het eten bevat.
- Kcal: Eenheid die de hoeveelheid energie aangeeft. 1 kcal = 1000 calorieën
- Lineair programmeren: Een wiskundige manier om de beste uitkomst te berekenen. 
- Pivot tabel: Een draaitabel; een tabel wordt vervormd: de unieke waardes uit een bepaalde kolom worden de nieuwe kolomnamen, een andere kolom wordt de index. 
- Tag: label; omschrijft tot welke categorie een gerecht behoort.
- Lineair Programmeren?

### Container
- Reinforcement Learing:
- Stack: Een stapel containers.
- Yard: 
- Agent:
- Envoirment: De ruimte waard
- Learning rate: De mate/snelheid waarin de agent leert.
- Move: Een container oppakken en ergens anders weer neerzetten.
- Episode: 
- Prioriteit: Een cijfer dat aangeeft met welk schip de container weer mee moet. Hoe lager, hoog sneller dat schip vertrekt
- Trachstacker: 
- Container Stacking Probleem: 
- State: De huidige status van de kade/ speelveld

[Terug naar de inhoud](#inhoud)

# Data voorbereiding

Ik heb zowel voor het Foodboost project als het Container project de data bekeken en voorbereid. 

## Foodboost

### Calorieën
Samen met Jesse had ik de taak om de maximale calorieën te bepalen voor zowel de lunch en diner. Daarvoor had ik eerst literatuuronderzoek gedaan naar de aanbevolen aantal calorieën. Met deze resultaten hebben we een boxplot gemaakt om zo de verdeling te zien. In de boxplot is te zien dat de lunch twee uitschieters heeft en het diner geen. 

<details>
  <summary>Lunch en dinner kcal boxplot</summary>
  <img src="Afbeeldingen/Statistiek op calorieën1.png" />
</details>

Ook hebben we een histogram gemaakt en de mediaan en het gemiddelde berekend voor het diner en de lunch. Uit de histogram van de lunch komt dat de meeste bronnen zeggen dat de lunch tussen de 435 en de 515 calorieën moet bevatten. Tussen de 500 en 570 calorieën moet het diner bevatten zeggen de meeste bronnen. 

<details>
  <summary>Lunch en dinner kcal histogrammen</summary>
  <img src="Afbeeldingen/Statistiek%20op%20calorieën2.png" />
  <img src="Afbeeldingen/Statistiek%20op%20calorieën3.png" />
</details>

Op basis van deze gegevens hebben we bepaald dat het diner maximaal 570 calorieën mag zijn, dit komt overeen met de mediaan. En de lunch mag 470 calorieën bevatten, dat komt overeen met het gemiddelde. In het project zijn we verder gegaan met 1040 calorieën voor het diner en lunch samen, zodat er meer mogelijkheden zijn.

Het [notebook](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Notebooks/Statistiek%20op%20calorie%C3%ABn.ipynb) met de code. 

### Data voorbereiden

De data voor het voorspellen of iemand een recept lekker vindt of niet heb ik gemaakt. Dat word gedaan op basis van de ingrediënten van een recept. De recepten zonder noten van de lunch en diner werden alleen meegenomen. 

Van de ingrediënten heb ik een pivot tabel gemaakt, dat waren in totaal 7204 verschillende ingrediënten. Sommige ingrediënten lijken erg veel op elkaar bijvoorbeeld zwarte-peperkorrel en zwarte-peperkorrels. Met Fuzzywuzzy heb ik de verschillende ingrediënten met elkaar vergeleken. Als de token_sort_ratio hoog genoeg was, voegde ik de twee kolommen samen. Daarna waren er nog 6774 verschillende ingrediënten over. Niet elk ingrediënt kwam vaak voor. Om overfitten tegen te gaan hadden was als groep besloten om alleen ingrediënten mee te nemen die in 40 of meer recepten voorkomen. Daarmee hadden we nog 167 ingrediënten over. 

Het [notebook](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Notebooks/Stap%202%20Data%20voorbereiden.ipynb) met de code. 

[Terug naar de inhoud](#inhoud)

## Container

### Onderzoek naar de datasets
De aangereikte datasets van Colfano heb ik onderzocht. Ik heb per kolom in de datasets bekeken welke waardes er in voorkwamen en of we de kolom mogelijk nodig hebben. De resultaten heb ik onder elkaar gezet in een [MS Word bestand](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/onderzoekdataset%20containers.pdf). De blauw gemarkeerde kolommen in het bestand hadden we waarschijnlijk niet nodig als we de datasets zouden gebruiken. De rood gemarkeerde kolommen hebben geen waardes, alleen NaN's of minder dan 5 ingevulde waardes en daarnaast alleen NaN's of overal dezelfde waardes.

### Scheepsdata simuleren

Bij de haven komen boten aan, maar daar hadden we nog geen data voor. Mijn taak was het om deze data te simuleren. Ik had daar voor drie verschillende boten gekozen: de Alphenaar, de Bokkenboot en een Pinker. Op deze boten kunnen een verschillend aantal containers. De containers kunnen een prioriteit van 1, 2 of 3 hebben. Doormiddel van mijn code is het gemakkelijk om een willekeruig aantal volle boten te simuleren en dus ook de containers daar op. Elke container krijgt een random plaats op het schip en een random prioriteit. In deze [code](Notebooks/Simulated%20data%20schepen%20en%20containers.ipynb) wordt er random één boot gesimuleerd.

<details>
  <summary>Schip simulatie</summary>
  <img src="Afbeeldingen/schip%20simulatie.png" />
</details>
 
[Terug naar de inhoud](#inhoud)

# Communicatie
## Presentaties

Tijdens de minor heb ik verschillende presentaties voorbereid en gegeven, de presentaties: 
- [Week 2 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/Foodproject%20week%202.pdf).
- [Week 4 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/Voortgang%20food%20project%20week%204.pdf) 
- [Week 6 - eindpresentatie](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/food%20project%20week%206.pdf).
- [Week 8 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/container%20-%20week%208.pdf).
- [Week 14 - eindpresentatie](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/container%20-%20eindpresentatie%20week%2014.pdf).

## Paper 

Voordat we aan de paper konden beginnen hadden we een opzet nodig van de hoofdstukken en wat er in deze hoofdstukken moest. Daar had ik een klein onderzoekje naar gedaan. Dat had ik tijdens een vergadering met een docent besproken. En vervolgens hadden we de paper verdeeld in stukjes, zodat iedereen een stuk schreef. Ik had de inleiding toebedeeld gekregen. Nadat iedereen zijn stukje afhad, kreeg iedereen weer een ander stuk van de paper die hij moest controleren. Ik had het stukje toekomstig werk gekregen. Daar was nog veel aan te doen want het waren nog bulletpoints en de grammatica was nog niet goed genoeg, daardoor moest ik het hele stuk herschrijven. Ook heb ik de hele paper doorgelezen een aangepast waar nodig. De uiteindelijke stijl van de paper heb ik gedaan met behulp van MS Word. 

We hadden de paper naar twee docenten gestuurd voor feedback, een deel van die feedback heb ik verwerkt. Daarnaast heb ik de stukjes van andere gecontroleerd op aanleiding van de feedback en aangepast waar nodig, om een zo goed mogelijke paper op te leveren.

De uiteindelijke paper staat [hier](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/Paper%20Groep%205%20Cofano%20Containers%20(1).pdf). 

[Terug naar de inhoud](#inhoud)

# Overige dingen


[Terug naar de inhoud](#inhoud)
