# Vecka 14: State Bootcamp

## Shakespearean insult generator

> _Have you no wit, manners, nor honesty but to gabble like tinkers at this time of night? - Twelfth Night_

I denna övning ska du få bygga en sida som slumpar en förolämpningar från en pjäs skriven av Shakespeare och visar dessa för användaren.
En "sick burn" från Shakespeare ger en bra start på dagen!

I denna övning skall du använda dig av 4 komponenter:

- App
- Header
- Page
- Insult

Din _Header_ skall innehåla ett formulär där användaren kan ange hur många (max 10) förolämpningar hen vill ha kastade i ansiktet. Denna data skall sedan användas i din _Page_ för att rendera ut X antal _Insult_-komponenter.

Fundera på strukturen i din applikation, vilka tillståndsvariabler behöver du använda, och var någonstans bör de ligga?

Förolämpningarna hittar du i `insults.json` i _assets_-mappen.

Tips på typsnitt: [MedievalSharp](https://fonts.google.com/specimen/MedievalSharp), [IM Fell English SC](https://fonts.google.com/specimen/IM+Fell+English+SC).

## Booking form

Bygg din React-app enligt [denna skiss](https://www.figma.com/file/XenjCcyq3pZUOa9MF3urqQ/Vue.js-form-exercise---Book-a-flight?node-id=0%3A1).

### Steg 1

Koppla ihop varje datapunkt ( klass, titel, förnamn, efternamn, godkänner ) med en funktion i din React-komponent som lyssnar efter inmatning och sparar värdet i en tillståndsvariabel.

### Steg 2

Lyssna efter ett klickevent på knappen. Vid klick skall du bygga ihop all data till ett bokningsobjekt som du sedan antingen console.loggar ut, alt. presenterar på skärmen för användare på ett snyggt sätt.

## React Bootcamp

[I detta dokument](https://docs.google.com/document/d/15Ez_E2d3mh7NuDa60A3Lj-4rZZc52eN7I05PhYwtvk8/edit?usp=sharing) finner ni uppgifter som ni nu bör kunna utföra.

## Valfritt projekt

Arbeta vidare på ditt valfria projekt, alt. påbörja ett nytt, där du nu kan försöka implementera tillståndsvariabler för att göra din sida mer dynamisk. Precis som tidigare ligger det en massa data i _assets_ som ni kan använda er av, men det uppmuntras såklart att skapa egen data om man vill det.
