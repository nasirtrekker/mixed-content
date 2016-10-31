# Positionering - Flexbox

Det finns många olika sätt att sköta responsivitet. Dels kan man använda relativ bred och höjd (`%` eller de nyare enheterna: `vh`/`vw`) för att ett element ska uppta en viss procent av skärmen. En sidebar t.ex. tar upp 20% (`width: 20%`) av skärmytan medan det huvudsakliga innehållet tar upp 80% (`width:80%`) av skärmytan. Helst ska man undvika att sätta en fast bredd på element men det kan inte alltid undvikas.

I och med nyaste css-specifikationen, *CSS3*, har `flexbox` blivit ett populärt verktyg när man positionerar med css. `flexbox` gör det också enklare att göra en hemsida/app mer anpassningsbar eftersom elementen marginaljusterar sig själva.

CSS-tricks har en grundlig genomgång av hur man använder flexbox och tar upp alla egenskaper man behöver använda för att skapa en layout med `flexbox`:

* [CSS-tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Övningar - flexbox

### Övning 1 - Flexbox Froggy

Spela spelet **[Flexbox Froggy](http://flexboxfroggy.com/)** och lär dig grunderna i att använda `flexbox`.

Alternativt kan du även spela flexbox-spelet men Froggy är lite tydligare: **[FlexBox Defense](http://www.flexboxdefense.com/)**

### Övning 2 - Positionering med flexbox

Återskapa denna layout. Använd flexbox till så mycket av positioneringen som går. Tänk på vad som ska vara en column och vad som ska vara en row. Hur elementen positionereras bestäms av att sätta `display: flex` på containern/parent-elementet. Använd [CSS-Tricks Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) som dokumentation om du stöter på några problem.

![Imgur](http://i.imgur.com/cwfCqUi.png)

### Övning 3 - Använd till ert projekt

Implementera `flexbox` i ert eget projekt på något sätt. Använd flexbox för att positionera navigationen, headern eller liknande. Flexbox is the limit!
