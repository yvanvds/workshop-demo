# Golvenlab

## Doel
Leerlingen laten zien en horen hoe je rekent met geluidsgolven. Door sinusgolven en hun bewerkingen naast elkaar te bekijken en te beluisteren, ontdekken ze wat er verandert aan de golf en het geluid.

## Doelgroep
Leerlingen van de derde graad secundair onderwijs, voor fysica. De app is Nederlandstalig.

## Eerste versie
- Starten met één sinusgolf met een vrij te kiezen frequentie.
- Elke golf visueel tonen en afzonderlijk kunnen beluisteren, ook na een bewerking.
- Elke golf en elke envelope een herkenbaar, uniek ID geven, zodat leerlingen die bij een bewerking kunnen kiezen.
- Onder de golven een balk met de bewerkingen uit de oorspronkelijke beschrijving tonen.
- Nieuwe sinusgolven toevoegen.
- Envelopes toevoegen: geleidelijk luider, geleidelijk zachter en aanzwellen en weer uitdoven. Een envelope bepaalt hoe de amplitude tijdens de twee seconden verandert.
- Een bestaande golf vermenigvuldigen met een decimaal getal.
- Twee bestaande golven optellen.
- Een bestaande golf vermenigvuldigen met een envelope.
- Elke bewerking als een nieuw resultaat tonen, met de gebruikte ID's en de berekening erbij. De oorspronkelijke golven blijven beschikbaar voor verdere bewerkingen.

## Nog niet
- Andere basisgolfvormen, zoals blok- en zaagtandgolven.
- Werk bewaren, delen, downloaden of opnieuw inladen.
- Accounts of een centrale gegevensopslag.
- Installeerbare apps voor Windows, Android of andere platformen.

## Platform
Een website die leerlingen via een link openen, zonder installatie. Het experimenteren gebeurt op hun eigen toestel in de browser.

## Frameworks en bouwstenen
Flutter met Dart, op uitdrukkelijke voorkeur van de gebruiker. Flutter verzorgt het interactieve scherm, de bediening en de grafieken. De golfberekeningen en geluidsweergave gebeuren lokaal in de browser; er is geen server nodig voor de werking van de app.

## Opslag
Niets bewaren. Golven, envelopes en bewerkingen bestaan alleen tijdens het huidige gebruik van de pagina. Bij herladen of een volgend bezoek begint de leerling opnieuw. De app vraagt of bewaart geen persoonsgegevens.

## Vormgeving
Gebruikt het design system in `design-system/`. De kleuren en lettertypes worden overgenomen uit `design-system/tokens.json` en toegepast in Flutter.

## Eisen
- "Elke wave duurt 2 seconden."
- "Die wordt dan visueel getoond en je kan er naar luisteren."
- "Daarvoor heeft elke waveform dus een id nodig."

## Publicatie
GitHub Pages, zodat leerlingen de Flutter-website via een link kunnen openen. Een later in te richten GitHub Actions-workflow bouwt en publiceert de site automatisch bij elke merge of push naar de hoofdbranch `main`.

## Ontwikkelomgeving
Git, GitHub CLI en Flutter zijn aanwezig. Flutter 3.47.4 (stable) met Dart 3.13.3 en Chrome zijn gecontroleerd; de omgeving is klaar voor webontwikkeling. Android-tools zijn voor dit project niet nodig. GitHub is gekoppeld en deze repository gebruikt het anonieme GitHub-adres voor commits.
