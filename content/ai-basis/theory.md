---
sort: 1
title: AI-gebruik in de bouw
goal: Je begrijpt waarom AI-antwoorden niet altijd kloppen, waarom je ze
  altijd controleert, en hoe je een prompt opbouwt die goede resultaten
  oplevert.
accent: indigo
summary: De basis van verantwoord en effectief AI-gebruik, geschreven voor
  je toekomstige rol als uitvoerder of leidinggevende in de bouw.
leeruitkomsten:
  - Ik kan uitleggen waarom AI niet altijd betrouwbare informatie geeft
  - Ik kan uitleggen waarom controle van AI-antwoorden noodzakelijk is
  - Ik kan een effectieve prompt opstellen volgens een vaste structuur
---

Je kent ChatGPT vast al. Deze les gaat niet over *of* je AI gebruikt, maar
over hoe je het slim, veilig en effectief inzet — straks als leidinggevende
op de bouwplaats, en nu al bij challenge 2.

Lees dit rustig door. De opdrachten die erop volgen bouwen hierop voort.

## 1. Waarom AI niet altijd gelijk heeft

Een taalmodel zoals ChatGPT voorspelt het meest waarschijnlijke volgende
woord, op basis van patronen in tekst waarop het getraind is. Het **weet**
dus niets zeker — het **gokt** heel goed. Dat gaat vaak goed, maar niet
altijd.

<x-callout type="warning">
AI kan met volledig zelfvertrouwen iets verzinnen dat er correct uitziet,
maar niet klopt. Dit heet een **hallucinatie**. De AI "liegt" niet bewust —
het heeft geen manier om te weten dat het fout zit.
</x-callout>

Een paar redenen waarom AI-antwoorden mis kunnen gaan, met voorbeelden uit
de bouw:

- **Verouderde informatie.** Het model kent alleen informatie tot een
  bepaalde datum. Een genoemde NEN-norm of Bouwbesluit-eis kan inmiddels
  gewijzigd zijn.
- **Verzonnen details.** Vraag je om een productspecificatie of
  fabrikantnaam en de AI kent het antwoord niet precies, dan verzint hij
  soms iets plausibels — inclusief niet-bestaande productcodes.
- **Geen lokale kennis.** De AI kent jouw project, bouwplaats of
  bedrijfsafspraken niet, tenzij jij die informatie zelf aanlevert.
- **Gemiddelde in plaats van feit.** Bij rekenvragen (bijv. een
  materiaalhoeveelheid) geeft de AI soms een aannemelijk klinkend getal dat
  niet klopt met jouw specifieke situatie.

## 2. Waarom je AI-antwoorden altijd controleert

Als toekomstig uitvoerder of leidinggevende neem jij de verantwoordelijkheid
voor wat je doorstuurt naar je team, opdrachtgever of onderaannemer — niet
de AI.

<x-compare>
<x-compare-item title="Zonder controle">

Je kopieert een door AI gegenereerde planning direct naar je team. Er blijkt
een verkeerde aanname over de droogtijd van beton in te zitten. Het team
plant de volgende fase te vroeg in.

</x-compare-item>
<x-compare-item title="Met controle">

Je gebruikt de AI-planning als startpunt, controleert de aannames (droogtijd,
weersafhankelijkheid, afstemming met andere disciplines) en past aan waar
nodig voordat je hem deelt.

</x-compare-item>
</x-compare>

**Vuistregel: AI is een startpunt, geen eindpunt.** Gebruik het om sneller
op gang te komen, niet om het laatste woord te hebben.

Dit geldt extra hard bij:

- **Planningen** — foutieve aannames leiden tot vertraging of onveilige
  volgordes van werk.
- **Werkinstructies** — een onduidelijke of onjuiste instructie kan tot
  fouten of onveilige situaties leiden.
- **Veiligheidsrapportages** — hier is controle niet optioneel: mensen
  kunnen letterlijk gewond raken als een risico verkeerd wordt ingeschat.

### Wat je niet in een AI-tool invoert

