---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Undantaget som kastas när användaren försöker öppna ett dokument med format‑specifika alternativ som är inkompatibla med originaldokumentets format."
type: docs
weight: 15
url: /sv/nodejs-java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

Undantaget som kastas när användaren försöker öppna ett dokument med
format‑specifika alternativ som är inkompatibla med originaldokumentets format.


*** ** * ** ***

Till exempel kommer detta undantag att kastas om man försöker öppna ett kalkylbladsdokument med ordbehandlingsdokumentalternativ.

<br />


## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [InvalidFormatException()](#InvalidFormatException--) |  |
| [InvalidFormatException(String message)](#InvalidFormatException-java.lang.String-) |  |
| [InvalidFormatException(String message, RuntimeException inner)](#InvalidFormatException-java.lang.String-java.lang.RuntimeException-) |  |
### InvalidFormatException() {#InvalidFormatException--}
```
public InvalidFormatException()
```


### InvalidFormatException(String message) {#InvalidFormatException-java.lang.String-}
```
public InvalidFormatException(String message)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meddelande | java.lang.String |  |
| inre | java.lang.RuntimeException |  |

