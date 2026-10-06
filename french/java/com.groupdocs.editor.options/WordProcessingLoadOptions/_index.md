---
title: "WordProcessingLoadOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Contient des options pour charger des documents WordProcessing compatibles Word tels que DOCX, RTF, ODT, etc."
type: docs
weight: 45
url: /fr/java/com.groupdocs.editor.options/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class WordProcessingLoadOptions implements ILoadOptions
```

Contient des options pour charger des documents WordProcessing (compatibles Word) tels que
DOC(X), RTF, ODT, etc. dans la classe Editor

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour |
ouverture du document WordProcessing, s'il est encodé.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour |
ouverture du document WordProcessing, s'il est encodé.
|
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour
ouverture du document WordProcessing, s'il est encodé. Définir sur NULL ou vide
chaîne afin de ne pas utiliser le mot de passe (valeur par défaut).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour
ouverture du document WordProcessing, s'il est encodé. Définir sur NULL ou vide
chaîne afin de ne pas utiliser le mot de passe (valeur par défaut).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

