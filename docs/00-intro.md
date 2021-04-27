# Introductie
De idee is om een eigen Knowledge Graph concept op te zetten. Op dit moment is het nogal organisch gegroeid en bevat het niet veel meer dan:
* een shell script om heel basaal entities te creëren (YML + .md files)
* een HUGO theme om de webpagina's en JSON-files te genereren

Het genereren van de YML-files moet een stuk efficiënter kunnen, zoals bijvoorbeeld het scrapen van content uit:
* Wikidata
* Wikipedia
* Google Maps
* Google Knowledge Graph
* Geonames
* Kamer van Koophandel
* Drimble
* Telefoonboek
* Zorgkaartnederland
* en andere bronnen

Daarnaast zou het mooi zijn om een interface te hebben, waarin de entities kunnen worden:
* Gecreëerd
* Gevuld
* Verwijderd
* Aangepast
* Gelinkt (2 kanten op)
* Zoeken van orphan entities (die dus nog niet zijn gelinkt)

Het creëren van entities moet kunnen op basis van templates, zodat de kans op het vergeten van velden kan worden verminderd. Wellicht een idee om hiervoor de velden uit schema.org als default te gebruiken.
