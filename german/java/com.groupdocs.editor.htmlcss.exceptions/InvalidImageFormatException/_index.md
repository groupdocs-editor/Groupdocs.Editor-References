---
title: "InvalidImageFormatException"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Die Ausnahme, die ausgelöst wird, wenn versucht wird, irgendeinen Inhalt zu öffnen, zu laden, zu speichern oder zu verarbeiten, der vermutlich ein Bild (Raster oder Vektor) ist, aber tatsächlich ein Bild unerwarteten Typs oder überhaupt kein Bild ist."
type: docs
weight: 11
url: /de/java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

Die Ausnahme, die ausgelöst wird, wenn versucht wird, zu öffnen, zu laden, zu speichern oder zu verarbeiten
irgendein anderer Inhalt, der vermutlich ein Bild (Raster oder Vektor) ist,
der jedoch tatsächlich ein Bild unerwarteten Typs oder überhaupt kein Bild ist.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Erstellt eine neue Instanz von InvalidImageFormatException mit der angegebenen Fehlermeldung |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Erstellt eine neue Instanz von InvalidImageFormatException mit der angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Erstellt eine neue Instanz von InvalidImageFormatException mit der angegebenen Fehlermeldung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Textnachricht, die den Fehler beschreibt, kann null oder leer sein |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Erstellt eine neue Instanz von InvalidImageFormatException mit der angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Textnachricht, die den Fehler beschreibt, kann null oder leer sein |
|
|  | innerException | java.lang.RuntimeException | Die Ausnahme, die die Ursache der aktuellen Ausnahme ist, oder ein Nullverweis, wenn keine innere Ausnahme angegeben ist. |
|

