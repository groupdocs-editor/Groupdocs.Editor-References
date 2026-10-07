---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Undantaget som kastas när man försöker öppna, läsa in, spara eller bearbeta på något sätt annat innehåll som antagligen är en bild (raster eller vektor) men som faktiskt är en bild av oväntad typ eller inte en bild alls."
type: docs
weight: 11
url: /sv/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

Undantaget som kastas när man försöker öppna, läsa in, spara eller bearbeta
på något annat sätt något innehåll, som antagligen är en bild (raster eller vektor),
men som faktiskt är en bild av oväntad typ eller inte en bild alls.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Skapar en ny instans av InvalidImageFormatException med angivet felmeddelande |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Skapar en ny instans av InvalidImageFormatException med angivet felmeddelande och en referens till den inre undantaget som är orsaken till detta undantag |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Skapar en ny instans av InvalidImageFormatException med angivet felmeddelande


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Textmeddelande som beskriver felet, kan vara null eller tomt |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Skapar en ny instans av InvalidImageFormatException med angivet felmeddelande och en referens till den inre undantaget som är orsaken till detta undantag


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Textmeddelande som beskriver felet, kan vara null eller tomt |
|
|  | innerException | java.lang.RuntimeException | Undantaget som är orsaken till det aktuella undantaget, eller en null-referens om inget inre undantag har angetts. |
|

