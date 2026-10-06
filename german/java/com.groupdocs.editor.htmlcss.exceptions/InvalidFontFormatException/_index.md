---
title: "InvalidFontFormatException"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Die Ausnahme, die ausgelöst wird, wenn versucht wird, irgendeinen Inhalt zu öffnen, zu laden, zu speichern oder zu verarbeiten, der vermutlich eine Schriftart in einem unterstützten bekannten Format ist, aber tatsächlich eine Schriftart in einem nicht unterstützten oder unerwarteten Format oder überhaupt keine Schriftart ist."
type: docs
weight: 10
url: /de/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

Die Ausnahme, die ausgelöst wird, wenn versucht wird, irgendeinen Inhalt zu öffnen, zu laden, zu speichern oder anderweitig zu verarbeiten, der vermutlich eine Schriftart in einem unterstützten (bekannten) Format ist, tatsächlich jedoch eine Schriftart in einem nicht unterstützten oder unerwarteten Format oder überhaupt keine Schriftart ist.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Erstellt eine neue Instanz von mit der angegebenen Fehlermeldung |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Erstellt eine neue Instanz von @see \"InvalidFontFormatException\" mit der angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Erstellt eine neue Instanz von mit der angegebenen Fehlermeldung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Textnachricht, die den Fehler beschreibt, kann null oder leer sein |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Erstellt eine neue Instanz von @see \"InvalidFontFormatException\" mit der angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die die Ursache dieser Ausnahme ist


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | message | java.lang.String | Textnachricht, die den Fehler beschreibt, kann null oder leer sein |
|
|  | innerException | java.lang.RuntimeException | Die Ausnahme, die die Ursache der aktuellen Ausnahme ist, oder ein Nullverweis, wenn keine innere Ausnahme angegeben ist. |
|

