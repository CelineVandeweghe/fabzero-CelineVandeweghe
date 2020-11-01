# Les 08: Programmeren voor Arduino

## Inleiding

Ik heb vroeger ooit eens met Arduino gewerkt, maar dat was een jaar of 8 geleden, dus dat zit erg ver. Ik beschouw me dus als een persoon zonder ervaring.


## Wat is Arduino?

Arduino is een open source computer platform om het gebruik van elektronica gemakkelijker te maken. Voornamelijk voor standaard elektronica. Het is eenvoudig zolang je het eenvoudig houdt. Want bij ingewikkeldere projecten kan er veel fout lopen. De microcontroller is de basis. 
Momenteel bijna basisplatform door de populariteit bij de lancering van Arduino.

Ook voor geavanceerde elektronica om prototypes te maken en te tonen dat iets mogelijk is.

Iedereen mag zoiets maken en verkopen, maar je mag er geen Arduino opzetten.


## Componenten

Je Arduino krijgt **stroom** via je computer (USB 5V) of via een 7V batterij (wel weinig power, snel plat en veel batterijen nodig) of connecteren via GND of VIN. Als je zaken aanpast, schakel dan wel eerst de stroomtoevoer uit.
De uitgangen werken met 5V.

Een **breadboard** wordt gebruikt om schakelingen te maken. 
De rijen en kolommen zijn geconnecteerd met elkaar. (horizontaal/verticaal)

**Weerstanden**

**LED**

**Andere borden:**
- Arduino Nano (zelfde maar kleiner)
- NodeMCU (populair door chip, zoveel mogelijk functionaliteit naar buiten, programma's Arduino kunnen rechtstreeks gebruikt worden)
- Wemos D1 Mini
- Borden voor textiel
- ...

Om andere boarden te gebruiken moet je naar 'Bestand' - 'Preferences' gaan en deze link http://arduino.esp8266.com/stable/package_esp8266com_index.json  kopiëren en plakken. Daarna naar bord beheer (bij hulpmiddelen). Daarna zoeken op esp8266 en dit installeren (voor IOT versie 2.3.0 nodig).
Daarna het Board Wemos D1 R2 Mini aanduiden.

**Potentiometer**: horizontaal monteren!

**Nieuwe componenten**: Google raadplegen

...


## Responsive Code

- Geen delay
- Millis (tijd sinds start microcontroller - start stroom/reset)




## Oefeningen

### 1. Arduino connecteren met PC

![1]({{site.baseurl}}/assets/arduino/1.jpg)


### 2. LED doen branden

Het lange been is de +, het korte been is de -.
+ in 3.3V, - in GND (ground). Het lampje gaat aan als het correct is en ontploft als het fout is.

![2]({{site.baseurl}}/assets/arduino/2.jpg)

**Hoe via de 5V?** Dan heb je een weerstand nodig!

![3]({{site.baseurl}}/assets/arduino/3.jpg)

Dit ging heel vlot bij mij.


### 3. Programmeren

Hiervoor hebben we het gedownloade programma nodig.
Het bordje kan je kiezen bij tools. Je moet ook de juiste poort aanduiden (niet aansluiten, kijken welke er staat, verbinden en dan die nieuwe nemen.)

We laten de LED knipperen.
Kies voor 'Blink' onder 'Bestand' 'Voorbeelden'. Daarna compileren en uploaden. Bij mij veranderde er niets tot ik de pin van 5V verplaatste naar nummer 13.

![4]({{site.baseurl}}/assets/arduino/4.jpg)


### 4. WeMos connecteren en blinken

Na lang zoeken vond ik de WeMos. Het duurde ook even voordat ik door had dat ik geen micro-USB kabel in mijn doosje had. Gelukkig lag die van mijn gsm in de buurt en kon ik die gebruiken.
(Achteraf heb ik die dus wel gevonden.)

Bij deze opdracht moet je terug de poort selecteren. 
Daarna terug naar de voorbeelden. ESP8266 kiezen, daar staat er een blink voor WeMos. Daarna dezelfde stappen voor uploaden.

![5]({{site.baseurl}}/assets/arduino/5.jpg)


## Programmeren: IDE en blokkencode

Zaken opslaan in sketchbook (opslaan als, dan zit je automatisch in de juiste map). Daarna kan je alles vinden bij 'sketchbook'.

Void setup en loop (beide in code)

Mogelijkheid tot maken in blokkencode.ingegno.be en daarna code kopiëren en plakken in IDE;

Oefening met Hello World en naam (in blokkencode, daarna kopiëren en plakken):
Toevoeging van LED.
![Opdracht]({{site.baseurl}}/assets/arduino/1.xml)

Digitale (drukknop) en analoge input (6 analoge pinnen, via multiplexer naar 1 analoge pin)


## Opdracht - De Creatieve Stem Booklets

Opdrachten in boekjes maken. Een van de boekjes kiezen en het uitvoeren.
Boekje 2 en 3 is de basis.
Boekje 5 voor meer gevorderden.

Boekje 4 best niet gebruiken, het moet aangepast worden. Hiervoor best de slides gebruiken.