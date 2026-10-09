---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Undantaget som kastas när man försöker öppna, läsa in, spara eller bearbeta på något sätt något innehåll som förmodligen är ett typsnitt i ett stödd känt format men som faktiskt är ett typsnitt i ett icke‑stödd eller oväntat format eller inte är ett typsnitt alls."
type: docs
weight: 10
url: /sv/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

Undantaget som kastas när man försöker öppna, läsa in, spara eller på annat sätt bearbeta något innehåll som antas vara ett teckensnitt i ett stödjat (känt) format, men som i själva verket är ett teckensnitt i ett icke‑stödjat eller oväntat format eller inte är ett teckensnitt alls.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Skapar en ny instans av med angivet felmeddelande |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Skapar en ny instans av @see "InvalidFontFormatException" med angivet felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Skapar en ny instans av med angivet felmeddelande


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Textmeddelande som beskriver felet, kan vara null eller tomt |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Skapar en ny instans av @see "InvalidFontFormatException" med angivet felmeddelande och en referens till det inre undantaget som är orsaken till detta undantag


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | meddelande | java.lang.String | Textmeddelande som beskriver felet, kan vara null eller tomt |
|
|  | innerException | java.lang.RuntimeException | Undantaget som är orsaken till det aktuella undantaget, eller en null-referens om inget inre undantag har angetts. |
|

