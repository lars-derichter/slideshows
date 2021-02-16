# Use case beschrijvingen

(Analyse & UML – Lars De Richter – Thomas More)

---

## Use case diagram en use case beschrijvingen

- Use case diagram: lijst functionele eisen
- Use case beschrijvingen: details hoe de functionaliteit moet verlopen

Notes:

- Documentatie in tekstvorm (scenariobeschrijving) eventueel aangevuld met schermontwerpen (prototypes), activiteitendiagrammen of sequentiediagrammen

---

## Soorten use case beschrijvingen

- Brief use case
- Casual use case
- Fully dressed use case
- Fowler style use case

---

### Brief use case

- 1 paragraaf
- enkel successcenario

Notes:

- Kan bijv. als samenvatting in een spreadsheet gebruikt worden waarbij in de andere kolommen andere details als prioriteit en deadlines kunnen komen.
- Welk van de voorbeelden voor de ATM past hierbij? -> het tweede

---

### Casual use case

- ‘Cockburn Casual Style’
- enkele paragrafen
- meerdere scenario’s (alternatieven, uitzonderingen)
- voor kleinere teams/niet-kritische projecten

Notes:

- Welk van de voorbeelden past hierbij? -> het eerste
- Is zeker in een vroge fase vaak goed genoeg. Verdere details zijn vaak pas nodig wanneer er werkelijk aan deze use case gewerkt wordt.

---

### Fully dressed use case

- ‘Cockburn Style’
- formeel document
- gedetailleerde, vaste structuur
- velden voor verschillende secties
- grote teams/grote, kritische projecten

Notes:

- Welk van de voorbeelden past hierbij? -> het vierde
- De exacte vorm zal van bedrijf tot bedrijf verschillen, maar binnen één bedrijf of project wordt steeds dezelfde template gebruikt.

---

### Fowler style

- Martin Fowler: ‘There is no standard way to write the content of a use case, and different formats work well in different cases.’
- Vereenvoudigde versie van Cockburns ‘Fully dressed’ template.
- Tussen fully-dressed en casual in.

Notes:

- Welk voorbeeld past hier het best bij volgens jou? -> het derde
- Wij zullen voor grotere projecten een stijl gebruiken die hierop gebaseerd is.
- Veel detail, maar toch flexibel en wendbaar genoeg om in ‘agile’ projecten en omgevingen te gebruiken.

---

## Structuur ‘Fowler style’

- Naam
- Functionaliteit
- Actoren
- (Aannamen)
- Normaal verloop
- (Alternatieven/Uitzonderingen)
- Resultaat

---

### Naam

Spreekt voor zich. De naam van de use case.

---

### Functionaliteit

Beschrijf de functionaliteit in de vorm van een user story.

Notes:

- Op user stories komen we later nog uitgebreid terug.
- Als <rol> wil ik <functionele eis/use case> kunnen, zodat <beoogd resultaat>.
- Bijv.: Als klant wil ik mijn saldo kunnen consulteren, zodat ik weet hoeveel ik nog beschikbaar heb op mijn zichtrekening.

---

### Actoren

Lijst van alle actoren die betrokken zijn bij de use case

---

### Aannamen

- Alles wat je aanneemt bij de uitvoering van het scenario.
- Alles wat vooraf aanwezig is.

bijv. ‘de administrator is aangemeld’

Notes:

- Wat zou een aanname zijn die ons scenario fel zou vereenvoudigen? (Dat de klant de juist pincode ingeeft)

---

### Normaal verloop

- het normale/ideale verloop van het scenario
- in een ideale wereld zonder fouten/problemen/onverwachte situaties
- ‘gouden scenario’

Notes:

- Bij het beschrijven van een scenario is het het eenvoudigst als je eerst uitgaat van een ideale wereld waarin alles verloopt zoals je als ontwikkelaar zou willen.
- Uiteraard ga je in je analyse ook al rekening houden met alternatieve wegen en zelfs worst-case scenario’s, maar daarvoor heb je de volgende stap.

---

### Alternatieven/uitzonderingen

Hier hou je rekening met andere input/keuzes van de actor en met te voorziene fouten.

---

### Resultaat

Een korte omschrijving van het gewenste resultaat van een use case

Notes:

- Nog maar eens: als een use case op zichzelf geen gewenst resultaat heeft voor de gebruiker, is het geen op zichzelf staande use case, maar hooguit een stap (of een paar stappen) in het scenario van een grotere use case.
- Soms is het toch gemakkelijker om stappen die vaak gebundeld terug komen samen te documenteren in een apart document met dezelfde structuur en ernaar te verwijzen vanuit h-je use cases. Voor welk onderdeel van onze use case zou dat bijv. wenselijk zijn? (foute pincode; kaart niet snel genoeg uitnemen)

---

## Template

Je vindt een template voor MS Word op Canvas.

---

## Bibliografie

- Unknown. (unknown date). _Fully Dressed Example: Process Sale in a POS System._ Retrieved February 16, 2020, from http://suraj.lums.edu.pk/~cs463s04/Use%20case%20POS.pdf

---

- Verboven, Michiel. (2019). _Analyse. Eisenanalyse en UML._ [presentatie].

---

- Wikipedia. (2020)._Use case._ Retrieved February 16, 2020, from https://en.wikipedia.org/wiki/Use_case

---

## Licentie

Deze slides werden gemaakt door [Lars De Richter](mailto:lars.derichter@thomasmore.be) voor het Graduaat Programmeren aan [Thomas More.](http://thomasmore.be)

Beschikbaar onder de volgende Creative Commons licentie: [Naamsvermelding-NietCommercieel-GelijkDelen 4.0 Internationaal (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.nl).
