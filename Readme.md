# Proposal for Semester Project


<!-- 
Please render a pdf version of this Markdown document with the command below (in your bash terminal) and push this file to Github

quarto render Readme.md --to pdf
-->

**Patterns & Trends in Environmental Data / Computational Movement
Analysis Geo 880**

| Semester:      | FS23                                     |
|:---------------|:---------------------------------------- |
| **Data:**      | What type of data are you focussing on? Bewegungsdaten von menschlicher Aktivität  |
| **Title:**     | "Predicting Transportation Choices Based on Road Conditions and Weather: An Analysis of Individual Travel Behavior"
Deutsch: "Vorhersage der Verkehrsmittelwahl anhand von Straßenbedingungen und Wetter: Eine Analyse des individuellen Reiseverhaltens"               |
| **Student 1:** | Pfister Nadja                        |
| **Student 2:** | Martig Serafin                         |

## Abstract 
<!-- (50-60 words) -->

## Research Questions
<!-- (50-60 words) -->

## Results / products
<!-- What do you expect, anticipate? -->

Weiter könnten wir ein Modell erstellen / Wahrscheilnlichkeiten berechnen bei welcher Termperatur, bei welchem wetter oder auf welcher Strassen eine Person welches Verkehrsmittel benutzt. 

## Data
<!-- What data will you use? 
Movement Data from Google Maps and GPS from human travel activities.
Will you require additional context data? 
Ja, Wetterdaten von Meteoschweiz: Niederschlag, Durchschnittstemperatur am Reisetag.
Daten über Strassen-, Wegnetz von Openstreetmap.

Where do you get this data from? 
Meteschweiz 
Openstreetmap Strassennetz
Kartenlayer

Do you already have all the data? -->
Movement Data ja
Meteodaten, Streetmap Daten. wurden noch nicht eingeholt. 


## Analytical concepts
<!-- Which analytical concepts will you use? What conceptual movement spaces and respective modelling approaches of trajectories will you be using? What additional spatial analysis methods will you be using? -->

Auswerten der Bewegungsdaten. Geschwindigkeit berechnen über Steps und Zeit. Visualisierung der Geschwindigkeit über die Zeit oder nach Standort. 
Visualisierung des Bewegungsverlaufs.
Visualisierung der Temperatur an einem bestimmten Standort (hohe Temp = rot, tief = blau) 
Visualisieurng der Durchschnittsgeschwindigkeit auf einem Strassenabschnitt

Nadja?

## R concepts
<!-- Which R concepts, functions, packages will you mainly use. What additional spatial analysis methods will you be using? -->
Packages: tidyr, dplyr, ggplot, lubridate, sf, readr.
Wird hier andere Programme wie QGis oder ArcGis gemeint?


## Risk analysis
<!-- What could be the biggest challenges/problems you might face? What is your plan B? -->
Nicht erhalten der Wetterdaten in der benötigten lokalen/hohen Auflösung. Fehlende Wetterstationen. Lösung: Wetterdaten der Gemeinde, Kantone, Region oder Nationale Wetterdaten verwenden.  
Das Zusammenführen von Metadaten (Wetter, Strassen) mit unserem GPS Punkten. 
Abweichung der GPS Punkte von den jeweiligen Strassen. Fehlende GPS Werte. Plan B: Datenpunkte Extra- und Interpolieren. 


Plan B: andere Daten verwenden. Nicht diejenigen von GoogleMaps. 

Weitere Schwierigkeiten: Handhabung von Ausreisser. 

## Questions? 
<!-- Which questions would you like to discuss at the coaching session? -->
Welche Modelle verwenden wir für die Analyse? 
Wir wollen anhand der mittleren Reisegeschwindigkeit, Zeit (in der Nacht fahren keine Züge) und der Strasse vorhersagen, welches Verkehrsmittel benutzt worden ist. Welche Kategorien an Geschwindigkeiten sollen wir verwende?
Wenn eine Person mit dem Auto fährt, dann parkiert und dann zu Fuss einkaufen geht, sollen diesen kurze Wege zu Fuss separat analysieren. Resp. welche Auflösung sollen wir verwenden? 
Welcher und wie viele Zeiträume sollen wir anschauen? 1 Tag, 2 Tage, 1 Monat?


