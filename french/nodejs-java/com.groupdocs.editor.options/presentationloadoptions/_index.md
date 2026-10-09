---
title: "PresentationLoadOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Permet de spécifier des options personnalisées pour charger des documents de tous les formats de présentation pris en charge, tels que PPTX, PPTM, PPSX, etc."
type: docs
weight: 33
url: /fr/nodejs-java/com.groupdocs.editor.options/presentationloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public class PresentationLoadOptions implements ILoadOptions
```

Permet de spécifier des options personnalisées pour charger des documents de tous les formats pris en charge
Formats de présentation tels que PPT(X), PPTM, PPS(X), etc.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PresentationLoadOptions()](#PresentationLoadOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour |
ouverture du document Presentation, s'il est encodé.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour |
ouverture du document Presentation, s'il est encodé.
|
### PresentationLoadOptions() {#PresentationLoadOptions--}
```
public PresentationLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour
ouverture du document Presentation, s'il est encodé. Définir sur NULL ou vide
chaîne afin de supprimer le mot de passe.


*** ** * ** ***

Par défaut, cette propriété a la valeur NULL — le mot de passe n'est pas défini. Si le document Presentation d'entrée est protégé par un mot de passe, le mot de passe est obligatoire et une exception sera levée si le mot de passe n'est pas spécifié ou est invalide. Si le document Presentation d'entrée n'est PAS protégé par un mot de passe, mais qu'un mot de passe est défini, il sera ignoré.

<br />



**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour
ouverture du document Presentation, s'il est encodé. Définir sur NULL ou vide
chaîne afin de supprimer le mot de passe.


*** ** * ** ***

Par défaut, cette propriété a la valeur NULL — le mot de passe n'est pas défini. Si le document Presentation d'entrée est protégé par un mot de passe, le mot de passe est obligatoire et une exception sera levée si le mot de passe n'est pas spécifié ou est invalide. Si le document Presentation d'entrée n'est PAS protégé par un mot de passe, mais qu'un mot de passe est défini, il sera ignoré.

<br />



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

