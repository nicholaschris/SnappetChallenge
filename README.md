## Requirements
- Python 3.x
- virtualenv

- Save csv as database

## Installation
    git clone SnappetChallenge
    cd SnappetChallenge
    virtualenv --no-site-packages -p python3 env  
    pip install -r requirements.txt  
    cd snappet_challenge
    python manage.py migrate
    python manage.py runserver
    view at http://127.0.0.1:8000/work/


# SnappetChallenge
At [Snappet](http://www.snappet.org), we care about data and we care about code. When we interview for development positions, we want to see code and we want to discuss code. That's why we want candidates to show some work on our challenge. This challenge is not meant to cost you tons of time. A few hours should be enough. The challenge is defined very broadly. You could spend weeks on it, or half an hour. We understand that in 2 hours, you can only do so much. Don't worry about completeness, work on something that works and shows your skills.

### Language
From the next paragraph on, this challenge is worded in Dutch. Snappet is a Dutch organisation. We are present in several European countries and part of our development team is based in Russia, but still, most of the organisation is Dutch. We all speak English, standups, code and documentation are in English, but being able to operate in a Dutch environment is a required skill. So use whatever tools you can to make sense of the rest of the challenge if you are not a Dutch speaker. It is part of the exercise. :)

### De opdracht
In deze repository vind je een folder Data met daarin work.csv en work.json. Beiden bevatten dezelfde data, je hoeft er maar één te gebruiken (wat jij handig vindt). In dit bestand zitten de werkresultaten van de kinderen in één klas over een maand. 

Maak een rapport of scherm of wat ook dat een leerkracht een overzicht geeft van hoe zijn klas vandaag heeft gewerkt en waaraan. Het is nu dinsdag 2015-03-24 11:30:00 UTC. De antwoorden van na dat tijdstip worden dus nog niet getoond.

Maak een pull request aan waarin je in ieder geval een readme hebt opgenomen die uitlegt wat je moet doen om het resultaat te kunnen bekijken.

### Achtergrond informatie
- Alle tijden zijn in UTC
- Er is een attribuut Progress. Dit geeft de verandering in de inschatting van de vaardigheid van de leerling op een leerdoel. Daar zitten psychometrische modellen achter die rekening houden met de moeilijkheid van de opgave, of de opgave al eerder door deze leerling is gemaakt, etc. Er zijn meerdere situaties waarbij de Progress 0 is. Bijvoorbeeld als we nog geen goede calibratie van de moeilijkheid van de opgave hebben. Of als de leerling nog te weinig opgaven in een leerdoel heeft gemaakt om een goede schatting van de vaardigheid te maken.
- Aangezien deze dataset alleen wijzigingen laat zien en geen absolute waarde, kan je aan deze dataset niet zien wat de vaardigheid van iedere leerling is. Dat hoeft ook niet in de resultaten terug te komen.

### Vrijheid
Deze opdracht is expres ruim geformuleerd. Je mag de technieken en tools gebruiken die je het liefst gebruikt. Je mag je tijd besteden aan de aspecten die je zelf het belangrijkst vindt. Er is geen tijd om alles te doen: maak een keuze. Bij Snappet werken we met C#, .NET, Javascript, JQuery en Knockout.JS. Maar we denken dat een goede programmeur op een ander platform zich dat snel genoeg eigen maakt. 
Je mag frameworks en libraries gebruiken. Je mag de data in een ander formaat omzetten of importeren in databases. Dan wel in de readme uitleggen hoe een ander het werkend kan krijgen.
De minimale requirement in de opdracht is "waar heeft mijn klas vandaag aan gewerkt". Dat kan in een lijstje, in een grafisch vorm, het kan als getallen of kleuren. Je kan het vergelijken met vorige week of een gemiddelde score. Probeer te bedenken wat voor een leerkracht in de klas het belangrijkst is.

## Translation

### The Assigment/Task

In this repository you will find a Data folder containing work.csv en work.json. Both contain the same data; you only have to use one (the one you prefer). Herein you will find one months work result of the kids in one class.

Make a rapport or a screen or whatever gives a teacher an oversight of how his class worked today, and on what. Today is Tuesday, 2015-03-24 11:30:00 UTC. The answers from after this time & date should not be shown (are not yet shown?). 

Make a pull request in which you at least incorporate a readme that explains what you have to do to view the results.

### Background Information

- All times are in UTC
- There is an attribute Progress. This shows the change in estimation of the pupils’ability of a learning aim. There are psychometric models behind this that take into account the difficulty of the task, whether the task has previously been performed by this student, etc. There are multiple situations in which the Progress is 0. For example if we do not have a good calibration of the difficulty of the task. Or if the pupil has not completed enough task in a certain learning-area to make a good estimation of the pupils skills.
- Because this dataset only shows changes, and not absolute values, you cannot see the skills of each individual pupil. This does not have to show in the results.

### Freedom
This task has purposefully been formulated with room for interpretation. You may use the techniques and tools that are most preferable to you. You may spend time on the aspects that you view to be the most important. There is not enough time to do everything: make choices. At Snappet, we work with C#, .NET, Javascript, JQuery en Knockout.JS. But we believe that a good programmer of another platform will find his way around these in no time. You may use frameworks and libraries. You may convert date in another format or import it in databases. But then you must explain in the readme how to get it working. The minimal requirement in the task is "what did my class work on today". You can show this in a list, in graphic form (graphs?), as numbers or with colours. You can compare it with the previous week or the average score. Try to imagine what is the most important & beneficial for the teacher of the class.