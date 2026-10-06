---
title: "PresentationLoadOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Permet de spécifier des options personnalisées pour le chargement des documents de tous les formats de présentation pris en charge, tels que PPTX, PPTM, PPSX, etc."
type: docs
weight: 33
url: /fr/java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Permet de spécifier des options personnalisées pour le chargement des documents de tous les formats pris en charge
Formats de présentation tels que PPT(X), PPTM, PPS(X), etc.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour |
ouvrir le document de présentation, s'il est encodé.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour |
ouvrir le document de présentation, s'il est encodé.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour
ouvrir le document de présentation, s'il est encodé. Définir sur NULL ou vide
chaîne afin de supprimer le mot de passe.


*** ** * ** ***

Par défaut, cette propriété a la valeur NULL \\u2014 le mot de passe n'est pas défini. Si le document de présentation d'entrée est protégé par un mot de passe, le mot de passe est obligatoire et une exception sera levée si le mot de passe n'est pas spécifié ou est invalide. Si le document de présentation d'entrée n'est PAS protégé par un mot de passe, mais qu'un mot de passe est défini, il sera ignoré.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour
ouvrir le document de présentation, s'il est encodé. Définir sur NULL ou vide
chaîne afin de supprimer le mot de passe.


*** ** * ** ***

Par défaut, cette propriété a la valeur NULL \\u2014 le mot de passe n'est pas défini. Si le document de présentation d'entrée est protégé par un mot de passe, le mot de passe est obligatoire et une exception sera levée si le mot de passe n'est pas spécifié ou est invalide. Si le document de présentation d'entrée n'est PAS protégé par un mot de passe, mais qu'un mot de passe est défini, il sera ignoré.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

