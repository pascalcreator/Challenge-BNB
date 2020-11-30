# Challenge Portfolio: Technische Eisen

## Userstory's van de klant:

- Ik wil een website waarop de vier kamers van mijn huis staan, zodat mijn klanten mijn huizen op internet overzichtelijke informatie kunnen vinden
- Ik wil dat er een duidelijk menu is, zodat klanten goed de weg kunnen vinden op mijn site en altijd weten waar ze zich bevinden
- Ik wil een indexpagina waarop foto’s van mijn vier kames staan, zodat klanten een snelle keuze kunnen maken en door op een foto te klikken op een pagina terechtkomen waarop ze meer ze informatie kunnen vinden over de verschillende kamers
- Ik wil voor elke kamer een pagina met vier foto’s van het interieur, een beschrijving van de kaart en een lijst met gegevens, zodat klant op detailniveau geïnformeerd wordt
- Ik wil een contactpagina zodat klanten weten hoe ze contact met me kunnen opnemen

   
## Technische eisen
<!-- ik begrijp dat je technische eisen ook via userstory's kunt communiceren, zullen we dat doen? -->

### Elke pagina bevat:

1. De root van je BNB-site website moet de `/BNB-site` map zijn. Dit is dus waar je `index.html` staat.
2. Elke pagina is correct opgebouwd met `DOCTYPE`, `HTML`, `HEAD` en `BODY` elementen.
3. Elke pagina bevat een correcte titel voor de desbetreffende pagina in het `TITLE` element
4. Het menu is zichtbaar en bruikbaar op elke pagina 
5. Elke pagina is logisch verdeeld en er wordt gebruikt gemaakt van semantische elementen. (`NAV`, `HEADER`, `SIDEBAR`, `MAIN`, `ARTICLE` en/of `FOOTER`)
6. CSS- en Javascriptcode staat in externe bestanden in een eigen submap (`/css` en `/js`) van de website en wordt gelinkt vanuit de html-bestanden. <!-- moet dit ook voor PHP? -->

7. De code voorzie je van duidelijk commentaar <!-- ik denk dat dit nog SMART gemaakt moet worden -->

Gebruik zoveel mogelijk HTML/CSS technieken zoals je die heb leren kennen in Frontend-Basic en Frontend-Essentials. Dit betekent dat je juiste HTML-elementen (tags) gebruikt voor onderdelen van je BNB-site. Dus als je een lijst hebt met punten maak daar dan een ordered of unordered list van. Wil je informatie tonen die het beste in een tabel is te vatten, maak daar dan een tabel van. Het is aan jou om te beslissen welke elementen het beste kunnen worden toegepast in een bepaalde situatie.

Onderstaande lijst is een beknopt overzicht van de HTML/CSS- en JS-technieken die behandeld zijn in de Frontend-Basic en Essentials modules I & II. Kijk voor uitleg bij de desbetreffende modules. Uiteraard is het toegestaan niet behandelde technieken te gebruiken.

#### HTML
```html
<!-- Frontend-Basic -->
    <!DOCTYPE html>
    <head> en <title> en <body>
    <h1> t/m <h6> en <p>
    <a href="">
    <img src="">
    class- en id-atributen (<element class="" id="">)

<!-- Frontend-Essentials -->
    <ul> en <ol> met <li>
    <nav> en <article>
    <table> met <thead> en <tr> en <td>
    <link rel="" href="">
    <script src=""> 
```

#### CSS
```css
/* Frontend-Basic */
    background-color
    color

/* Frontend-Essentials */
    display
    boxmodel met border, margin en padding
    flexbox met row / row-reverse en column / column-reverse en justify-content / align-items
```

#### Javascript
```javascript
// Frontend-Basic
    alert() en prompt() en confirm()
    Let (Variabelen) 

// Frontend-Essentials
    console.log()
    variabelen met datatypes
    objects met properties
    string concattenation
    if / else
    document.queryselector()
```
<!-- Hier PHP, MySQl en Fr.End.Es II nog bij vermelden -->

<!-- Onderstaand onderdeel naar het eind van de challenge, waar studenten de challenge aan hun portfolio toevoegen

## Live zetten mbv Github Pages

Onderstaande video linkt naar een korte introductie (1:05m) over Github Pages.

[![Wat is Github Pages?](https://img.youtube.com/vi/2MsN8gpT6jY/maxresdefault.jpg)](https://vib.by/v/XyYAbowfq)

Github Pages geeft je de mogelijkheid om één repository in je account live te zetten. Zie [deze link](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site) voor een uitleg over hoe je de Challenge repository live zet. Je portfolio zal te zien zijn op `github_username.github.io`.
>
> :warning: LETOP: je moet aangeven dat je de `portfolio` submap van deze repository als root wilt gebruiken. -->
