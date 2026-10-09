---
title: "InvalidImageFormatException"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "L'exception qui est levée lorsqu'on essaie d'ouvrir, charger, enregistrer ou traiter d'une manière ou d'une autre un contenu qui est supposé être une image raster ou vectorielle mais qui est en réalité une image d'un type inattendu ou qui n'est pas du tout une image."
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.htmlcss.exceptions/invalidimageformatexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException
```
public class InvalidImageFormatException extends RuntimeException
```

L'exception qui est levée lorsqu'on essaie d'ouvrir, charger, enregistrer ou traiter
d'une manière ou d'une autre un contenu, qui est supposé être une image (raster ou vectorielle),
mais qui est en réalité une image d'un type inattendu ou qui n'est pas du tout une image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [InvalidImageFormatException(String message)](#InvalidImageFormatException-java.lang.String-) | Crée une nouvelle instance de InvalidImageFormatException avec le message d'erreur spécifié |
|
|  | [InvalidImageFormatException(String message, RuntimeException innerException)](#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-) | Crée une nouvelle instance de InvalidImageFormatException avec le message d'erreur spécifié et une référence à l'exception interne qui est la cause de cette exception |
|
### InvalidImageFormatException(String message) {#InvalidImageFormatException-java.lang.String-}
```
public InvalidImageFormatException(String message)
```


Crée une nouvelle instance de InvalidImageFormatException avec le message d'erreur spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Message textuel, qui décrit l'erreur, peut être nul ou vide |
|

### InvalidImageFormatException(String message, RuntimeException innerException) {#InvalidImageFormatException-java.lang.String-java.lang.RuntimeException-}
```
public InvalidImageFormatException(String message, RuntimeException innerException)
```


Crée une nouvelle instance de InvalidImageFormatException avec le message d'erreur spécifié et une référence à l'exception interne qui est la cause de cette exception


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | message | java.lang.String | Message textuel, qui décrit l'erreur, peut être nul ou vide |
|
|  | innerException | java.lang.RuntimeException | L'exception qui est la cause de l'exception actuelle, ou une référence nulle si aucune exception interne n'est spécifiée. |
|

