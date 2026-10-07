---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "De uitzondering die wordt gegooid wanneer geprobeerd wordt om op een of andere manier inhoud te openen, laden, opslaan of verwerken die vermoedelijk een lettertype van een ondersteund bekend formaat is, maar eigenlijk een lettertype van een niet‑ondersteund of onverwacht formaat is of helemaal geen lettertype."
type: docs
weight: 10
url: /nl/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

De uitzondering die wordt gegooid bij het proberen te openen, laden, opslaan of op een andere manier verwerken van bepaalde inhoud, die vermoedelijk een lettertype van een ondersteund (bekend) formaat is, maar in werkelijkheid een lettertype van een niet‑ondersteund of onverwacht formaat is of helemaal geen lettertype.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Maakt een nieuw exemplaar aan met het opgegeven foutbericht |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Maakt een nieuw exemplaar van @see \"InvalidFontFormatException\" met het opgegeven foutbericht en een verwijzing naar de innerException die de oorzaak van deze uitzondering is |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Maakt een nieuw exemplaar aan met het opgegeven foutbericht


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bericht | java.lang.String | Tekstbericht, dat de fout beschrijft, kan null of leeg zijn |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Maakt een nieuw exemplaar van @see \"InvalidFontFormatException\" met het opgegeven foutbericht en een verwijzing naar de innerException die de oorzaak van deze uitzondering is


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | bericht | java.lang.String | Tekstbericht, dat de fout beschrijft, kan null of leeg zijn |
|
|  | innerException | java.lang.RuntimeException | De uitzondering die de oorzaak is van de huidige uitzondering, of een null‑referentie als geen innerException is opgegeven. |
|

