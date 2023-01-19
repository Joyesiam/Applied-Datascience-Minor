# Applied-Datascience-Minor
Student: Joanne Pals  
Studentennummer: 20189186
https://markdownlivepreview.com/

[title](link)

# Inhoud
- [Obligatory criteria](#Obligatory-criteria)  
  - [DataCamp](#DataCamp)
  - [Reflectie](#Reflectie)
- [Research project](#Research-project)
  - iets
- [Predictive Analytics](#Predictive-Analytics)
- [Domain knowledge](#Domain-knowledge)
- [Data preprocessing](#Data-preprocessing)
  - [Foodboost](#Foodboost)
  - [Container](#Container)
- [Communication](#Communication)
  - [Presentaties](#Presentaties)
  - [Paper](#Paper)


## Obligatory criteria
### DataCamp

![DataCamp](/Afbeeldingen/DataCamp.png "This is a sample image.")

### Reflectie 
#### Mine contribution to the project
bla
#### Own learning objectives
bla
#### Evaluation on the group project as a whole
bla
## Research project
literatuuronderzoek calorieen 
## Predictive Analytics
## Domain knowledge


#### Introduction
#### Literatuuronderzoek
#### Termologie 

```diff
-meer begrippen
```
##### Foodboost
- Allergie: Als iemand in aanraking komt een bepaalde stof en daarop een reactie krijgt (overgevoeligheid).
- Calorie: Hoeveel energie het eten bevat.
- Kcal: De eenheid die de hoeveelheid energie aangeeft. 1 kcal = 1000 calorieën
- Lineair programmeren: Een wiskundige manier om de beste uitkomst te berekenen. 
- Pivot tabel: Een draaitabel; een tabel wordt vervormd: de unieke waardes uit een bepaalde kolom worden de nieuwe kolomnamen, een andere kolom wordt de index. 
- Tag: label; omschrijft tot welke categorie een gerecht behoort.

##### Container
- Reinforcement Learing:
- Stack: Een stapel containers.
- Yard: 
- Agent:
- Envoirment: De ruimte waard
- Learning rate: De mate/snelheid waarin de agent leert.
- Move: Een container oppakken en ergens anders weer neerzetten.
- Episode: 

## Data preprocessing

Ik heb zowel voor het Foodboost project als het Container project de data bekeken en voorbereid. 

### Foodboost

#### Calorieën
Samen met Jesse had ik de taak om de maximale calorieën te bepalen voor zowel de lunch en diner. Daarvoor had ik eerst literatuuronderzoek gedaan naar de aanbevonden aantal calorieën. Met deze resultaten hebben we een boxplot gemaakt om zo de verdeling te zien. In de boxplot is te zijn dat de lunch twee uitschieters heeft en de diner er geen. 

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

Op basis van deze gevens hebben bepaald dat het diner maximaal 570 calorieën mag zijn en de lunch 470 calorieën. In het project zijn we verder gegaan met 1040 calorieën voor het diner en lunch samen, zodat er meer mogelijkheden zijn. 

Het [notebook](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Notebooks/Statistiek%20op%20calorie%C3%ABn.ipynb) met de code. 

#### Data voorbereiden
```diff
- to do: verschil oplossen in recepten
```

De data voor het voorspellen of iemand een recept lekker vindt of niet heb ik gemaakt. Dat werd gedaan op basis van de ingrediënten van een recept. De recepten zonder noten van de lunch en diner werden alleen meegenomen. 
Van de ingrediënten heb ik een pivot tabel gemaakt, dat waren in totaal 5100 verschillende ingrediënten. Sommige ingrediënten lijken erg veel op elkaar bijvoorbeeld zwarte-peperkorrel en zwarte-peperkorrels. Met fuzzywuzzy heb ik de verschillende ingrediënten met elkaar vergeleken. Als de token_sort_ratio hoog genoeg was voegde ik de twee kolommen samen. Daarna waren er nog 4797 verschillende ingrediënten over. Niet elk ingrediënt kwam vaak voor. Om overfitten tegen te gaan hadden was als groep besloten om alleen ingrediënten mee te nemen die in 40 of meer recepten voorkomen. Daarmee hadden we nog 166 ingrediënten over. 
Het [notebook](link) met de code. 

### Container

#### Onderzoek naar de datasets
De aangereikte datasets van Colfano heb ik onderzocht. Ik heb per kolom in de datasets bekeken welke waardes er in voorkwamen en of we de kolom mogelijk nodig hebben. De resultaten heb ik onder elkaar gezet in een [MS Word bestand](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/onderzoekdataset%20containers.pdf). De blauw gemarkeerde kolommen in het bestand hadden we waarschijnlijk niet nodig als we de datasets zouden gebruiken. De rood gemarkeerde kolommen hebben geen waardes, allen NaN's, minder dan 5 ingevulde waardes en daarnaast alleen NaN's of overal dezelfde waardes.

#### Scheepsdata simuleren

Bij de haven komen boten aan, maar daar hadden we nog geen data voor. Mijn taak was het om deze data te simuleren. Ik had daar voor drie verschillende boten gekozen: de Alphenaar, de Bokkenboot en een Pinker. Op deze boten kunnen een verschillend aantal containers. De containers kunnen een prioriteit van 1,2 of 3 hebben. Doormiddel van mijn code is het gemakkelijk om een random aantal volle boten te simuleren en dus ook de containers daar op. Elke container krijgt een random plaats op het schip en een random prioriteit. In deze [code](Notebooks/Simulated%20data%20schepen%20en%20containers.ipynb) wordt er random één boot gesimuleerd.

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

 
## Communication
### Presentaties
- [Week 2 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/Foodproject%20week%202.pdf).
- [Week 4 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/Voortgang%20food%20project%20week%204.pdf) 
- [Week 6 - eindpresentatie](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/food%20project%20week%206.pdf).
- [Week 8 - voortgang](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/container%20-%20week%208.pdf).
- [Week 14 - eindpresentatie](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/Presentaties/container%20-%20eindpresentatie%20week%2014.pdf).
### Paper 
```diff
- inleiding
```