<x-callout type="danger">
Alles wat je in een publieke AI-tool typt, kan buiten jouw organisatie
terechtkomen of gebruikt worden om het model te verbeteren. Vertrouwelijke
of persoonsgebonden informatie hoort daar niet in.
</x-callout>

Deel dus geen:

- Persoonsgegevens van collega's of medewerkers (namen in combinatie met
  bijvoorbeeld verzuim, functioneren of BSN).
- Vertrouwelijke bedrijfsinformatie, zoals prijsafspraken, offertes of
  interne kostprijzen.
- Nog niet gepubliceerde tekeningen, BIM-modellen of ontwerpen zonder
  toestemming van de opdrachtgever.
- Informatie die concurrentiegevoelig is voor je opdrachtgever of bedrijf.

Twijfel je? Beschrijf de situatie algemeen (zonder namen, project- of
bedrijfsgegevens) in plaats van de originele documenten of gegevens te
kopiëren.

### Eerlijk vermelden dat je AI hebt gebruikt

Verantwoord AI-gebruik is niet alleen controleren — het is ook eerlijk zijn
over wat je hebt gedaan. Gebruik je AI als hulpmiddel bij een planning,
rapportage, werkinstructie of e-mail? Vermeld dat dan, volgens de afspraken
van je opleiding of werkgever.

<x-callout type="info">
AI gebruiken als hulpmiddel mag. Het ongecontroleerd overnemen van
AI-tekst en presenteren alsof het volledig je eigen werk is, niet — ook al
heb je er zelf niets aan veranderd.
</x-callout>

## 3. De vier bouwstenen van een goede prompt

Een vage vraag levert een vaag antwoord op. Bouw je prompt op met deze vier
onderdelen en de kwaliteit van het antwoord gaat direct omhoog:

- **Rol** — wie moet de AI zijn? Bijvoorbeeld: *"Je bent een ervaren
  uitvoerder in de woningbouw."*
- **Context** — wat is de situatie? Project, fase, doelgroep, relevante
  omstandigheden.
- **Taak** — wat moet er precies gebeuren? Hoe concreter, hoe beter.
- **Vorm** — hoe moet het antwoord eruitzien? Lengte, toon, opmaak, taal.

<x-compare>
<x-compare-item title="Zwakke prompt">

"Schrijf een planning voor mijn bouwproject."

</x-compare-item>
<x-compare-item title="Sterke prompt (met de 4 bouwstenen)">

"Je bent een ervaren uitvoerder in de utiliteitsbouw. We lopen 3 dagen
vertraging op bij het storten van de begane grondvloer door regen. Stel een
bijgestelde weekplanning op voor de komende twee weken, waarin je rekening
houdt met de droogtijd van het beton en de aansluitende werkzaamheden van de
elektrapartij. Presenteer het antwoord als een overzichtelijke tabel per
dag, in het Nederlands."

</x-compare-item>
</x-compare>

Het verschil zit 'm niet in "slimmer typen" — het zit in **volledigheid**.
Hoe meer relevante informatie je meegeeft, hoe minder de AI hoeft te
gokken.

<x-callout type="tip">
Niet tevreden met het antwoord? Voeg ontbrekende context toe of stel een
vervolgvraag. Een prompt hoeft niet in één keer perfect te zijn.
</x-callout>

## 4. Werken in duo's: opsteller en controleur

Bij de opdrachten waarin je zelf een prompt schrijft, werk je met vaste
rollen — dat maakt "controle" (zie onderdeel 2) iets wat je samen echt
oefent, niet iets wat je alleen leest:

- **Opsteller** — schrijft de prompt en werkt met de AI.
- **Controleur** — leest actief mee en bewaakt de kwaliteit: klopt dit,
  mist er iets, is dit veilig om te delen?

Wissel na elke opdracht van rol. Geef elkaar daarna kort **tips & tops**:
één ding dat goed ging in de prompt of de controle, en één ding dat
scherper had gekund.

Ga hierna aan de slag met de opdrachten — die bouwen alle onderdelen
hierboven stap voor stap in de praktijk.
