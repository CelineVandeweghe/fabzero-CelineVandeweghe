# Les 05: Basis elektronica

## Inleiding

De les begon een uurtje later (om 19u), tot 21u of 22u. 

Ik heb een basis elektriciteit, maar dat gaat niet echt verder dan de elektriciteit die aangeboden wordt in het secundair onderwijs. Dus ook tijdens deze les heb ik veel bijgeleerd. Ik maak een samenvatting van wat ik bijleerde.

Bruce heeft heel veel informatie gegeven. Het was een beetje overload voor mij, dus heb ik een deel weggelaten. Ik ben toch niet van plan om heel veel specialigheden van elektronica te gebruiken. De basis is dus goed.


## Basis

De basis van elektronica (fijner dan elektriciteit) is een stroombron, verbruiker en geleiders. Een weg en het werkt niet. Oef, dat wist ik gelukkig nog van vroeger

![Stroomkring](https://lh3.googleusercontent.com/proxy/xQoK7kU0H1y4KS_zYlAUaj0KsRH2oGpekxiHhJ2v2fAXBnFaSwZRP29b-jSmsYhthsnT9n8ayI56pYVf6iZ46NPTVfEYVPN4FsWBP89_Q5NPv0GuyXbLmNSdZZiSRsSwbg)

In theorie loopt de stroom van + naar -, maar in het echt van - naar +.


## Grootheden

### Weerstand

= elektrische eigenschap van materialen om de doorgang van elektrische stroom te belemmeren

**Grootheid** = weerstand
**Symbool** = R
**Eenheid** = Ohm
**Symbool**= Ω

![Tabel soortelijke weerstand](https://i.imgur.com/jwrPk3U.png)

Op een weerstand kan je zien hoeveel weerstand deze heeft aan de hand van de lijntjes in kleuren. Je kan dan opzoeken welke kleur voor welke woorde staat.

![Weerstand](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/3_Resistors.jpg/500px-3_Resistors.jpg)

Bij een open stroomkring is de weerstand eindoloos.


### Spanning

= het verschil in potentiële elektrische energie (elektrisch potentiaal verschil, vergelijkbaar met een bak water) tussen twee punten per eenheid van lading

**Grootheid** = spanning
**Symbool** = U
**Eenheid** = Volt
**Symbool**= V


### Stroom

= transport van elektrische lading.

**Grootheid** = stroom
**Symbool** = I
**Eenheid** = Ampère
**Symbool**= A


### Vermogen

= de snelheid waarbij elektrische energie wordt verplaatst

**Grootheid** = vermogen
**Symbool** = P
**Eenheid** = Watt
**Symbool**= W


### Formules

Wanneer je weet hoeveel spanning en vermogen er op een stroomkring staat, kan je berekenen hoeveel vermogen het is. En dit langs alle kanten (met stroom, spanning of vermogen als uitkomst).

Dit had ik al eerder geleerd, dus ik was er weer vlot mee weg.

![Formules](https://lh3.googleusercontent.com/proxy/D-Ajv9ua3Fpyg4agFd-yKGhJZvmm6EuG6gsOQuO7341eM8dD-6zA4jDPx6TurCNGQvzeuacei4uFR-PIdDAuAERvDrnFWSrA6vf3Q0PWjz4b_TA)


### Besluit

Als de spanning stijgt, dan stijgt de stroom.
Als de weerstand stijgt, dan daalt de stroom door de weerstand.
Als de stroom door de weerstand vergroot, dan stijgt de spanning over de weerstand.


## Apparatuur

### Voeding

Voeding geeft de spanning aan de schakeling. Er zijn voordelen aan geen batterijen gebruiken.

Wat kan je nog gebruiken?
Oude computers, adapters (best namaten met een multimeter en hun +/- pool, tip om multimeter tweedehands te kopen)


### Multimeter

De uitleg van de verschillende knoppen en standen heb ik niet genoteerd. Deze kan ik altijd terug opzoeken.

Het is belangrijk om in het achterhoofd te houden dat een multimeter slechts een momentopname maakt.

**Wat kan je meten?**
- Spanning
- Weerstand
- Stroom
- Diodes testen


### Oscilloscoop

Een **oscilloscoop** is een multimeter die een grafiek toont.


### Functiegenerator

Je kan een luidspreker koppelen aan een functiegenerator.


### Tips

- Fourier series applet
- Tinkercad -> circuits
- Sawwave


## Componenten 

### Weerstanden

Een weerstand bestaat uit twee geleidende buisjes in een lichtgevoeligde materie (LDR).
Weerstanden zijn warmtegevoelig. Als de temperatuur stijgt, dan daalt het aantal ohm.

**Noot**: een weerstand zet al zijn vermogen om in warmte

Toepassingen: flex (e-textiles)


### Bron

![bron](https://i.imgur.com/zrhCGJM.png)


### Schakelaars

Er zijn veel verschillende soorten schakelaars.
- Normaal open/gesloten
- Bistabiel / drukknop
- Meer polig
- Wisselschakelaar


### Spoel

Een spoel is een geïsoleerde koperdraad, gewikkeld rond een kern.
De spoel zorgt voor tegengestelde spanning en laat bijna geen stroom door. Bij een open schakeling zorgt de spoel er voor dat er toch stroom is.

Dit kan je bijvoorbeeld vinden in een luidspreker.

**Grootheid** = zelfinductie
**Symbool** = L
**Eenheid** = Henry
**Symbool**= H


### Condensator

Een condensator kan heel snel op- en ontladen.
vb. lampje van dynamo dat nog even blijft branden

Een condensator dempt ook spanningen.

**Grootheid** = Capaciteit
**Symbool** = C
**Eenheid** = Farad
**Symbool**= F


### Relais

Een schakelaar die aan gaat door spanning op de spoel.


### Diode

Een diode laat stroom in 1 richting door. Er zijn verschillende soorten, zoals een led.
(van anode naar cathode)
Gaat pas in geleiding als de minimum voorwaartse spanning is bereikt.

**Andere types:**
- Zekerdiode (stabilisator)
- Schotkeydiode (lagere doorlaat spanning)
- Photodiode (licht gevoelige diode)


### Transistor

Een transistor versterkt de stroom.


### Mosfet

Dit vond ik heel ingewikkeld om te begrijpen.

Na wat extra opzoekingswerk kwam ik er achter dat je een mosfet als een schakelaar of versterker kunt gebruiken.

Een mosfet is een schakelaar/transistor. Die controleert de stroom die tussen een source en drain loopt, door het voltage via de gate (M-gedeelte van de MOS, van Metaal) aan te passen. Zet je spanning op de gate dan kan de  het S-gedeelte (Semiconductor) van de mosfet geleidend worden (weerstand wordt aangepast) waardoor er een stroom van electronen ontstaat. Laag voltage op de gate -> hoge weerstand, hoog voltage lage weerstand. 

_Thanks to Google!_


### Spanningsregelaar

Ook hier vond ik het moeilijk om te volgen, dus heb ik google ingeschakeld.

Een spanningsregelaar is in het algemeen een schakeling, al dan niet elektronisch, die ten doel heeft een aangeboden spanning zo goed mogelijk op een bepaalde waarde constant te houden, onafhankelijk van fluctuaties in de voedingsspanning en de belasting.
_Leve Wikipedia!_


## Schakelingen

Dit deel heb ik weggelaten. Ik ga niet zo veel met elektronica doen, dus is het niet nodig om dit allemaal te begrijpen. Het kon wel fijn zijn voor de lol, maar het was laat en moeilijk. Dus ik heb het hierbij gehouden.


## Motoren

Er zijn verschillende motoren die interessant kunnen zijn:
- **DC**: spanning + draaien (meer en sneller), veel stroom, niet enkel met ardiuno, kan ook met mosfet, met een H-brug kan je de richting veranderen.
- **servo-motoren**: arduino, veel stroom, heel nauwkeurig controleren, stap voor stap laten draaien
- **buzzer*: muziekjes maken met arduino


## Bedenkingen

Ik vond dit een heel moeilijke les. Sommige zaken waren nogal abstract en heb ik toch niet echt nodig. Deze samenvatting is wel handig om bij te houden wat er allemaal nodig is.

Ik heb sowieso iets van schakeling nodig, omdat ik een lamp wil maken. Maar ik ga het basic houden.
















## Volgende les

Volgende les is het normaal KiCad, maar ik heb gekozen voor optie B, dus volgende week geen les.
