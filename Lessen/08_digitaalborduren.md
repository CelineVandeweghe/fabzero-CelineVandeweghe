# Les 08: Digitaal borduren

## Inleiding

Aan het begin van de les werd er wat praktische informatie meegedeeld in verband met Fab Academy.

De sessie is in drie delen. Deel 1 gaat over smart textiles, deel 2 over digitaal borduren en deel 3 is een praktische sessie.

Ik heb nog nooit met een borduurmachine gewerkt. Wel met een naaimachine en simpele borduursteken hierop. Ik heb ook al handmatig geborduurd.

Hieronder lees je een samenvatting van de les.


## Inkstitch

De installatie van Inkstitch was een enorme uitdaging. Zelfs met hulp lukte het niet op mijn mac. Uiteindelijk heb ik het geïnstalleerd op de pc van mijn man. Dat lukte wel vlot.


## Deel 1: Smart textiles

### Wat zijn e-textiles?

E-textiles zijn stukken stof waaraan er elektronica toegevoegd worden. 

Smart textiles kunnen voor verschillende zaken gebruikt worden. Bijvoorbeeld of een baby nog beweegt. Als er actuatoren inzitten dan kan er bijvoorbeeld een alarm afgaan. Er zijn ook nog heel slimme textielen.

**Functies**:
- Sensoren
- Data processing (meting omzetten in reactie)
- Actuatoren die reageren
- Voeding
- Communicaties (meting doorsturen)


### Waarom?

