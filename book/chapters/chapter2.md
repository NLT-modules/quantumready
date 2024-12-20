# Licht waarnemen en maken

## Inleiding

In het vorige hoofdstuk heb je kennisgemaakt met een toepassing van de quantummechanica: de sensor voor het elektrisch veld maakte gebruik van halfgeleidermateriaal. Quantummechanica is een natuurkundige theorie die het gedrag van licht, materie en hun interactie beschrijft. Vaak wordt deze theorie gebruikt om het gedrag te beschrijven van dingen die we niet met het blote oog kunnen zien, zoals koolstofverbindingen ([figuur 2.1a](fig2.1)), bladgroencellen ([figuur 2.1b](fig2.1)) en zelfs kleine beestjes zoals het beerdiertje ([figuur 2.1c](fig2.1)).

(fig2.1)=
<div style="display: flex; justify-content: center;">
    <figure style="margin-right: 20px;">
        <img src="../figures/ch2/afm koolstof.jpg" alt="AFM C" style="height: 200px;">
        <figcaption>Figuur 2.1a: AFMopname van een koolstof-molecuul ( $2 \mathrm{~nm}$ breed).</figcaption>
    </figure>
    <figure style="margin-right: 20px;">
        <img src="../figures/ch2/bladgroencellen.jpg" alt="Bladgroencellen mos." style="height: 200px;">
        <figcaption>Figuur 2.1b: Bladgroencellen in de mossoort Plagiomnium affine. Elke groene stip heeft een diameter van $5 \mu \mathrm{m}$.</figcaption>
    </figure>
    <figure>
        <img src="../figures/ch2/beerdiertje.jpg" alt="beerdiertje" style="height: 200px;">
        <figcaption>Figuur 2.1c: Een beerdiertje onder de microscoop (lengte $0.3 \mathrm{~mm}$ ).</figcaption>
    </figure>
</div>

Quantummechanica drukt een groot stempel op de wereld om je heen, ook al is dat niet altijd direct zichtbaar. Apparaten zoals een USB-stick, een laser en een led-lamp zouden niet mogelijk zijn zonder quantummechanica. Bovendien komen we er meer en meer achter dat ook in biologische processen quantummechanica een belangrijke rol moet spelen. We weten vaak nog niet precies hoe, maar wel dat het zo is. Ondertussen wordt er hard gewerkt aan het ontwikkelen van nieuwe quantum technologieën.

In deze module maak je kennis met een aantal voorbeelden van zowel oude als nieuwe quantumtechnologie. Daarbij wordt regelmatig de vergelijking gemaakt met de natuur of gebruik je technologie om de natuur beter te kunnen bestuderen. Dit hoofdstuk gaat over de vraag: wat is licht en hoe neem je het waar?

(ex2.1)=
```{exercise} Nogmaals de Bij
In hoofdstuk 1 heb je gezien dat bijen het elektrisch veld kunnen gebruiken om te navigeren en bloemen te herkennen. Zelf kun je ook de aanwezigheid van een elektrisch veld voelen maar je hebt geen zintuig dat erin is gespecialiseerd zoals een bij dat wel heeft.
a)	Geef een reden waarom de bij een zintuig heeft ontwikkeld om nauwkeurig het elektrisch veld te kunnen bepalen (en wij niet). 
b)	Leg uit met welk biologisch proces de ontwikkeling van verschillende zintuigen samenhangt.
```

De haartjes van de bij gaan bewegen door de invloed van geladen deeltjes die (op afstand) een elektrisch veld veroorzaken. Om een beweging in gang te zetten is een energieomzetting nodig: de energie die zit opgeslagen in het elektrisch veld wordt omgezet in bewegingsenergie van de haartjes. Je kunt die energie transporteren van A naar B. Dat gebeurt via een verschijnsel waar je al enigszins bekend mee bent uit het dagelijks leven: licht.

De natuur heeft vele verschillende manieren gevonden om dat licht waar te nemen. Kijk daarover [onderstaande video](vid2.1). Later in dit hoofdstuk bekijk je de ogen van een van de dieren uit de video.
(vid2.1)=
<div style="display: flex; justify-content: center;">
    <div style="position: relative; width: 70%; height: 0; padding-bottom: 56.25%;">
        <iframe
            src="https://www.youtube.com/embed/LIfKk37bkyk?si=Im69JXuSRV7IOpeM"
            style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
        ></iframe>
    </div>
</div>

<iframe width="553" height="445" src="https://www.youtube.com/embed/LIfKk37bkyk" title="The Amazing Ways Animals See the World" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Licht: Kleur, golflengte en frequentie

In de komende paragrafen ga je verder onderzoeken wat licht en kleur zijn en hoe we licht kunnen waarnemen, maken en meten. Daarvoor is het handig eerst wat meer te weten over wat licht eigenlijk is.

In [figuur 2.2](fig2.2) zie je een deel van een regenboog. Licht van de zon wordt door regendruppels uit elkaar getrokken in verschillende kleuren. Dat verloop van kleuren wordt een spectrum genoemd. De volgorde waarin het witte licht van de zon uiteenvalt is altijd hetzelfde.

(fig2.2)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/regenboog.jpg" alt="Regenboog na storm" style="height: 200px;">
        <figcaption>Figuur 2.2 Regenboog na een storm door Ben Njeri.</figcaption>
    </figure>
</div>

(ex2.2)=
```{exercise} Kleuren van de regenboog
<iframe src="https://tudelft.h5p.com/content/1292327410820329727/embed" aria-label="Kleuren van de regenboog" width="1088" height="637" frameborder="0" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe><script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>
```

Met licht bedoelen we meestal zichtbaar licht. Licht ontstaat door een regelmatige verstoring in het elektrisch veld. Een bij kan bijvoorbeeld ook een willekeurige verstoring in het elektrisch veld waarnemen, maar dat is een ander soort die we geen licht zouden noemen. Die regelmatige verstoring wordt elektromagnetische straling genoemd. Naast zichtbaar licht zijn er ook vormen van elektromagnetische straling die niet zichtbaar zijn voor mensen. Als we ze wel zouden kunnen zien, dan zou je in [figuur 2.2](fig2.2) ultraviolet links van de regenboog nog violet zien en infrarood rechts van rood.

