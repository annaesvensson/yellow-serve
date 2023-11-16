<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Serve 0.8.24

Inbyggd webbserver.

<p align="center"><img src="SCREENSHOT.png?raw=true" alt="Skärmdump"></p>

## Hur man installerar ett tillägg

[Ladda ner ZIP-filen](https://github.com/annaesvensson/yellow-serve/archive/refs/heads/main.zip) och kopiera den till din `system/extensions` mapp. [Läs mer om tillägg](https://github.com/annaesvensson/yellow-update/tree/main/README-sv.md).

## Hur man startar en webbserver

Du kan starta en webbserver på [kommandoraden](https://github.com/annaesvensson/yellow-core/tree/main/README-sv.md). Den inbyggda webbservern är praktisk för utvecklare, formgivare och översättare. Detta ger dig möjlighet att visa webbsidor på din dator, granska dem och ladda upp dem till den externa webbservern senare. Öppna ett terminalfönster. Gå till installationsmappen där filen `yellow.php` finns. Skriv `php yellow.php serve`, du kan valfritt ange en URL. Öppna en webbläsare och gå till URL:en som visas.

## Exempel

Starta webbserver på kommandoraden:

`php yellow.php serve`  

Starta webbserver på kommandoraden, olika URL:

`php yellow.php serve http://localhost:8000/`  
`php yellow.php serve http://localhost:8080/`  
`php yellow.php serve http://localhost:8888/`  

## Utvecklare

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
