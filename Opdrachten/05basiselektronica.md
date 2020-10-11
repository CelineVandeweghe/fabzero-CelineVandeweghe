# Basis elektronica

## Opdracht

**Denk na over:**

- de voeding van je project
- de inputs (spanningsdelers of andere bescherming nodig?)
- de outputs (versterking nodig met mosfets, transistors of relais?)
- simuleer je berekende waarden


### Situering project

Mijn project is een gelasercut aapje uit hout en acrylaat. Bij het gezicht plaats ik een lampje dat door het acrylaat het gezicht oplicht.


### Voeding

Ik had graag met een kleine, gemakkelijk vervangbare batterij gewerkt. Zo kan mijn project gemakkelijker verplaatst worden.
Nl. een knoopcelbatterij van 3V


### Inputs

De elektronica is vrij klein in dit ontwerp, dus ik heb enkel een weerstand en een potentiometer nodig.


### Outputs

Output is een gele LED (warmer licht dan wit). Op het internet heb ik zo een LEDs gevonden (2,0V/10mA).


### Waarden

Ik vond het moeilijk om dit allemaal te berekenen. In theorie lukt het wel met de formules, maar dit voor een reële situatie uitzoeken, waar het nog een extra moeilijkheid is dat je zelf moet zoeken wat je allemaal nodig hebt, is echt moeilijk. Dus ik hoop dat het juist is.

R = (Uv - Uf) / If
R = (3V - 2,0V) / 0,01A
R = 1V / 0,01A
R = 100 Ω


### Tekening circuit

![Circuit]({{site.baseurl}}/assets/elek/Funky Trug.png)


## Aanvullingen

Bovenstaand ga ik uitvoeren als het volgende niet mogelijk is:
Met arduino had ik graag geprogrammeerd dat er drie verschillende ledjes (geel, rood en groen) kunnen branden. 
Er zouden twee settings zijn.
1. Het gele lichtje brandt en kan afgezet worden, na verloop van tijd gaat het vanzelf uit.
2. Ofwel brand het rode lichtje, ofwel het groene. Dit hangt af van hoe laat het is. Dit kan aan en afgezet worden. De uren kunnen ook aangepast worden.

Indien dit niet mogelijk is, ga ik het plan uitvoeren dat ik bij **opdracht** besproken heb.



