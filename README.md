# Applied-Datascience-Minor
Student: Joanne Pals  
Studentennummer: 20189186
https://markdownlivepreview.com/

[title](link)

# Inhoud
- [Obligatory criteria](#Obligatory-criteria)  
  - [DataCamp](#DataCamp)
  - [Reflectie](#Reflectie)
- 1. [Research project](#Research-project)
  - iets
- 3. [Predictive Analytics](#Predictive-Analytics)
- 4. [Domain knowledge](#Domain-knowledge)
- 5. [Data preprocessing](#Data-preprocessing)
- 6. [Communication](#Communication)


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

## Data preprocessing

Ik heb zowel voor het Foodboost project als het Container project de data bekeken en voorbereid. 

### Foodboost

##### Calorieën
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

##### Data voorbereiden
De data voor het voorspellen of iemand een recept lekker vindt of niet heb ik gemaakt. Dat werd gedaan op basis van de ingredienten van een recept. Maar alleen de recepten van de lunch en diner zonder noten worden meegenomen. Van de ingredienten heb ik een pivot tabel gemaakt, dat waren in totaal 5100 verschillende ingredienten. Sommige ingredienten lijken erg veel op elkaar bijvoorbeeld zwarte-peperkorrel en zwarte-peperkorrels. Met fuzzywuzzy heb ik de verschillende ingredienten met elkaar vergeleken. Als de token_sort_ratio hoog genoeg was voegde ik de twee kolommen samen. Daarna waren er nog 4797 verschillende inrgedienten over. Niet elk ingredient kwam vaak voor. Als groep hadden we besloten om allen ingredienten mee te nemen die 40 kekeer of meer me te nemen 


- [Data voorbereiden](link)

### Container
- to do: verschil oplossen in recepten 
- [title](link)
- [Container dataset onderzoek](https://github.com/Joyesiam/Applied-Datascience-Minor/blob/main/PDF/onderzoekdataset%20containers.pdf)
- [Schepen simuleren](Notebooks/Simulated%20data%20schepen%20en%20containers.ipynb)

### Data exploration
### Data cleansing
### Data preparation
### Data visualization (exploratory)

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