Dat de verstoring in het elektrische veld regelmatig is betekent dat het een bepaalde frequentie heeft: het aantal keer dat het veld per seconde verandert. Voor de grootheid frequentie wordt de letter $f$ gebruikt en je meet het in de eenheid hertz, afgekort met $\mathrm{Hz}$. De hertz is gelijk aan de eenheid 'per seconde', dus $\mathrm{Hz}=\frac{1}{{ }^{s}}$. Elke kleur heeft zo een andere frequentie. Rood licht heeft bijvoorbeeld een frequentie van rond de $4,4 \cdot 10^{12} \mathrm{~Hz}$. Vergelijk die frequentie maar eens met je hartslag: in rust zo'n $60 \mathrm{~Hz}$.

Het bijzondere van elektromagnetische straling is dat de trilling zich altijd voortplant met de lichtsnelheid: $v=c=3,0 \cdot 10^{8} \mathrm{~m} / \mathrm{s}$. Doordat de trilling zich voortplant ontstaat er een golflengte. Je kunt dat vergelijken met wat er in een heel lang touw gebeurt dat je aan een kant regelmatig op en neer beweegt: een trilling ([figuur 2.3](fig2.3)). Die trilling zal zich ook door het touw verplaatsen. Maar niet elk punt op het touw trilt op het zelfde moment in dezelfde richting. Er zit een vertraging in. Door die vertraging ontstaat er een golf in het touw. De lengte van één zo'n golf heet een golflengte. Voor de grootheid golflengte wordt de Griekse letter $\lambda$ gebruikt (spreek uit: lambda). De eenheid is de meter. De golflengte is gelijk aan de afstand die het licht in één trilling aflegt.

