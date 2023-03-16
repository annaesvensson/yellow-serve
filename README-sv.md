<p align="right"><a href="README-de.md">Deutsch</a> &nbsp; <a href="README.md">English</a> &nbsp; <a href="README-sv.md">Svenska</a></p>

# Serve 0.8.22

Inbyggd webbserver.

<p align="center"><img src="serve-screenshot.png?raw=true" alt="Skärmdump"></p>

## Hur man installerar ett tillägg

[Ladda ner ZIP-filen](https://github.com/annaesvensson/yellow-serve/archive/main.zip) och kopiera den till din `system/extensions` mapp. [Läs mer om tillägg](https://github.com/annaesvensson/yellow-update/tree/main/README-sv.md).

## Hur man startar en webbserver

Du kan starta inbyggda webbservern på [kommandoraden](https://github.com/annaesvensson/yellow-command/tree/main/README-sv.md). Den inbyggda webbservern är praktisk för utvecklare, formgivare och översättare. Detta ger dig möjlighet att redigera webbsidor på din dator och ladda upp dem till din webbserver senare. Öppna ett terminalfönster. Gå till installationsmappen där filen `yellow.php` finns. Skriv `php yellow.php serve`, du kan valfritt ange en URL. Öppna en webbläsare och gå till URL:en som visas.

## Exempel

Starta inbyggda webbservern på kommandoraden:

`php yellow.php serve`  

Starta inbyggda webbservern på kommandoraden, olika URL:

`php yellow.php serve http://localhost:8000/`  
`php yellow.php serve http://localhost:8080/`  
`php yellow.php serve http://localhost:8888/`  

## Utvecklare

Anna Svensson. [Få hjälp](https://datenstrom.se/sv/yellow/help/).
