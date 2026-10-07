---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "De uitzondering die wordt gegooid wanneer een gebruiker probeert een document te openen met formatspecifieke opties die niet compatibel zijn met het oorspronkelijke documentformaat."
type: docs
weight: 15
url: /nl/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

De uitzondering die wordt gegooid wanneer een gebruiker probeert een document te openen met
formatspecifieke opties die niet compatibel zijn met het oorspronkelijke documentformaat.


*** ** * ** ***

Bijvoorbeeld, deze uitzondering wordt gegooid als men probeert een Spreadsheet-document te openen met WordProcessing-documentopties.

<br />


## Constructors

| Constructor | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String |  |
| inner | java.lang.RuntimeException |  |

