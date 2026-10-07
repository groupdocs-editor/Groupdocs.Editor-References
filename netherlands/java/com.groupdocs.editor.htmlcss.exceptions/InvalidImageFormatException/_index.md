---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "De uitzondering die wordt gegooid wanneer geprobeerd wordt om op een of andere manier inhoud te openen, laden, opslaan of verwerken die vermoedelijk een raster‑ of vectorafbeelding is, maar eigenlijk een afbeelding van onverwacht type is of helemaal geen afbeelding."
type: docs
weight: 11
url: /nl/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

De uitzondering die wordt gegooid wanneer geprobeerd wordt te openen, laden, opslaan of verwerken
op een of andere manier andere inhoud, die vermoedelijk een afbeelding (raster of vector) is,
maar eigenlijk een afbeelding van onverwacht type is of helemaal geen afbeelding.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Maakt een nieuw exemplaar van InvalidImageFormatException met het opgegeven foutbericht |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Maakt een nieuw exemplaar van InvalidImageFormatException met het opgegeven foutbericht en een verwijzing naar de innerException die de oorzaak van deze uitzondering is |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Maakt een nieuw exemplaar van InvalidImageFormatException met het opgegeven foutbericht


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bericht | java.lang.String | Tekstbericht, dat de fout beschrijft, kan null of leeg zijn |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Maakt een nieuw exemplaar van InvalidImageFormatException met het opgegeven foutbericht en een verwijzing naar de innerException die de oorzaak van deze uitzondering is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bericht | java.lang.String | Tekstbericht, dat de fout beschrijft, kan null of leeg zijn |
|
|  | innerException | java.lang.RuntimeException | De uitzondering die de oorzaak is van de huidige uitzondering, of een null‑referentie als geen innerException is opgegeven. |
|