(fig2.3)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/transversale golf.jpg" alt="Voortplanting trilling in touw" style="height: 200px;">
        <figcaption>Figuur 2.3: Een trilling plant zich voort in een touw. (Bron: https://evantoh23.wordpress.com/2011/07/29/general-wave-properties-rope-wave/, rechten onbekend)</figcaption>
    </figure>
</div>

Tussen golflengte, frequentie en lichtsnelheid geldt nu het volgende verband:

$$
\lambda \cdot f=c
$$

Met deze formule kun je de frequentie van rood licht omrekenen naar een golflengte.

(ex2.3)=
```{exercise} Golfsnelheid, golflengte en frequentie

Elektromagnetische straling plant zich in vacuüm en lucht voort met een snelheid van $3,0 \cdot 10^{8} \mathrm{~m} / \mathrm{s}$. Het is moeilijk voor te stellen hoe snel dat is.

a) Bereken hoe vaak licht in één seconde rond de evenaar kan reizen.

Er zijn vele vormen van elektromagnetische straling. Zichtbaar licht is daar maar een klein gedeelte van. Reken voor de volgende voorbeelden de gegeven frequentie om in een golflengte of andersom.

b) Rood licht heeft een frequentie van rond de $4,4 \cdot 10^{12} \mathrm{~Hz}$.

Bereken de bijbehorende golflengte.

c) Er zijn drie soorten ultraviolette straling: UV-A, UV-B en UV-C. Het grootste deel van de ultraviolette straling van de zon die de aarde bereikt is UV-A. Dat heeft een golflengte van 315 tot $400 \mathrm{~nm}\left(1 \mathrm{~nm}=10^{-9} \mathrm{~m}\right)$. Reken de grenzen van UV-A om in hun frequentie.

d) Een magnetron warmt eten op met behulp van radiogolven met een frequentie van 2,45 GHz. De G staat voor Giga. Zoek op hoe groot de vermenigvuldigingsfactor $\mathrm{G}$ is en reken de frequentie van magnetronstraling om naar een golflengte. Vergelijk die golflengte met de afmeting van een magnetronoven.
```

## Licht en donker onderscheiden: staafjes

Dat wij elektromagnetische straling met een frequentie van rond de $4,4 \cdot 10^{12} \mathrm{~Hz}$ waarnemen als rood is niet zo vanzelfsprekend. Die kleur komt op een ingewikkelde manier tot stand. Om de werking van het oog beter te begrijpen kijken we daarom eerst naar de meest eenvoudige functie van het oog: het verschil meten tussen licht en donker.

Om licht van donker te onderscheiden moet het oog lichtenergie opnemen en omzetten in een elektrisch signaal dat naar de hersenen gestuurd wordt via de oogzenuw. Het opvangen en verwerken van licht gebeurt met je netvlies, zie [figuur 2.4](fig2.4). Daar bevinden zich de lichtgevoelige cellen die kegeltjes en staafjes worden genoemd. De staafjes zijn vooral heel lichtgevoelig, met de kegeltjes zie je kleur. Daar is wel meer licht voor nodig. Vandaar dat je in het donker weinig kleur ziet: er is te weinig licht voor de kegeltjes in je oog om kleuren te onderscheiden.

(fig2.4)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/schema oog.jpg" alt="doorsnede oog" style="height: 200px;">
        <figcaption>Figuur 2.4 Een schematische doorsnede van het oog, waarin ook het netvlies is aangegeven. (CC BY 3.0 door Cenveo https://www.coursehero.com/study-guides/cuny-csi-ap-1-2/special-senses-vision/ )</figcaption>
    </figure>
</div>

(ex2.4)=
```{exercise} Kegeltjes en staafjes

In [figuur 2.5](fig2.5) zie je een afbeelding van kegeltjes en staafjes gemaakt met een (elektronen)microscoop.
<!-- Commented [LK34]: In deze sectie kunnen nog wat meer praktische opdrachten. Misschien is te bepalen hoe lichtgevoelig het oog is? -->

a) Twee cellen zijn aangegeven met een letter ( $\mathrm{a}$ en b). Welke van deze cellen is een kegeltje, welke een staafje?

b) De vergroting van de opname bedraagt $4000 \times$

Bepaal de breedte en lengte van de cel aangegeven met $b$.

(fig2.5)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/kegeltjes en staafjes.jpg" alt="SEM kegeltjes en staafjes oog" style="height: 200px;">
        <figcaption>Figuur 2.5 Een afbeelding van kegeltjes en staafjes gemaakt met een elektronenmicroscoop. De kleuren zijn niet echt maar later toegevoegd. Vergroting 4000× (nietrechtenvrij!) https://www.sciencephoto.com/media/308755/view/false-colour-sem-of-rods-and-cones-of-theretina</figcaption>
    </figure>
</div>
```

Hoewel kegeltjes en staafjes verschillende functies hebben, is hun werking gebaseerd op hetzelfde principe. Een lichtgevoelig molecuul (retinal) zit opgevouwen binnenin een groot eiwitmolecuul (opsine). Deze combinatie heet rodopsine ([figuur 2.6](fig2.6)). Als retinal lichtenergie opneemt dan verandert het van vorm ([figuur 2.7](fig2.7)). Hierdoor past het niet meer in de opsine. Zo valt het rodopsine uit elkaar en dat is het begin van het signaal dat naar de hersenen wordt gestuurd dat er licht is waargenomen.

(fig2.6)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/rodopsine.jpg" alt="Rodopsine en retinal" style="height: 200px;">
        <figcaption>Figuur 2.6 Rodopsine met in het midden retinal (rode bolletjes). [publiek domein]</figcaption>
    </figure>
</div>

(fig2.7)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/cis trans retinal.png" alt="cis-retinalmolecuul trans-retinal" style="height: 200px;">
        <figcaption>Figuur 2.7 cis-retinalmolecuul absorbeert licht en verandert in trans-retinal.</figcaption>
    </figure>
</div>

(ex2.5)=
```{exercise} Lichtgevoelig molecuul: retinal

Retinal komt in twee vormen (isomeren) voor. In [figuur 2.7](fig2.7) zie je een schematische weergave de twee vormen van retinal: cis en trans genaamd. Op ieder hoekpunt bevindt zich een koolstofatoom ( $\mathrm{C}$ ) die met een enkele binding (één streep) of dubbele binding (twee strepen) is verbonden met andere koolstofatomen.

Construeer een cis retinal molecuul met een molecuul bouwdoos. Maak er een foto van, verander het vervolgens in trans retinal en maak een tweede foto.
```
(ex2.6)=
```{exercise} Stabiliteit van rodopsine

Af en toe verandert retinal spontaan van vorm zonder dat er een interactie is met licht. Dat is een bron van ruis: je oog (of een sensor) geeft een vals signaal af. Om goed te kunnen zien moet die ruis veel kleiner zijn dan het echte signaal. Met andere woorden: de kans dat rodopsine spontaan uit elkaar valt moet heel klein zijn. Een staafje bevat ongeveer $10^{8}$ moleculen rodopsine en geeft ongeveer iedere 150 seconden een vals signaal af

Leg met deze twee gegevens en een berekening uit dat rodopsine een heel stabiel molecuul is.
```

## Kleur onderscheiden: kegeltjes

In zowel de staafjes als de kegeltjes is het de stof retinal die reageert op licht. Het precieze eiwit waar het in opgesloten zit (de opsine) verschilt echter. Daardoor verschilt de kleur van het licht waarbij retinal van vorm verandert. Zo heeft de natuur een (bio)sensor ontworpen die gevoelig is voor bepaalde kleuren licht.

In [figuur 2.8](fig2.8) zie je voor welke golflengtes een staafje gevoelig is. De piek ligt ongeveer bij een golflengte van 500 nanometer, wat overeenkomt met groen licht. Kleur zie je juist met de kegeltjes. Daarvan heb je drie verschillende soorten. Elk kegeltje is gevoelig voor een specifiek stukje van lichtspectrum. Een is voornamelijk gevoelig voor rood licht, één voor groen en één voor blauw licht. Zie [figuur 2.9](fig2.9). In dit figuur is ook nog eens de grafiek voor de staafjes weergegeven.

Met die drie kegeltjes kun je veel meer kleuren zien dan alleen blauw, groen en rood. Dat werkt als volgt. Stel er valt cyaan licht op je netvlies met een golflengte van $480 \mathrm{~nm}$. Alle drie de kegeltjes zijn gevoelig voor dit soort licht en geven dus alle drie een signaal naar de hersenen. Omdat bij deze golflengte de gevoeligheid niet precies gelijk is, verschilt het signaal van de drie kegeltjes. Het is die precieze combinatie van signalen waar de hersenen een betekenis aan geven. Je hersenen gebruiken dus de relatieve sterkte van de drie signalen om heel veel kleuren mee te kunnen zien

(fig2.8)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/absorptie licht staafjes.png" alt="Absorptie van licht door een staafje als functie van de golflengte" style="height: 200px;">
        <figcaption>Figuur 2.8 Absorptie van licht door een staafje als functie van de golflengte.</figcaption>
    </figure>
</div>

(fig2.9)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/gevoeligheid kegeltjes staafjes.jpg" alt="De gevoeligheid van kegeltjes en staafjes als functie van kleur." style="height: 200px;">
        <figcaption>Figuur 2.9 De gevoeligheid van kegeltjes en staafjes als functie van kleur. (Variatie op Bowmaker \& Dartnall CC BY-SA 3.0 https://commons.wikimedia.org/wiki/File:Cone-response-uk.svg)</figcaption>
    </figure>
</div>

(ex2.7)=
```{exercise} Lichtgevoeligheid staafjes 

Bij weinig licht is het signaal dat van de kegeltjes naar je hersens gaat veel kleiner dan van de staafjes.

a. Leg met behulp van [figuur 2.8](fig2.8) uit waarom je met alleen staafjes toch geen kleuren van elkaar kunt onderscheiden, hoewel de staafjes wel gevoelig zijn voor meerdere kleuren. Apps die gebruikt worden bij het sterrenkijken hebben vaak een nachtmodus waarbij alleen roodtinten worden gebruikt met een golflengte rond de $630 \mathrm{~nm}$. Daardoor kun je wel de app zien, maar wordt je niet door je scherm verblind waardoor je de lichtzwakke sterren niet meer ziet.

b. Leg dat uit met behulp van de grafiek in [figuur 2.9](fig2.9).
```

(ex2.8)=
```{exercise} Kleuren zien

In de video bij de inleiding van dit hoofdstuk heb je al kennis kunnen maken met de bidsprinkhaankreeft. Vreemde naam trouwens: het is geen sprinkhaan en geen kreeft. Lees onderstaande tekst over de ogen van dit diertje.


>$\textbf{De ogen van de bidsprinkhaankreeft}$<br>
In het oog van bidsprinkhaankreeften bevinden zich twaalf verschillende fotoreceptorklassen, waaronder vier die uv-licht kunnen detecteren. Kun je je voorstellen wat een bidsprinkhaankreeft aan kleuren kan ontwaren!
(fig2.1)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/bidsprinkhaan garnaal.jpg" alt="Ogen van de bidsprinkhaan garnaal" style="height: 200px;">
        <figcaption>Figuur 2.10 Ogen van de bidsprinkhaan garnaal door Daniel Sasse (CC BY 4.0) https://commons.wikimedia.org/wiki/File:Mantis-Shrimp-Eyes.jpg</figcaption>
    </figure>
</div>

> Toch maakt het schaaldiertje het niet zo bont: ze zijn ontstellend slecht in het onderscheiden van subtiele kleurverschillen. Mensen kunnen kleuren onderscheiden waarvan de golflengte één tot vier nanometer verschilt. Bidsprinkhaankreeften kunnen dat nog niet met kleuren die tussen twaalf en vijfentwintig nanometer uit elkaar liggen, ongeveer het verschil tussen zuiver geel en oranje. Zij zien als het ware de kleuren van een setje van twaalf verschillende potjes verf, maar kunnen de mengkleuren niet waarnemen.
>
> Bron: Esger Brunner, Nederlands Tijdschrift voor Natuurkunde

In het oog van de bidsprinkhaankreeft vind je dus veel meer verschillende soorten lichtgevoelige cellen. Toch kun jij beter kleuren onderscheiden dan de bidsprinkhaankreeft.
a) Leg met behulp van de theorie eerder beschreven uit hoe je met slechts drie soorten kegeltjes de kleuren geel en violet kunt zien.
Elk van de lichtgevoelige cellen van de bidsprinkhaankreeft is gevoelig voor een net iets andere golflengte. In [figuur 2.9](fig2.9) staat de gevoeligheid van de drie kegeltjes in mensenogen.
b) Maak een schets hoe jij denkt dat de grafiek er voor de 12 lichtgevoelige cellen van de bidsprinkhaankreeft eruit ziet. Geef kort een motivatie voor je schets.
c) Leg met behulp van jouw schets en het artikel uit dat de hersenen van de bidsprinkhaankreeft niet veel doen aan het verwerken van de informatie, zoals wel het geval is in de hersenen van mensen.
Doordat er minder verwerking plaats vindt in de hersenen van de bidsprinkhaankreeft wordt het signaal veel sneller verwerkt dan bij de mens.
d) Noem een evolutionair voordeel van deze snelle verwerking.
```

(ex2.9)=
```{exercise} Kleurenblind

Een vorm van kleurenblindheid is de rood-groen beperking. Je kunt dan niet goed onderscheid maken tussen de kleuren rood en groen.

Bedenk een oorzaak voor die beperking waarbij je gebruik maakt van [figuur 2.9](fig2.9).
```

(ex2.10)=
```{exercise} Meer kegeltjes of meer staafjes?

Vier leerlingen praten over de vraag of je nu meer kegeltjes of staafjes hebt in je netvlies:

Sumeia zegt: 'Je moet drie verschillende kleuren kunnen zien. Staafjes hoeven alleen licht en donker waar te nemen. Dus je hebt meer kegeltjes nodig.'

Iris zegt: 'In het donker is er minder licht. Dan kijk je met je staafjes, dus je hebt meer staafjes nodig.'

Sem zegt: 'In het donker kun je soms nog steeds kleur zien, dus je hebt van een bepaald type kegeltje er minder nodig dan van de anderen.'

Amir zegt: 'Ik denk dat het aantal staafjes gelijk is aan het totaal aantal kegeltjes. Dus van alle drie bij elkaar opgeteld.

a) Geef voor elk van de leerlingen een argument waarom je het eens zou kunnen zijn.

b) Geef voor elk van de leerlingen een argument waarom je het oneens zou kunnen zijn.

c) Bedenk samen nog andere mogelijke antwoorden.
```


## Kleuren maken en meten met LEDs

Je kunt je oog dus zien als een sensor die licht meet en omzet in een signaal. Je oog kan daarbij onderscheid maken tussen licht en donker: ogen zijn lichtgevoelig. En je ogen kunnen heel veel verschillende kleuren licht onderscheiden: ze zijn ook kleurgevoelig. Veel technische toepassingen moeten iets soortgelijks kunnen: 1) weinig licht waarnemen en omzetten in een elektrisch signaal, en/of 2) de kleur van licht waarnemen en dat omzetten in een elektrisch signaal.

In [Opdracht 1.7](ex1.7) heb je al een eerste sensor gemaakt. Die zette een verandering van het elektrisch veld om in een elektrisch signaal (en vervolgens weer in licht). Die sensor maakte gebruik van een JFET en een led. Een JFET is een voorbeeld van een transistor: een component die een signaal kan versterken of kan dienen als schakelaar. Transistoren kunnen heel klein zijn: in je smartphone zitten wel 10 miljard transistoren! Al die transistoren samen zijn verantwoordelijk voor het verwerken van elektrische signalen en dat maakt allerlei bewerkingen mogelijk.

In de sensor van [Opdracht 1.7](ex1.7) zat ook een led: die zette het elektrische signaal om in een lichtsignaal. Led is een afkoring van light emitting diode (vertaling: licht uitzendende diode). Een diode is, net als een transistor, een elektrische component die gemaakt kan worden van halfgeleiders. In [figuur 2.11](fig2.11) zie je een schematische weergave van een led. Het plastic omhulsel zorgt ervoor dat het licht gebundeld wordt en beschermt tegelijkertijd de diode zelf. Merk op dat een led twee aansluitingen heeft die niet gelijk zijn. De led geeft alleen licht als deze goed is aangesloten: het lange pootje is de plus, het korte de min. Bovendien kun je de min-kant herkennen doordat het omhulsel aan die kant is afgeplat.

(fig2.11)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/schema led.gif" alt="Schematische weergave van een led" style="height: 200px;">
        <figcaption>Figuur 2.11 Schematische weergave van een led.</figcaption>
    </figure>
</div>

Je kunt een led ook gebruiken als een eenvoudig soort lichtsensor.

(ex2.11)=
```{exercise} Practicum: Een eerste lichtsensor

Voor deze kleine proef heb je nodig:

- een rode en een groene of blauw led
- een rood lampje
- een uv-zaklamp
- een knoopcelbatterij

Uitvoering:

1) Controleer eerst met de knoopcelbatterij of de leds werken. Sluit daarvoor de led aan op de plus en min van de knoopcel. Let op dat je de juiste kant gebruikt (zie ook de theorie hierboven).
2) Houd nu de plus van de ene led tegen de plus van de andere led. Doe hetzelfde met de min.
3) Vraag een andere leerling om met het rode lampje op de groene/blauwe led te schijnen. Neem waar of de rode led licht gaat geven.
4) Doe hetzelfde maar nu met de uv-zaklamp. Neem opnieuw waar of de rode led licht gaat geven.
```

(ex2.12)=
```{exercise} Practicum: kleur van een led

In [Opdracht 2.11](ex2.11) heb je gezien dat een led licht geeft als er een spanning over staat. In dit practicum onderzoek je dat wat preciezer

Onderzoeksvraag: Welk verband is er tussen de spanning over een led en het licht dat de led uitzendt?

Zie [figuur 2.12](fig2.12) voor de proefopstelling. Er zijn vier leds parallel aangesloten op een variabele spanningsbron die in eerste instantie is ingesteld op 0 volt. De spanning kan variëren van 0 tot 5 volt. ledere led is in serie geschakeld met een weerstand van $100 \Omega$. Bovendien kan iedere led aan /uit geschakeld worden. Bij een parallelschakeling is de spanning over iedere tak op ieder moment gelijk is. Die spanning wordt gemeten met een voltmeter.

(fig2.12)=
<div style="display: flex; justify-content: center;">
    <figure style="margin-right: 20px;">
        <img src="../figures/ch2/demoopstelling 4 leds.jpg" alt="demo vier leds." style="height: 200px;">
        <figcaption>Figuur 2.12a: De demonstratieopstelling met vier leds.</figcaption>
    </figure>
    <figure>
        <img src="../figures/ch2/schema demoopstelling 4 leds.png" alt="De demonstratieopstelling met vier leds" style="height: 200px;">
        <figcaption>Figuur 2.12b: Schematiche weergave van de demonstratieopstelling met vier leds</figcaption>
    </figure>
</div>

Selecteer met de schakelaars steeds één led en onderzoek door langzaam de spanning op te voeren bij welke spanning de led begint te branden en met welke kleur. Controleer vervolgens wat er met het licht gebeurt als je de spanning verder opvoert. Daarna zet je de led weer uit en ga je door naar de volgende led.

Neem onderstaande tabel over in je schrift en vul hem in op basis van je waarnemingen. De kolommen voor golflengte en frequentie heb je nodig bij de verwerking.

| led | Kleur | Golflengte $(\mathrm{nm})$ | Frequentie $\left(10^{14} \mathrm{~Hz}\right)$ | Spanning (Volt) |
| :--- | :--- | :--- | :--- | :--- |
| 1 |  |  |  |  |
| 2 |  |  |  |  |
| 3 |  |  |  |  |
| 4 |  |  |  |  |

$\textbf{Verwerking}$

a) Zoek in Binas of internet bij elke kleur led welke golflengte er (ongeveer) bij hoort.

b) Reken de golflengte om naar frequentie en vul die ook in

c) Zet je gegevens in een diagram waarin je de frequentie uitzet tegen de spanning.

d) Welk verband is er op basis van je diagram tussen de frequentie (kleur) en de spanning over de led?

Beschrijf wat er veranderde aan de kleur en de felheid van de leds toen je de spanning verhoogde voorbij het punt waarop de leds licht gingen geven.
```

De resultaten uit [Opdracht 2.12](ex2.12) kun je met een vereenvoudigd model van de werking van een led verklaren. Een led, maar ook een diode, bestaat uit twee tegen elkaar geplaatste plakjes silicium (halfgeleiders) die elk verontreinigd zijn met een bepaalde stof om ze zo verschillende eigenschappen te geven. In het grensgebied tussen die twee materialen ontstaat daardoor een elektrisch veld dat elektronen tegenhoudt. Er is dus een blokkade waardoor er geen elektrische stroom kan lopen. Het bijzondere is dat je de hoogte van die blokkade kunt beïnvloeden tijdens de fabricage door de keuze van de verontreinigingen.

Tijdens de oversteek door het grensgebied geeft een elektron een hoeveelheid elektrische energie $\Delta E_{e l}$ af in de vorm van licht. Zie [figuur 2.13](fig2.13). Om die oversteek te maken moet de spanning groot genoeg zijn: minimaal gelijk aan de drempelspanning $U_{\text {drempel }}$. Het verband tussen $U_{drempel}$ en $\Delta E_{e l}$ wordt gegeven door:

$$
\Delta E_{e l}=q \cdot U_{\text {drempel }}
$$

In deze formule is $q$ de lading van het elektron dat de oversteek tussen de twee halfgeleiders en heeft een waarde van $-1,6 \cdot 10^{-19}$ coulomb (C). Voor deze module is het belangrijk om met vergelijking (1) te kunnen werken. Wil je meer weten over de werking van de led en het ontstaan van het grensgebied, lees dan [2.9 Verdieping: Halfgeleiders](h2.9).

(fig2.13)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/werking led.png" alt="Schematische weergave van de twee halfgeleidende materialen in een led/diode." style="height: 200px;">
        <figcaption>Figuur 2.13 Schematische weergave van de twee halfgeleidende materialen in een led/diode.</figcaption>
    </figure>
</div>

We kunnen dit alles samenvatten met het energiediagram in [figuur 2.14](fig2.14). De elektronen kunnen zich (bij benadering) in een van twee energietoestanden bevinden die de valentieband en de geleidingsband worden genoemd. Tussen die twee energietoestanden bevinden zich geen mogelijke energietoestanden voor de elektronen. Dit wordt de band gap genoemd. De grootte van die band gap bepaald de kleur van een led. Steekt een elektron het grensgebied tussen twee halfgeleiders over dan valt het vanuit de geleidingsband terug naar de valentieband en het energieverschil tussen de banden, de band gap, wordt omgezet in licht.
(fig2.14)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/energieniveauschema led.jpg" alt="Energieniveauschema voor een led." style="height: 200px;">
        <figcaption>Figuur 2.14 Energieniveauschema voor een led.</figcaption>
    </figure>
</div>

In [tabel 2.1](tb2.1) staan de verontreinigingen die gebruikt zijn in de leds uit [Opdracht 2.12](ex2.12). In de verdieping aan het eind van dit hoofdstuk kun je in meer detail te weten komen hoe de eigenschappen van halfgeleiders te beïnvloeden zijn en wat er in een diode en transistor gebeurt.


(tb2.1)=
Tabel 2.1 Halfgeleiders gebruikt in verschillende kleuren leds.

| led (kleur) | Verontreiniging |
| :--- | :--- |
| rood | AlGaInP = Aluminium Gallium Indium Fosfide (fosfor) |
| geel | AlGaInP = Aluminium Gallium Indium Fosfide (fosfor) |
| groen | InGaN = Indium Gallium Nitride (stikstof) |
| blauw | InGaN = Indium Gallium Nitride (stikstof) |

(ex2.13)=
```{exercise} Stroom-spanningskarakteristiek van een led

In [figuur 2.15](fig2.15) zie je een stroom-spanningkarakteristiek die de elektrische eigenschappen van een led laat zien.

a) Leg aan de hand van de grafiek uit dat de led geen stroom geleidt en dus geen licht uitzendt als de spanning onder de drempelspanning blijft.

b) Lees uit de grafiek af wat de drempelspanning is voor deze led.

c) Gebruik je resultaten uit [Opdracht 2.12](ex2.12) om te voorspellen welk soort straling deze led uitzendt. De spanningen die je daar hebt bepaald zijn bij benadering gelijk aan de drempelspanning voor de betreffende led.

d) Schets op basis van je resultaten uit [Opdracht 2.12](ex2.12) de stroom-spanningskarakteristiek voor leds die rood, geel, groen en blauw licht uitzenden.

(fig2.15)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/i-v karakteristiek diode.png" alt="De stroom-spanning karakteristiek van een diode" style="height: 200px;">
        <figcaption>Figuur 2.15 De stroom-spanning karakteristiek van een diode (eigen werk)</figcaption>
    </figure>
</div>
```

De kleur van een led wordt bepaald door de drempelspanning. ledere keer als een elektron genoeg energie heeft om door de led heen te stromen komt er licht vrij. Boven de drempelspanning geldt: hoe hoger de spanning, hoe groter de kans dat elektronen de oversteek gaan maken. De led gaat dan dus feller branden. Je ziet in [figuur 2.15](fig2.15) dat bij een grotere spanning er meer stroom gaat lopen. De grootte van de elektrische stroom zou dus een maat kunnen zijn voor de hoeveelheid licht die de led uitzendt.

Wil je beter begrijpen waarom de led pas licht gaat uitzenden boven een bepaalde drempelspanning, bestudeer dan de [verdieping](h2.9).

## Lichtdeeltjes: fotonen

Een aquarium gevuld met water bevat een gigantische hoeveelheid watermoleculen die zich samen gedragen als een vloeistof. Je kunt een los watermolecuul niet zien maar het is wel de kleinste bouwsteen waaruit de vloeistof bestaat: de kleinste hoeveelheid water die je er in de bak bij kunt doen (of er uit kunt halen) is [één watermolecuul](opmerkingatomen). Er bestaat geen 'half' watermolecuul, het is alles of niks. Het idee dat de materie om ons heen is opgebouwd uit een kleinste bouwsteen stamt al uit de Griekse oudheid. Het woord atoom komt daar ook vandaan: het betekent 'ondeelbaar'.

(opmerkingatomen)=
> Moleculen bestaan natuurlijk weer uit atomen maar er is maar één combinatie van atomen die we een watermolecuul noemen: H$_2$O

In het dagelijks leven merk je niet dat materie is opgebouwd uit atomen en moleculen. Dat komt omdat je bij alles wat je doet met een enorme hoeveelheid atomen tegelijkertijd in aanraking komt. In een suikerklontje zitten al gauw zo'n $3 \cdot 10^{23}$ atomen die met elkaar $7 \cdot 10^{21}$ suikermoleculen maken.

Ook licht heeft een kleinste bouwsteen. Die bouwsteen heet een foton. Het is de kleinste hoeveelheid energie die je in het elektrisch veld kunt opslaan of eruit kunt halen. Bij iedere kleur licht hoort een eigen fotonenergie. Wil je meer energie toevoegen (van een bepaalde kleur) dan kan dat alleen door er een geheel foton bij te doen. In een led wordt de energie van één elektron omgezet in de energie van één foton.

Anders dan atomen en moleculen kunnen fotonen niet met elkaar botsen of aan elkaar blijven plakken. Fotonen zijn dus altijd losse deeltjes en ze zitten elkaar niet in de weg. Je kunt er ook niet zoiets als een lichtmolecuul mee bouwen. Als je een (denkbeeldige) doos wil vullen met atomen zit de doos op een gegeven moment vol tot aan de rand. Maar in dezelfde doos kun je (bijna) oneindig veel fotonen kwijt.

(ex2.14)=
```{exercise} Energie van een foton

Pak voor deze opdracht je resultaten op [Opdracht 2.12](ex2.12) er weer bij en beantwoord de volgende vragen.

a) Welk verband is er tussen de frequentie van het licht dat een led uitzendt en de drempelspanning van die led?

Voor spanning geldt de volgende formule: $U=\frac{\Delta E_{e l}}{q}$. In woorden: als er over een elektrische component een spanning $U$ staat, dan geven de ladingen een elektrische energie $\Delta E_{e l}$ af aan die component. In een led zijn het de elektronen die hun energie afgeven en die energie wordt omgezet in de energie van een foton, dus: $\Delta E_{e l}=E_{f}$.

b) Bereken met behulp van bovenstaande formule en de drempelspanning voor de vier led uit hoeveel energie de fotonen hebben die de leds uitzenden.

c) Maak een grafiek met op de verticale as de fotonenergie (in joule) en op de horizontale as de frequentie (in $\mathrm{Hz}$ ) van het licht.

d) Welk verband lijkt er te zijn tussen fotonenergie en frequentie van het licht? Teken in je diagram een trendlijn die bij dit verband past.

e) Bepaal de helling van de trendlijn. Geef je antwoord in de juiste eenheid.
```

In [Opdracht 2.14](ex2.14) heb je gezien dat de hoeveelheid energie van een foton afhangt van de kleur licht en dus van de frequentie $f$. Voor de energie $E_{f}$ van een foton geldt de volgende formule:

$$ E_{f}=h \cdot f $$ (fotonenergie)

De letter $h$ staat voor een constante, de zogenoemde constante van Planck. De eenheid van $E_{f}$ is joule (J). De eenheid van $f$ is $\mathrm{Hz}$. De helling die je in [Opdracht 2.14](ex2.14) hebt bepaald is bij benadering gelijk aan de constante van Planck $h$. De literatuurwaarde is: $h=6,626 \cdot 10^{-34} \mathrm{~J} \cdot \mathrm{s}$. Uit formule (2) volgt dat in een bundel licht van precies één kleur alle energiepakketjes even veel energie hebben

Omdat de energie van een enkel foton heel klein is gebruiken we in deze module we vaak de eenheid elektronvolt (eV). Ook daar kun je het verschil tussen een enkel deeltje en een hele groep zien. Wissel je energie uit met een grote groep deeltjes dan gebruik je de joule. De uitwisseling met een enkel deeltje is zo klein dat je er een aparte eenheid voor gebruikt. Daarvoor geldt: $1 \mathrm{eV}=1,6 \cdot 10^{-19} \mathrm{~J}$. Door deze keuze wordt het heel makkelijk om een spanning om te rekenen in elektrische energie. Een spanning over een led van (bijvoorbeeld) $1 \mathrm{~V}$ komt overeen met een energie van $1 \mathrm{eV}$.

(ex2.15)=
```{exercise} Omrekenen joule en elektronvolt

De meeste halfgeleiders zijn gemaakt van silicium. Ook zonnepanelen bestaan uit kristallen van silicium. De band gap van silicium is $1,1 \mathrm{eV}$.

a) Reken deze energie om naar een energie in joule.

b) Reken met behulp van formule (2) uit welke frequentie fotonen minimaal moeten hebben om elektronen in silicium over de band gap te krijgen.

c) Reken de frequentie uit b) om naar een golflengte.

d) Leg uit of de golflengte uit opdracht c) een minimale of juist maximale waarde is om elektronen in het silicium over de band gap te krijgen.

In de zomer bedraagt de gemiddelde zonnestraling in Nederland 200 W per vierkante meter. Een zonnepaneel van één vierkante meter ontvangt dus gemiddeld per seconde $200 \mathrm{~J}$ aan lichtenergie. Zonlicht bestaat natuurlijk uit licht met meerdere kleuren. Neem voor de volgende opdracht aan dat al het zonlicht een frequentie heeft van $5,2 \cdot 10^{14} \mathrm{~Hz}$ (geel licht).

e) Bereken uit hoeveel fotonen $200 \mathrm{~J}$ zonlicht bestaat.

f) Maak een schatting hoeveel fotonen er per seconde in je oog terecht komen.
```

## Fotodiodes

Zoals je in de vorige paragraaf hebt gezien kun je met behulp van een led elektrische energie omzetten in licht. Het omgekeerde kan ook: met licht elektrische energie opwekken. Een voorbeeld daarvan is natuurlijk een zonnepaneel. Die worden ook gemaakt van halfgeleiders. Maar ook de leds uit de vorige paragraaf kun je hiervoor gebruiken. Als je een diode gebruikt om licht te meten (in plaats van licht te maken) dan noem je het een fotodiode.

Eerder heb je geleerd dat een diode maar in één richting stroom doorlaat. Een led geeft dus alleen maar licht als je deze in de goede richting aansluit. Draai je de led om, dan wordt de stroom geblokkeerd en lijkt het alsof er niks gebeurt. Maar diodes hebben altijd een kleine lekstroom. Die lekstroom wordt gevormd door elektronen die 'toevallig' de grens tussen de twee halfgeleiders oversteken. De energie die daarvoor nodig is kan uit de omgeving gehaald worden, bijvoorbeeld in de vorm van warmte of, zoals net beschreven, licht. Hoe meer licht de diode opvangt, hoe groter de lekstroom. Door de lekstroom te meten kun je een fotodiode dus gebruiken als lichtsensor. De grootte van de band gap speelt dan nog steeds een rol.

(ex2.16)=
```{exercise} Toepassingen van een fotodiode

Bedenk samen zo veel mogelijk toepassingen waarin je een of meerdere fotodiodes gebruikt om:

a) De hoeveelheid licht te meten en

b) De kleur van licht te meten.

Geef voor elke toepassing aan welke eisen er zijn aan de fotodiode.

Voorbeeld van a): met een fotodiode meet je hoeveel licht er van buiten een kamer binnenkomt. Als het licht wordt kan de verlichting automatisch uitgeschakeld worden. Eisen aan de fotodiode: moet gevoelig zijn voor zichtbaar licht en moet bij weinig licht een verschillend signaal af kunnen geven.
```

(ex2.17)=
```{exercise} Practicum: spectrometer maken
(fig2.16)=
<div style="display: flex; justify-content: center;">
    <figure>
        <img src="../figures/ch2/opstelling spectrometer.png" alt="Aangesloten opstelling spanningsmeter en twee voor de gelijkspanningsbron." style="height: 200px;">
        <figcaption>Figuur 2.16 Aangesloten opstelling spanningsmeter en twee voor de gelijkspanningsbron.</figcaption>
    </figure>
</div>


Voor dit practicum heb je een opstelling nodig die is gemaakt door studenten van de Leidse instrumentmakers School, de LiS (zie [figuur 2.16](fig2.16)).

Verder heb je nodig:

- Een spanningsmeter (of multimeter).
- Een gelijkspanningsbron instelbaar op $5 \mathrm{~V}$.
- Vier aansluitsnoeren.

Uitvoering:

- Aan de buitenkant bevinden zich vier aansluitpunten: twee voor de spanningsmeter en twee voor de gelijkspanningsbron. Sluit ze op de juiste wijze aan. (Zie [figuur 2.16](fig2.16).)
- Stel de spanningsbron in op $5 \mathrm{~V}$, niet hoger.
- Stel de spanningsmeter zo in dat je tot enkele volts kunt meten, op tienden volts nauwkeurig. (In [figuur 2.16](fig2.16) is een multimeter aangesloten.)
- Door het knopje in het midden te draaien kun je achtereenvolgens een led aanzetten (zenders). Controleer dat de leds werken.
- De binnenste ring bevat dezelfde leds als de buitenste ring. Deze leds zijn de ontvangers. Door de ring te draaien kun je een bepaalde zender led (b.v. rood) plaatsen tegenover een ontvanger led (b.v. geel). De spanningmeter meet de spanning over deze ontvanger leds.
- Schakel een bepaalde zender led aan, draai één voor één een ontvanger led tegenover de zender en lees af welke spanning je meet. Noteer je gegeven in een tabel zoals hieronder. Vul aan met het aantal rijen en kolommen dat je nodig hebt.

| Spanning (V) over <br> ontvanger $\rightarrow$ | rood | geel | $\ldots$ |
| :---: | :---: | :---: | :---: |
| Zender $\downarrow$ |  |  |  |
| rood |  |  |  |
| geel |  |  |  |
| $\ldots$ |  |  |  |

Verwerking:

a) Bekijk je tabel met gegevens. Welk verband kun je ontdekken tussen de kleur van de lichtgevende led en de hoogte van de spanning die je over de ontvanger led meet?

b) Geef een verklaring voor het verband dat je bij a) hebt gevonden op basis van de energie van de fotonen en de bandgap van de led waarover je de spanning meet.
```

## Fotodiodes en het oog

Zoals je in [Opdracht 2.17](ex2.17) heb gezien kun je met behulp van fotodiodes licht meten. Je zou fotodiodes dus kunnen gebruiken om een camera te maken. Maar de kleur en hoeveelheid licht bepalen is ook precies de functie van het netvlies.

(ex2.18)=
```{exercise} Oogimplantaat
Lees onderstaand artikel en bespreek vervolgens welke technologische uitdagingen jij ziet om van een led (als fotodiode) een kunstmatig netvlies te maken dat geïmplanteerd kan worden in een oog.

> $\textbf{Fotovoltaïsch implantaat kan zicht herstellen}$
>Een team onder leiding van onderzoekers van Stanford University zegt een draadloos implantaat te hebben ontwikkeld dat het zicht vijf keer beter kan herstellen dan bestaande apparaten.
>Resultaten van rattenstudies suggereren dat het een functioneel gezichtsvermogen kan bieden aan patiënten met retinale degeneratieve ziekten, zoals retinitis pigmentosa of maculaire degeneratie.
>“De prestaties die we op dit moment waarnemen, is zeer bemoedigend”, zegt Georges Goetz, onderzoeker en promovendus elektrotechniek aan Stanford. “Op basis van onze huidige resultaten hopen we dat mensen met dit implantaat objecten kunnen herkennen en zich kunnen verplaatsen.” 
>Retinale degeneratieve ziekten vernietigen fotoreceptoren - de staven en kegels van het netvlies - maar andere delen van het oog blijven meestal gezond. Het implantaat maakt gebruik van de elektrische prikkelbaarheid van retinale neuronen die bekend staan als bipolaire cellen. Deze cellen verwerken de ingangen van de fotoreceptoren voordat ze ganglioncellen bereiken, die retinale signalen naar de hersenen sturen. Door bipolaire cellen te stimuleren, maakt het implantaat gebruik van belangrijke natuurlijke eigenschappen van het retinale neurale netwerk, dat meer verfijnde beelden produceert dan de apparaten die deze cellen overslaan.
>Het implantaat is samengesteld uit zeshoekige fotovoltaïsche pixels die licht via speciale brillen, die door de ontvanger worden gedragen, in elektrische stroom omzetten. Deze elektrische pulsen stimuleren vervolgens de bipolaire cellen van het netvlies en veroorzaken een neurale cascade die de hersenen bereikt.
>
>Vertaald van: https://med.stanford.edu/news/all-news/2015/04/photovoltaic-retinal-implant-could-restore-functional-sight.html (2015)
```

(h2.9)=
## Verdieping: Halfgeleiders

Synopsis: model van led, n-type en p-type halfgeleiders, depletielaag, intern E-veld

