---
title: "InvalidFormatException"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Die Ausnahme, die ausgelöst wird, wenn der Benutzer versucht, ein Dokument mit formatbezogenen Optionen zu öffnen, die mit dem ursprünglichen Dokumentformat nicht kompatibel sind."
type: docs
weight: 15
url: /de/java/com.groupdocs.editor/invalidformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public final class InvalidFormatException extends RuntimeException
```

Die Ausnahme, die ausgelöst wird, wenn der Benutzer versucht, ein Dokument zu öffnen mit
formatbezogenen Optionen, die mit dem ursprünglichen Dokumentformat nicht kompatibel sind.


*** ** * ** ***

Beispielsweise wird diese Ausnahme ausgelöst, wenn versucht wird, ein Spreadsheet-Dokument mit WordProcessing-Dokumentoptionen zu öffnen.

<br />


## Konstruktoren

| Konstruktor | Beschreibung |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String |  |

### InvalidFormatException(String message, RuntimeException inner) {#InvalidFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFormatException(String message, RuntimeException inner)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| message | java.lang.String |  |
| inner | java.lang.RuntimeException |  |