Kledij is een grote industrietak. Het is nu eenmaal een gewoonte geworden. Textiel zit ook in diverse gebruiksmaterialen (auto's, lampenkappen, vloerbekleding, zetels...).
Smart textiles kunnen dingen aangenamer maken.

**Sectoren**:
- Sportsector (alles zo klein mogelijk, metingen tijdens sporten, licht geven bij lopen in donker)
- Gezondheidszorg (metingen doorsturen)
- Mode (lichteffecten, neopixel ledjes)


### Componenten

**Moeilijkheden**:
- Inbouwen in weefgetouw of op stof plaatsen
- Hoe wassen? (vb. inbedden in siliconen om wasbaar te krijgen)
- Hoe recycleren?

Wat is dagelijks ziet is RFID. Bijvoorbeeld bij Decathlon kan je kleding kopen waar de labels RFID bevatten (af te knippen voor te wassen, logistiek voordeel).

**Conductieve draad**:
- Madeira yarn: HC12 zijn handige borduurgaren. HC40 is dunner maar heeft meer weerstand.
- Bekaert Bekinox VN yarn (kan je mee solderen, vastknijpen met kralen en daarop solderen)
- Carbon fibre: Hexel IM7-C 12K
- Ni coated CF
- Conductieve lijmen

Madeira en Bekinox vaakst gebruikt. Best ook eens uittesten met een multimeter.

**Weerstanden**:
- Nodig
- De grote vallen op maar zijn perfect bruikbaar.
- SMD-weestanden (tegenwoordig heel klein, valt niet op)

**LED**: 
- Grotere eilanden waar een draad doorpast. Met naald naaien aan neopixels
- Zelf maken 

**Conductieve stoffen**:
- Knippen
- Solderen
- Lasercutter
- Vinylplotter
- Space fabric (goed, wel vrij duur)
- Conductieve velcro (mogelijkheden om te verwijderen, redelijk duur)
- Space tape
(stoffen en draden kunnen ook met borduurmachine verwerkt worden)

Verdere componenten uit basis elektronica. Deze zijn al vrij klein dus deze kunnen gemakkelijk geïntegreerd worden.

Arduino kan ook geïntegreerd worden. (Lilypad beter om te naaien dan Arduino)

**Textile switches**:
- Conductieve knopjes (snaps zonder couting), toe en open voor aan en uit
- Velcro
- Magneten
- Drukelementen integreren (bij blijven drukken gaat het licht aan)

**Power**:
- Batterij
- USB power bank

**Sensoren**:
- Barometric sensor (druk, temperatuur, RH)
- Hartmetric sensor (zuurstofgehalte en hartslag)
- Afstandssensor (tot 4 meter, meting met snelheid van geluid)
- Afstandsensor gebaseerd op lidar met laserpuls
- Bewegingssensor
- Capactive Touch sensor


## Deel 2: Digitaal borduren

### Naaien versus borduren

_Naaien_ = twee draden die aan elkaar gelust worden (ook bij borduren)

Het grote verschil tussen borduren en naaien is het gebruik van een ander voetje (bij naaimachine rechthoekig en bij borduurmachine rond). Bij borduren (ook machinaal) wordt er ook een borduurring gebruikt (laat toe om gelijk welke tekening te maken).


### Soorten borduurmachines

-**1 naald**: telkens draad opnieuw inrijgen
-**Meerdere koppen** met verschillende draden (wel maar 1 onderdraad!)

Borduursel goed gemaakt = onderdraad niet zichtbaar 


### Stappen

1. Creatie vector afbeelding (vb. maken in inkscape en inladen in inkstitch voor stap 2)
2. Converteren naar Embroidery vectors 1 parametrize (hier kies je je steektype)
3. Plan stitch order & attach commands
4. Visualisatie (simulatie)
5. Embroidery file opslaan
6. Test naaien (optimale combo stof, naalden en garen)
7. Optimaliseren

**Tip**: gebruik niet te veel kleuren


### Basissteken

- Rijgsteek 
> - Randen (van kleine steken tot grotere, beter niet kleiner dan 1.5 mm)
> - Bean stitch (dikkere lijn, vaker weg en weer met naald)
> - Manueel stitch (knooppunten pad volgen)
> - Zigzag (best alleen maar bij rechte lijnen, je kan de hoogte van de pieken regelen maar ook hoe dicht ze bij elkaar komen, mogelijk voor afwerking)
- Vulsteek
> - Grotere gebieden met klein vullen (vb. patches)
- Satijnsteek
> - Kolom satijnsteek (randen, letters, klein opvulgebied, draden naast elkaar leggen om pad te vullen)
> Deze steek heeft een underlay.

Best enkele mogelijkheden naast elkaar uitproberen en dan een keuze maken.

Alledrie combineren voor patronen. Er zijn ook variaties op elke steek mogelijk.

Stof opspannen in een borduurring is heel belangrijk. De borduurring moet passen op de borduurmachine. Verstevig ook je stof (verschillende soorten backings/vliezen, afhankelijk van het soort stof). Hoe strakker en egaler de stof is des te mooier het borduurwerk wordt.


### Materialen

**Backings**:
- _Tear away_: achteraf wegsmijden (vaker voor dikkere stoffen en dunner leer)
- _Wash away_: wegwassen, voor dunnere stoffen, voorbeeld organza, ook goed voor harige stoffen (imitatiebond, badstof)
- _Cut away_: wegknippen, voorbeeld bij T-shirts uit de winkel (zie je nog een beetje)
- _Klevend vlies_: kleinere stukken of te dik (Filmoplast)

**Borduurgaren**:
Madeiragaren goed. Wel goed om te zorgen voor een goede combinatie garen en machine.
Ondergaren en bovengaren zijn anders. Ondergaren zijn dunner en steviger, bovengaren hogere glans en minder stevig.
Types:
- Polyester (algemeen, industriestandaard, sterk, duurzaam, kleurvast)
- Rayon (hogere glans)
- Katoen (zachte glans)
- Zijde (luxueus, sterk en fijn)
- Metallic (breken veel)


### Oefeningen

#### Logo NASA

Ik kon het logo van NASA niet downloaden als .svg. Dus ik heb het gedownload als .png en dan gekozen om de bitmap te tracen. Zo had ik ook een vectorieel bestand.

![Logo NASA]({{site.baseurl}}/assets/borduren/nasa.png)

Het is handig om eerst de afmetingen aan te passen.
Daarna zijn er verschillende mogelijkheden om aan de slag te gaan.

Wij gingen zo te werk:
- Ga naar uitbreidingen
- Kies voor Ink/Stitch
- Params (klikken en wachten op venster)
- Je krijgt enkele standaard opties

Als het er goed uit ziet, kan je het zo laten. En anders de parameters aanpassen.
Wanneer je het hebt opgeslaan, kan je naar visualisatie en export gaan. Daarna krijgt je een preview. Hier kan je het ook exporteren indien je tevreden bent. (kies het juiste type file bij het toestel, in Drongen .PES). Dan op een USB en na het toestel.

Het duurde zeer lang tot het lukte bij mij. Ik moest nog break apart doen en ook al waren er geen lijnen, deze uitzetten. Ik kreeg ook geen preview dus ik wist niet of het gelukt was.
Uiteindelijk is het gelukt door alles toe te passen en dan te kiezen voor realistic preview.

Hierna doen we een oefening met enkel lijnen. Ook hier is opdelen heel belangrijk.
De lijnen dienen als tool om de vulling te maken. Hiervoor heb je twee evenwijdige lijnen nodig. Dus de eindstukjes moeten worden verwijderd. (selecteren en zesde knopje onder de taakbalk)
Met het potloodje kan je dan enkele horizontale stukken tekenen op het eerste beentje van de N. Je tekent als het ware hoe je wilt dat er geborduurd wordt.

![Strepen N]({{site.baseurl}}/assets/borduren/strepen.svg)

Hierna moet de orientatie van een van de twee evenwijdige lijnen van de N gewijzigd worden?. Deze mogen niet in dezelfde richting lopen.

**Hoe doe je dat?**
Je selecteert een van de lijnen. Dan ga je naar paden. 
Dan kan je kiezen voor de optie omdraaien. (1 knooppunt op die zijde selecteren is voldoene om te kunnen omkeren) Alle paden moeten in dezelfde richting lopen.

**Waarom?**
Dit zorgt voor mooiere resultaten die je zelf meer in de hand hebt. 

Dit krijg je als je de stappen volgt voor alle letters.

![Strepen N 2]({{site.baseurl}}/assets/borduren/strepen2.svg)


Combineer (path - combine) alles per letter.
De volgende stap is letter per letter selecteren. Dan terug naar Ink Stitch gaan en kiezen voor Params. Dan gaan we naar Satin Column. De underlays van de andere vensters duiden we aan (zigzag underlay niet). Stroke zetten we af. (je kan zelf wat kiezen wat je aan en af zet, in de oefening heb ik niets aangepast)
Om de draadkleur aan te passen, moet je met verschillende lagen werken. Of de machine op pauze zetten. 

![Strepen N 2]({{site.baseurl}}/assets/borduren/nasa.pes)

Ook opslaan als .emf. Dan kan het ook in de software in Drongen gebruikt worden.


#### Patch maken

Een tekening maken aan de hand van een lijntekening en enkele vullingen.

Streepjeslijn wordt herkent als running stitch (lijnstijl). Gevulde objecten worden uitgewerkt zoals NASA. (eilanden gevuld met kleur)
Wil je meerdere kleuren en dat de machine automatisch stopt? Steek dan alles in een aparte laag.

Dit is een opdracht om af te werken voor de praktijkoefening. Dit bespreek ik bij de opdracht van digitaal borduren.


## Tips

- Vilt is fijn om mee te werken, ook voldoende lichtdoorlatend.


## Ideeën

- Patches om bijvoorbeeld op rugzakken te naaien die veranderen afhankelijk van temperatuur of vochtigheid.
- Patches met licht om goed zichtbaar te zijn in het donker. Of geborduurde buttons, want dan kan het verplaatst worden.
- Met velcro aan en af zetten. Afbeelding kan ook zo veranderd worden.