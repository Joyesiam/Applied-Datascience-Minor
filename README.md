# Applied-Datascience-Minor
Student: Joanne Pals  
Studentennummer: 20189186
https://markdownlivepreview.com/
https://datascience.hhs.nl:8888/user/20189176/notebooks/ads5/FoodBoost%20eerste%206%20weken/Stap%205%20Lp%20model%20v3.ipynb

[title](link)
- container project met of zonder hoofdletter?
- koppen grootte
# hoofdstuk titel 
## sub onderdeel hoofdstuk
### sub sub onderdeel

- naar elk bestand/ plaatje verwijzen

# Inhoud
- [Obligatory criteria](#Obligatory-criteria)  
  - [DataCamp](#DataCamp)
  - [Reflectie](#Reflectie)
- [Research project](#Research-project)
  - [Task definition](#Task-definition)
  - [Evaluatie](#Evaluatie)
  - [Conclusies](#Conclusies)
  - [Planning](#Planning)
- [Predictive Analytics](#Predictive-Analytics)
  - [Container](#Container)
- [Domain knowledge](#Domain-knowledge)
  - [Introduction](#Introduction)
  - [Literatuuronderzoek](#Literatuuronderzoek)
  - [Terminologie](#Terminologie)
- [Data preprocessing](#Data-preprocessing)
  - [Foodboost](#Foodboost)
  - [Container](#Container)
- [Communication](#Communication)
  - [Presentaties](#Presentaties)
  - [Paper](#Paper)
- [Overige dingen](#Overige-dingen)


# Obligatory criteria
## DataCamp
![DataCamp](/Afbeeldingen/DataCamp.png "This is a sample image.")

## Reflectie 
### Mine contribution to the project

| STARR| Uitleg |
| S| --- |
| T| List all *new or modified* files |
| A| Show file differences that **haven't been** staged |
| R| --- |
| R| --- |


### Own learning objectives
bla
### Evaluation on the group project as a whole
bla
## Research project

## Task definition

### Foodboost

Voor het Foodboost project wilden we een voor mensen met een notenallergie een aanbeveling maken. We kwamen er snel acht dat een aanbeveling voor alle maaltijden en snacks erg veel zou zijn. Daarom hebben we gekozen om alleen een aanbeveling te doen voor de lunch en het diner. Om te kunnen controleren of aanbevelingen variërend zijn moet de aanbeveling meer dan één lunch- en diner recept bevatten en dus langer dan één dag zijn. Daarom hebben we gekozen dat de aanbeveling een menu van een week lang. 

Naast de notenallergie wilden we ook rekening houden met de aanbevolen dagelijkse calorieën. Eerst wilden we de aanbevolen dagelijkse calorieën apart voor lunch en diner gebruiken voor het menu. Maar we kwamen er achter dat er dan minder mogelijkheden zijn. Ook bedachten we dat als een lunch wat minder calorieën heeft en het diner wat meer, dat dat ook nog goed is of andersom. Zolang het totaal maar rond de som van de aanbevolen dagelijkse calorieën voor lunch en diner is. 

Voor dit project hebben we een hoofdvraag en deelvragen opgesteld:

---
**Met welke methode(s) kunnen we een wekelijks menu voor lunch en diner, rekening houdend met een noten allergie en het gemiddeld aantal aanvaardbare calorieën, aanbevelen?**

1. Welke ingrediënten bevat noten?
2. Hoeveel is aanbevolen dagelijkse calorieën voor lunch en diner samen? 
3. Welke methode kan gebruikt worden om te voorspellen of iemand een recept lekker vindt?
4. Welke methode kan gebruikt worden voor een weekmenu met zo veel mogelijk variatie?

---

### Container

De opdracht gever van het container project is Cofano. De vraag van hen was hoe de containers zo met zo min mogelijk stappen van het ene schip naar de kade en dan naar het andere schip verplaatst kunnen worden. Dat zijn veel verschillende onderdelen om rekening mee te houden. Daarom hebben wij specifiek gekeken naar het uitladingsdeel van het probleem: een container van af het schip op de kade neerzetten. Ook houden we rekening met welk schip de container weer mee moet, de prioriteit. De prioriteit is een nummer en hoe lager het nummer hoe sneller de container weer op het volgende schip moet worden gezet. 

Toen we de lay-out van de kade zagen wisten we meteen dan we die niet gingen gebruiken omdat enorm veel containers zijn. Om een model te maken is het makkelijker om klein te beginnen. Daardoor maakte we onze eigen kade opstelling en eigen restricties daarvan. De containers zelf hebben ook restricties waar we rekening meer willen houden. 

Na dat we onze kade opstelling hadden gemaakt was het probleem nog steeds groot door de verschillende vervoersmiddelen die containers kunnen verplaatsten. Wij hebben er voor gekomen om één reachstacker te gebruiken. Ook vullen we de kade met container die van één schip komen. 

Ook voor dit project hebben we hoofdvraag en deelvragen opgesteld: 

---
**Met welke methode(s) kunnen we het uitladingsdeel van het Container Stacking Probleem oplossen, gebruik makend van één reachstacker en één schip met een random lading?**

1.	Welke methoden zijn mogelijk bij het Container Stacking Probleem?  
2.	Wat is een move en wat zijn de restricties? 
3.	Welke containers zijn er en welke gaan we gebruiken?
4.	Hoe is de haven ingericht en wat zijn de restricties?
5.	Hoe kunnen we de container data simuleren? 

---

## Evaluatie

### Foodboost

Als iemand verdergaat met ons Foodboost project dan zijn er een aantal punten die een beter model kunnen opleveren. Zoals een ander model dan een Logistic Regression, een Decision Tree Classifier of een K- nearest Neighbors Classifier gebruiken. Want dit een relatief makkelijk model en mogelijk zijn er andere (ingewikkeldere) modellen die het beter doen om een voorspelling te maken of iemand een recept wel of niet lekker vindt. 

Daarnaast is het handig om de data die we hebben gegeneerd te balanceren. Voor deze data hebben we een groepsgenoot laten aangeven of hij de honderd recepten wel of niet lekker vond met een 0 of 1. Later bleek dat hij veel meer recepten wel lekker vond dan niet lekken. Door dit meer te balanceren is een model eerder geneigd om meer naar de input van het model zelf te kijken dan alle recepten als lekker te voorspellen omdat dat voor de meeste recepten geldt. 

Bij Lineair Programmeren andere restricties op de calorieën zetten. Dit kan zowel door een minimum en een maximum aantal calorieën per dag te zetten zodat de verspreiding van de calorieën van het weekmenu meer gelijk wordt. Of door te zeggen dat iemand maximaal 1040 X 7 calorieën mag eten in een week, met een minimum per dag, zodat er meer variatie mogelijk is tussen de recepten. Als iemand dan iets minder calorieën eet op een dag en op een andere dag wat meer, dan komt het gemiddeld aantal calorieën per dag nog steeds overeen met het aantal aanvaardbare calorieën per dag voor lunch en diner. 

### Container
  
Bij het container project zijn er ook een aantal punten waaraan gedacht kan worden om onze oplossing te verbeteren of uit te bereiden. Bijvoorbeeld het aantal container per prioriteit op het schip als input geven aan ons model, wat tot betere resultaten kan leiden. Nu heeft het model als input de prioriteit van de huidige container en de huidige opstelling van de kade (state). Ook kan het model niet één container als input hebben maar meerdere containers, zodat de agent de beste container kan kiezen om die neer te zetten op de kade. Dit lijkt meer op de realiteit bij het uitladen van schip kunnen de containers in verschillende volgordes van het schip af.  

Andere en/of meerdere vervoersmiddelen gebruiken om het meer op de werkelijkheid te laten lijken. In ons model gebruiken we één reachstacker maar in de have van Rotterdam maken ze bijvoorbeeld ook gebruik van kranen om de containers te verplaatsen. Andere vervoersmiddelen kunnen container dan soms ook vanaf boven oppakken waardoor er meer mogelijkheden zijn om container te plaatsen. 

De kade uitbreiden naar een werkelijke opstelling van een haven, hiermee kan onderzocht worden of ons model ook voor zo’n grote kade werkt. 
Tijdens het uitladen van een schip rekening houden met het evenwicht van het schip. Een uitbereiding daarvan is de containers zelf een gewicht geven. In de realiteit zijn niet alle containers even zwaar beladen en sommige zijn ook leeg. Dit levert ook meer restricties op tijdens het stapelen van de containers. 

## Conclusies

### Foodboost

Met welke methode(s) kunnen we een wekelijks menu voor lunch en diner, rekening houdend met een noten allergie en het gemiddeld aantal aanvaardbare calorieën, aanbevelen?

1. **Welke ingrediënten bevat noten?**

Om de ingrediënten te vinden die noten bevatten hebben we eerst gekeken welke noten, waar mensen met notenallergie allergisch voor zijn, er allemaal zijn. Om de recepten te vinden die geen noten bevatten hebben voor elk ingrediënt van het recept gekeken of er minimaal één noot in voorkwam of niet. Die recepten die een ingrediënt hebben met noten hebben we weg gefilterd. Toen we die lijst zagen, kwamen we er achter dat de recepten met nootmuskaat en kokosnoot ook weg waren gefilterd maar dat hoeft niet. Daarom hebben we het filteren op aangepast. 

Dus de ingrediënten die noten bevatten zijn de ingrediënten die het volgende bevatten:

<details>
  <summary>Woorden die de ingrediënten met noten bevatten</summary>
  
  - Noot
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

1040, voor meer uitleg zie paragraaf [Calorieën](#Calorieën).

```diff
- meer uitleg?
```

3. **Welke methode kan gebruikt worden om te voorspellen of iemand een recept lekker vindt?**

Om te bepalen welke methode het beste is om te voorspellen of iemand een recept lekker vindt of niet hebben we drie modellen met elkaar vergeleken: Logistic Regression, Decision Tree Classifier en K- nearest Neighbors Classifier. Voor de vergelijking hebben we de metrieken recall, precision, accuracy en de f1 score berekend. Voor het voorspellen of iemand een recept lekker vindt kijken we vooral naar de metriek precision. Want precision geeft aan hoeveel van voorspeelde lekkere recepten de persoon ook echt lekker vindt. Het nadeel hiervan is dat de persoon hier door misschien minder recepten aangeraden wordt maar de kans is dan wel groter dat de aangeraden recepten ook echt lekker zijn. 

<details>
  <summary>Modellen vergelijken</summary>
  <img src="/Afbeeldingen/modellen%20vergelijken%20lekker%20voorspellen.png" />
</details>

De Decision Tree Classifier scoort het hoogst van de drie modellen op precision. Daarom is de Decision Tree Classifier van de drie methodes de best om te voorspellen of iemand een recept lekker vindt of niet. 

4.  **Welke methode kan gebruikt worden voor een weekmenu met zo veel mogelijk variatie?**

Om de recepten zonder noten die alleen een lunch of diner zijn om te zetten naar een weekmenu, rekening houdend met variatie hebben we Lineair Programmeren gebruikt. De libary die we hebben gebruikt is ortools.linear_solver. De restricties hier van zijn:
-	Elke dag staat er één lunch en één diner op het menu
-	Elke dag staat er maximaal 1040 calorieën op het menu 
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

### Container

Met welke methode(s) kunnen we het uitladingsdeel van het Container Stacking Probleem oplossen, gebruik makend van één reachstacker en één schip met een random lading?

1. **Welke methoden zijn mogelijk bij het Container Stacking Probleem?**

Voor het oplossen van dit probleem hebben Reinforcement Learning gebruikt. Het Deep Q-Network algoritme. De agent vult steeds de kade (het environment) opnieuw en    krijgt steeds een beloning of straf voor wat hij doet, daar leert het model van. 

Ook kan het probleem opgelost met lineair programmeren of andere operations research algoritmes of heuristieken. 

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

- Een container mag niet op een stapel geplaatste worden die al de maximale hoogte heeft bereikt. De maximale hoogte is vijf containers hoog. De regel is er voor de veiligheid.

  <details>
    <summary>Afbeelding restrictie 3</summary>
    <img src="/Afbeeldingen/Restrictie3.png" />
  </details>

- Een container mag niet buiten de gebieden voor containers staan. Dit is wederom voor de veiligheid.

  <details>
    <summary>Afbeelding restrictie 4</summary>
    <img src="/Afbeeldingen/Restrictie4.png" />
  </details>

- Een container mag niet tussen twee stapel worden geplaats via de korte kant van de container. Dit is omdat een reachstacker een container alleen van de lange kant kan oppakken. Als er dan twee stapels van containers aan beide lange kanten van die plek al staat dan kan de container er niet tussen gezet worden. 

  <details>
    <summary>Afbeelding restrictie 5</summary>
    <img src="/Afbeeldingen/Restrictie5.png" />
  </details>

3. **Welke containers zijn er en welke gaan we gebruiken?**

Er zijn veel verschillende soorten containers. De meest gebruikte zijn die van 20 en 40 feet. We hadden gekozen voor de 20ft container maar later hebben we het niet gebruikt omdat de containers in ons model altijd dezelfde afmetingen hebben. 

4. **Hoe is de haven ingericht en wat zijn de restricties?**

Van Cofano, de opdrachtgever, hebben drie sataliet beelden gekregen van de kade:

  <details>
    <summary>Sataliet aanzichten van de kades</summary>
    <img src="/Afbeeldingen/kade%20alles.png" />
  </details>

Ook hebben we kaarten gekregen met iets meer informatie over de indeling van de kade.

  <details>
    <summary>Kaarten van de kade</summary>
    <img src="/Afbeeldingen/indeling%20kade.png" />
    <img src="/Afbeeldingen/indeling%20kade2.png" />
  </details>

Op deze beelden staan enorm veel containers, om de kade klein te houden hebben we zelf een kade bedacht. Die kade is vier containers breed, vier lang en vijf hoog. Vijf containers hoog omdat dat het maximale aantal op elkaar te zetten container is. Vier breed en vier lang zodat er ook containers tussen andere containers neergezet kunnen worden, zodat het meer op de werkelijkheid lijkt. Ook is dat omdat het model dan getraind wordt er van uitgaande dat een container alleen vanaf de lange kant opgepakt en neergezet kan worden door de reachstacker.

Dus we hebben uiteindelijk niks gedaan met de informatie op de kade die we van Cofano hadden gekregen.

5. **Hoe kunnen we de container data simuleren?**

Zelf heb ik code geschreven die drie verschillende soorten schepen willekeurig indeelt met containers. Per container is het bekend op welk schip hij staat, op welke plek hij zich op datzelfde schip bevind en welke prioriteit de container heeft. Voor meer informatie, zie paragraaf [Scheepsdata simuleren](#Scheepsdata-simuleren).

Bij ons Reinforcement model hebben we de data gesimuleerd door een lijst te maken, met daarin de volgorde hoe de containers van het schip af gaan. In die lijst staan de prioriteiten van de containers. Deze lijst is willekeuring gegenereerd. 

## Planning 

### Foodboost
Voor het Foodboost project hebben we een Trello board gemaakt als groep zijnde. Elke vergadering opende we dit board en bespraken we de voortang en knelpunten van deze taken. Dan voegde we ook nieuwe taken toe als dat nodig was. Het board vergaten we wel eens, maar tijdens de vergadering bespraken we altijd de voortgang van de taken en een nieuwe taken/ deadline voor de volgende vergadering. Dat was soms ook ga door met waar je nu mee bezig bent. Door deze vergaderingen was het duidelijk waar iedereen mee bezig was en wisten we de vervolgstappen.

<details>
  <summary>Trello board Foodboost</summary>
  <img src="/Afbeeldingen/Trello1.png" />
</details>

### Container

Aan het begin van het container project wilden we echt een planning. Die heb ik toen samen met Jesse gemaakt. Hoe verder we ons in het project doken hoe meer we er achter kwamen dat de planning niet realistisch was. Ook hadden we van tevoren een aanpak bedacht die we later niet gebruikten omdat er andere beter waren. De projectplanning staat hieronder als afbeelding, voor een duidelijkere weergave: [Projectplanning](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/Projectplanning.xlsx) als een MS Excel bestand want als PDF bestand is het niet leesbaar.

<details>
  <summary>Projectplanning Container</summary>
  <img src="/Afbeeldingen/Projectplanning.png" />
</details>

Voor dit project hebben we ook een Trello board gemaakt. Wederom hebben we dit een paar weken gebruikt en daarna niet meer. Maar door de vergaderingen hadden we overzicht over wat iedereen aan het doen was. 

<details>
  <summary>Trello board Containers</summary>
  <img src="/Afbeeldingen/Trello2.png" />
</details>

## Predictive Analytics
```diff
Foodboost
-	Waarom dit model -> literatuur
-	Trainen -> underfitten overfitting etc. 
-	Modellen vergelijken + evalueren 
-	Visualisatie 
```

### Container
https://towardsdatascience.com/deep-q-learning-tutorial-mindqn-2a4c855abffc

Voor het container probleem heb ik Reinforcement Learning gebruikt omdat er geen beste uitkomst bestaand. Dat is omdat het niet duidelijk is wat de beste oplossing is. Daarnaast is er ook niet echt data over, waardoor dit geen Supervised of Unsupervised Learning is. Bij Reinforcement Learning genereert het model zelf data door spelletjes te spelen. Met de die data leert het model zo. In mijn geval zijn is een spelletje één keer een kade van 3 breed bij 3 lang bij 1 hoog vullen. Het spelletje is afgelopen als de kade volstaat of dat de agent te veel pogingen nodig heeft om een container neer te zetten. 

Voor mijn Reinforcement model heb ik een Deep Q-Network gebruikt. Hiervoor heb ik eerste een environment en agent gemaakt. Daarnaast heb ik de controles gemaakt die controleren of een move mag of niet. Voor deze controles wordt het platte speelbord vervormt naar een driedimensionale matrix.

Mijn environment heeft een discrete action space. In de step wordt een container aan het speelveld toegevoegd als dat mag, daarvoor krijgt de agent een reward van 1. Als de container niet wordt toegevoegd aan het speelveld omdat dat niet mag dan krijgt de agent een reward van -1. Als de laatste container wordt toegevoegd aan het speelveld dan krijgt de agent een bonus van 10. De episode is afgelopen als de kade vol is of als er te veel pogingen zijn gedaan om de container te plaatsen. 

Als resultaat uit het model heb ik een learning curve gemaakt met daarin de maximale score en de mediaan van de score. In de plot is duidelijk te zien dat de maximale score het hardste omhoog gaat Maar de mediaan is de lijn waar ik het meest naar kijk, want dat is de meest voorkomende waarde per 100 games. Het is ook duidelijk te zien dan die lijn ook het maximum bereikt bij ongeveer 1100 games.

<details>
  <summary>Reinforcement learning curve</summary>
  <img src="Afbeeldingen/RL%203x3x1.png" />
</details>

Mijn de hele code van het Reinforcement Learning staat in dit [notebook](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Notebooks/RL%20Joanne.ipynb).

# Domain knowledge

## Introduction

### Foodboost 

Het foodboost project behoort tot de zorg- en welzijn sector en dan specifiek eten en diëten. Ook behoort het tot Data Science. De recepten die we gebruiken komen van Allerhande en zullen daardoor al gecontroleerd zijn op de eetbaarheid van de recepten. Wij hebben als groep de recepten daaruit gefilterd die geen noten bevatten want ons model genereerd recepten voor mensen die allergisch voor noten zijn. Dat is een risico want het kan erge gevolgen hebben als we een recept aanraden waar toch noten inzitten. Daarnaast zijn er geen strikte regels in deze sectoren. Het ergste wat kan gebeuren is dat ons model een recept aanraadt die de gebruiker niet lekker vindt. 

### Container 
Het container project behoort tot de Transport en logistiek sector. Hierbij gelden veel regels. Wij houden vooral rekening met de regels over het stapelen van containers. Zo mag een stapel van containers bijvoorbeeld niet hoger zijn dan vijf containers. Ook mogen containers niet worden neergezet buiten de toebedeelde plekken. Deze regels en vele andere zijn er voor de veiligheid. Tijdens dit project hebben we het probleem moeten versimpelen maar toch kijken we voor elke oplossing of het ook echt kan in de werkelijkheid. Het doel van dit project was om een indeling op de kade te vinden waarbij de containers zo efficiënt mogelijk op de kade worden neergezet, rekening houdend met dat de containers ook weer makkelijk op een andere schepen gezet moeten worden. Het voordeel hiervan is dat schepen minder lang stil aan de kade hoeven te liggen, wat geld kost. 

## Literatuuronderzoek

### Foodboost
```diff
-   bestanden/ videos 
```
### Container
- [A decision support system for managing combinatorial problems in container terminals](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/A%20decision%20support%20system%20for%20managing%20combinatorial%20problems%20in%20container%20terminals.pdf)
- [An optimization model for the container pre-marshalling problem](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/An%20optimization%20model%20for%20the%20container%20pre-marshalling%20problem.pdf)
- [Two-stage search algorithm for the inbound container unloading and stacking problem](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/Two-stage%20search%20algorithm%20for%20the%20inbound%20container%20unloading%20and%20stacking%20problem.pdf)

## Terminologie 

```diff
-meer begrippen
```

### Foodboost
- Allergie: Als iemand in aanraking komt een bepaalde stof en daarop een reactie krijgt (overgevoeligheid).
- Calorie: Hoeveel energie het eten bevat.
- Kcal: De eenheid die de hoeveelheid energie aangeeft. 1 kcal = 1000 calorieën
- Lineair programmeren: Een wiskundige manier om de beste uitkomst te berekenen. 
- Pivot tabel: Een draaitabel; een tabel wordt vervormd: de unieke waardes uit een bepaalde kolom worden de nieuwe kolomnamen, een andere kolom wordt de index. 
- Tag: label; omschrijft tot welke categorie een gerecht behoort.

### Container
- Reinforcement Learing:
- Stack: Een stapel containers.
- Yard: 
- Agent:
- Envoirment: De ruimte waard
- Learning rate: De mate/snelheid waarin de agent leert.
- Move: Een container oppakken en ergens anders weer neerzetten.
- Episode: 

# Data preprocessing

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

Op basis van deze gegevens hebben we bepaald dat het diner maximaal 570 calorieën mag zijn en de lunch 470 calorieën. In het project zijn we verder gegaan met 1040 calorieën voor het diner en lunch samen, zodat er meer mogelijkheden zijn. 

Het [notebook](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Notebooks/Statistiek%20op%20calorie%C3%ABn.ipynb) met de code. 

### Data voorbereiden
```diff
- to do: verschil oplossen in recepten
```
De data voor het voorspellen of iemand een recept lekker vindt of niet heb ik gemaakt. Dat werd gedaan op basis van de ingrediënten van een recept. De recepten zonder noten van de lunch en diner werden alleen meegenomen. 
Van de ingrediënten heb ik een pivot tabel gemaakt, dat waren in totaal 5100 verschillende ingrediënten. Sommige ingrediënten lijken erg veel op elkaar bijvoorbeeld zwarte-peperkorrel en zwarte-peperkorrels. Met Fuzzywuzzy heb ik de verschillende ingrediënten met elkaar vergeleken. Als de token_sort_ratio hoog genoeg was, voegde ik de twee kolommen samen. Daarna waren er nog 4797 verschillende ingrediënten over. Niet elk ingrediënt kwam vaak voor. Om overfitten tegen te gaan hadden was als groep besloten om alleen ingrediënten mee te nemen die in 40 of meer recepten voorkomen. Daarmee hadden we nog 166 ingrediënten over. 
Het [notebook](link) met de code. 

## Container

### Onderzoek naar de datasets
De aangereikte datasets van Colfano heb ik onderzocht. Ik heb per kolom in de datasets bekeken welke waardes er in voorkwamen en of we de kolom mogelijk nodig hebben. De resultaten heb ik onder elkaar gezet in een [MS Word bestand](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/onderzoekdataset%20containers.pdf). De blauw gemarkeerde kolommen in het bestand hadden we waarschijnlijk niet nodig als we de datasets zouden gebruiken. De rood gemarkeerde kolommen hebben geen waardes, alleen NaN's of minder dan 5 ingevulde waardes en daarnaast alleen NaN's of overal dezelfde waardes.

### Scheepsdata simuleren

Bij de haven komen boten aan, maar daar hadden we nog geen data voor. Mijn taak was het om deze data te simuleren. Ik had daar voor drie verschillende boten gekozen: de Alphenaar, de Bokkenboot en een Pinker. Op deze boten kunnen een verschillend aantal containers. De containers kunnen een prioriteit van 1, 2 of 3 hebben. Door middel van mijn code is het gemakkelijk om een random aantal volle boten te simuleren en dus ook de containers daar op. Elke container krijgt een random plaats op het schip en een random prioriteit. In deze [code](Notebooks/Simulated%20data%20schepen%20en%20containers.ipynb) wordt er random één boot gesimuleerd.

<details>
  <summary>Schip simulatie</summary>
  <img src="Afbeeldingen/schip%20simulatie.png" />
</details>

onderdelen
- Data exploration
- Data cleansing
- Data preparation
- Data explanation
- Data visualization (exploratory)
 
# Communication
## Presentaties
- [Week 2 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/Foodproject%20week%202.pdf).
- [Week 4 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/Voortgang%20food%20project%20week%204.pdf) 
- [Week 6 - eindpresentatie](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/food%20project%20week%206.pdf).
- [Week 8 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/container%20-%20week%208.pdf).
- [Week 14 - eindpresentatie](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/container%20-%20eindpresentatie%20week%2014.pdf).
## Paper 
Voordat we aan de paper konden beginnen hadden we een opzet nodig van de hoofdstukken en wat er in deze hoofdstukken moest. Daar had ik een klein onderzoekje naar gedaan. Dat had ik tijdens een vergadering met een docent besproken. En vervolgens hadden we de paper verdeeld in stukjes, zodat iedereen een stuk schreef. Ik had de inleiding toebedeeld gekregen. Nadat iedereen zijn stukje afhad, kreeg iedereen weer een ander stuk van de paper die hij moest controleren. Ik had het stukje toekomstig werk gekregen. Daar was nog veel aan te doen want het waren nog bulletpoints en de grammatica was nog niet goed genoeg, daardoor moest ik het hele stuk herschrijven. Ook heb ik de hele paper doorgelezen een aangepast waar nodig. De uiteindelijke stijl van de paper heb ik gedaan met behulp van MS Word. 
```diff
- In dit bestand staat mijn inleiding en eerdere versie en mijn versie van toekomstig werk. En de uiteindelijke paper staat hier. 
```

# Overige dingen
