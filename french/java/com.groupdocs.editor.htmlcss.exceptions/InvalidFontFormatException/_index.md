---
title: "InvalidFontFormatException"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "L'exception qui est levée lorsqu'on essaie d'ouvrir, charger, enregistrer ou traiter d'une manière quelconque un contenu qui est supposément une police d'un format connu et pris en charge mais qui est en réalité une police d'un format non pris en charge ou inattendu ou qui n'est pas du tout une police."
type: docs
weight: 10
url: /fr/java/com.groupdocs.editor.htmlcss.exceptions/invalidfontformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidFontFormatException extends RuntimeException
```

L'exception qui est levée lorsqu'on essaie d'ouvrir, charger, enregistrer ou traiter d'une manière quelconque un contenu, qui est supposément une police d'un format pris en charge (connu), mais qui est en réalité une police d'un format non pris en charge ou inattendu, ou qui n'est pas du tout une police.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [InvalidFontFormatException(String message)](#InvalidFontFormatException-java.lang.String-) | Crée une nouvelle instance avec le message d'erreur spécifié |
|
|  | [InvalidFontFormatException(String message, RuntimeException innerException)](#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-) | Crée une nouvelle instance de @see \"InvalidFontFormatException\" avec le message d'erreur spécifié et une référence à l'exception interne qui est la cause de cette exception |
|
### InvalidFontFormatException(String message) {#InvalidFontFormatException-java.lang.String-}
```
public InvalidFontFormatException(String message)
```


Crée une nouvelle instance avec le message d'erreur spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Message textuel, qui décrit l'erreur, peut être nul ou vide |
|

### InvalidFontFormatException(String message, RuntimeException innerException) {#InvalidFontFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidFontFormatException(String message, RuntimeException innerException)
```


Crée une nouvelle instance de @see \"InvalidFontFormatException\" avec le message d'erreur spécifié et une référence à l'exception interne qui est la cause de cette exception


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Message textuel, qui décrit l'erreur, peut être nul ou vide |
|
|  | innerException | java.lang.RuntimeException | L'exception qui est la cause de l'exception actuelle, ou une référence nulle si aucune exception interne n'est spécifiée. |
|

