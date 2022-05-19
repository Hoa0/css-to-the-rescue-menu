# CSS to the Rescue @cmda-minor-web 2021 - 2022

## Proces

Bekijk hier mijn proces: [proces op notion](https://special-sprite-fab.notion.site/CSS-wiki-her-d7c220a3618e4238a5dfa7505b4831bc)

## Week 1

### Welke opdracht ga ik doen

Voor CSS-to-the-rescue heb ik de opdracht: CSS Zen Garden uitgekozen. Waarbij ik een responsive restaurant menu ga realiseren in bepaald stijlthema.

### Met welke Css-technieken ga ik als eerst aan de slag

De eerste CSS-techniek waarmee ik aan de slag ben gegaan, is typografie. Omdat in de stijlthema een duidelijk typografie aanwezig zijn. Zo was ik begonnen met het experimenten van de titel pagina, hiervoor heb ik writing-mode property gebruikt. Om bepaalde teksten in een verticale of horizontale richting te krijgen.

### Waar liggen de grootste uitdagingen**

Het menukaart responsive te krijgen en het weergeven in de juiste huisstijl.

### Schetsen

<img src="https://github.com/Hoa0/css-to-the-rescue-menu/blob/main/docs/assignments/restaurantMenu/img/schets.png" width="500">

### Stijl keuze
<img src="https://github.com/Hoa0/css-to-the-rescue-menu/blob/main/docs/assignments/restaurantMenu/img/stijl-css.png" width="300">

## Week 2

### Voortgang week 2

Deze week vooral geoefend met typografie in codepen en onderzoek gedaan naar input.

[codepen, vormen en tekst](https://codepen.io/hoa0/pen/qBVVgrM?editors=1100)

### Wat ging er soepel en wat was lastig?

Het implementeren van typografie ging soepel, daar was ik snel klaar mee. Vervolgens ging ik aan de slag met de input checkbox, dat vond ik wel lastiger. Omdat het heel lang duurde voordat het werkte en het animeerde was niet gelukt als je erop klikt. Voorbeeld waar ik mee aan het experimenteren was [input codepen](https://codepen.io/josetxu/pen/mdRgPLM)

### Welke experimenten heb je gedaan die mislukt zijn?

Het was mij niet gelukt om een transition weer te geven wanneer je op een input checkbox klikt. codepen mislukking [codepen](https://codepen.io/hoa0/pen/qBVVgrM?editors=1100)

codepen voorbeeld experiment [input inspiratie](https://codepen.io/josetxu/pen/mdRgPLM?editors=1100)

### Heb je nieuwe inzichten hoe je de kracht CSS kunt benutten of juist niet?

In een korte tijd heb ik zeker nieuwe inzichten gekregen over de kracht van CSS. Namelijk over de html input tag, het is niet alleen voor teksten input of checklist aanvinken, maar ook een slimme oplossing voor het verbergen van content, i.p.v. JS click event ervoor te gebruiken. Ook heb ik tijdens de themasessies geleerd dat je in css kan animeren en vormen maken.

### Neem wijzingen aan je 1e plan op

- Als eerst wilde ik het hele menu laten zien
- Nu wil ik een deel van het menu kunnen weergeven en verbergen.

### Waar liggen je nieuwe uitdagingen voor komende week?

Nieuwe uitdagingen voor komende week zijn:

- website responsive maken voor mobiel en dekstop
- huisstijl toepassen

## Week 3

### Voortgang week 3

In de afgelopen weken heb ik niet veel aanpassingen gemaakt in de eindopdracht, omdat ik veel in codepen bezig was met de input experimenteren. Verder heb ik tijdens de lessen twee themasessie gevolgd, filters en mask. Dit vond ik wel interessant, ik kreeg gelijk een nieuw idee hoe ik de achtergrond meer vorm kan geven.

### Wat ging er soepel en wat was lastig?

Het toepassen van grid op de content ging soepel, alleen niet voor alle content omdat, één daarvan een andere indeling heeft. Dit vond ik wel lastig om het zo aan te passen om tot een geheel te komen. Verder heb ik met Flexbox gewerkt om mijn content responsieve te krijgen, dit ging goed.

### Welke experimenten heb je gedaan die mislukt zijn?

Wat niet goed lukte was, grid-area gebruiken op de content die een andere indeling heeft dan de andere sections. Ook het toepassen van Clip-path property voor de achtergrond was niet helemaal goed gelukt om in de juiste vorm te krijgen, zoals op de huisstijl. [clip-path oefenen codepen](https://codepen.io/hoa0/pen/dyZwQZP)

### Heb je nieuwe inzichten hoe je de kracht CSS kunt benutten of juist niet?

Deze week heb ik zeker nieuwe CSS-technieken geleerd, vooral na het volgen van de themasessie filter & mask. Gelijk hierna ben ik aan de slag gegaan om vormpjes te maken in css met behulp van clip-path. Voor de hamburger vormen heb ik gebruik gemaakt van drie div’s, dit kon ik makkelijk vervangen door een before & after selector. Waarbij je een content property mee moet geven. Hierdoor hoef ik niet onnodige elementen eraan toevoegen.

### Clip-path
Met de clip-path kan je bepalen welke vorm je wil weergeven en welke je wilt verbergen. Dit kan bijvoorbeeld op een achtergrondkleur of op een foto.

- Clip-path: polygon() hiermee kan je bepalen welke punten wilt aanpassen met behulp van een SVG filter.
- clip path polygon om bepaalde vorm te creëren

### Neem wijzingen aan je 1e plan op

Voor het creëren van de hamburger vormen heb ik gebruik gemaakt van de div’s html-tags, dit heb ik vervangen met slimme before & after selectoren. Voor de volgende keer zal ik niet snel onnodige elementen toevoegen aan de html.

### Waar liggen je nieuwe uitdagingen voor komende week?

Clip-path: polygon(), responsive te krijgen lijkt mij een hele uitdaging, omdat je steeds de coördinatie moet aanpassen wanneer je scherm gaat schalen. Dit geldt ook voor de hamburger vorm, hoe kan ik dit responsive krijgen en dat het goed mee schaalt met de achtergrond clip-path?

Flexbox [flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Week 4

### Bespreek je eindresultaat plaatje

In de laatste week ben ik druk bezig geweest om alle content responsive te krijgen en het in de juiste huisstijl weergeven. Daarnaast heb ik geoefend hoe ik content op een natuurlijke manier kan weergeven, wanneer de gebruiker op een menu link klikt. Hiervoor heb ik de input manipulatie truck gebruikt, i.p.v JS.

### Wat ging er soepel en wat was lastig en waar ben je trotst op?

**Wat vond ik lastig**

- De website helemaal responsive te krijgen
- Achtergrond responsive krijgen, clip-path
- Grid gebruiken

**Trots**

- Vormen kunnen maken met css en slimme input tricks gebruiken voor het weergeven van het menu.
- Alleen vorm voor mobiel is gelukt

### Wat ging soepel?

- het toepassen van grid op de content
- tekst verticaal weergeven
- css kleur consistent aangeven door, **CSS custom properties (variables)**

### Wat vond ik lastig?

- Door de content filteren was zeker een uitdaging, omdat ik graag een transitions wilde meegeven zodat het natuurlijk aanvoelt wanneer je op het menu klikt. Maar ook het netjes weergeven op web en mobiel. Helaas kwam ik erachter dat je bij display property geen transitions mee kan geven.

Welke experimenten heb je gedaan die mislukt zijn?

Content weergeven met een transitions op een natuurlijke manier was niet gelukt. Wanneer je door het menu gaat filteren bij de optie “dessert”, krijg je als eerst een hele wit ruimte tussen doordat ik “opacity” heb gebruikt. [https://codepen.io/hoa0/pen/xxYgLrQ](https://codepen.io/hoa0/pen/xxYgLrQ)

### Conclusie

Om filter op een nette manier weer te geven zonder dat er aparte spaties tussen zitten, is het nodig om `display:none` te gebruiken op de elementen die worden verborgen. Zonder JS is het mij niet gelukt om de content te verbergen. De reden hiervoor is omdat wanneer je de height en opacity aanpast, de order van de grid niet gewijzigd wordt, en omdat je dit niet per element wilt stijlen is de eerst volgende optie `display: none`.

- Vele voorbeelden gebruiken om deze redenen voor een pure CSS optie display none, een voorbeeld hiervan is [https://webdesign.tutsplus.com/tutorials/how-to-build-a-filtering-component-in-pure-css--cms-33111](https://webdesign.tutsplus.com/tutorials/how-to-build-a-filtering-component-in-pure-css--cms-33111)
- Omdat je display: none en block gebruikt, kan je helaas geen css transitions gebruiken.

### Heb je nieuwe inzichten hoe je de kracht CSS kunt benutten of juist niet?

- met display: kan je geen transition meegeven.

Waar wil je meer mee gaan doen?

- responsive met grid en flexbox

## Installation

Porject ophalen
```javascript
git clone https://github.com/Hoa0/css-to-the-rescue-menu.git
```
navigeer naar docs/assignments/restaurantMenu/menu.html

Voor het opstarten heb ik een VSCode [live server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

## Bronnen

[filteren menu input](https://codepen.io/jalajcodes/pen/wvGKZNy)

[input toggle](https://css-tricks.com/almanac/selectors/c/checked/#:~:text=The%20%3Achecked%20pseudo%2Dclass%20in,toggled%20to%20an%20on%20state).

