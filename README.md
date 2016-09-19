# Wikipedia-API

##Special Export
Here you can export pages to xml, either by adding the name of the page or taking a category and add all pages of the category by a push of a buttion (e.g. Category:Communes_of_Tunisia will add all pages of tunisian communes)

####Links
#####German
https://de.wikipedia.org/wiki/Spezial:Exportieren
#####English
https://en.wikipedia.org/wiki/Special:Export/
#####Italian
https://it.wikipedia.org/wiki/Speciale:Esporta
#####French
https://fr.wikipedia.org/wiki/Sp%C3%A9cial:Exporter
#####Spanish
https://es.wikipedia.org/wiki/Especial:Exportar
#####Portugese
https://pt.wikipedia.org/wiki/Especial:Exportar
#####Turkish
https://tr.wikipedia.org/wiki/%C3%96zel:D%C4%B1%C5%9FaAktar
#####Polish
https://pl.wikipedia.org/wiki/Specjalna:Eksport

##API Sandbox
#### Links (Keep in mind that only one language version of wikipedia will be queried)
https://en.wikipedia.org/wiki/Special:ApiSandbox

https://de.wikipedia.org/wiki/Special:ApiSandbox

#### Query Examples
##### Category Pages - Extract elements of a category e.g. Communes of Tunisia:

https://en.wikipedia.org/w/api.php?
action=query&
format=xml&
maxlag=10&
list=categorymembers&
cmtitle=Category%3ACommunes_of_Tunisia&
cmlimit=500
