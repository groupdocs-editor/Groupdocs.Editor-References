---
title: "PdfLoadOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Contient des options pour charger des documents PDF dans la classe Editor"
type: docs
weight: 30
url: /fr/nodejs-java/com.groupdocs.editor.options/pdfloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class PdfLoadOptions implements ILoadOptions
```

Contient des options pour charger des documents PDF dans la classe Editor

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfLoadOptions()](#PdfLoadOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour ouvrir un document PDF, s'il est chiffré. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour ouvrir un document PDF, s'il est chiffré. |
|
### PdfLoadOptions() {#PdfLoadOptions--}
```
public PdfLoadOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour ouvrir un document PDF, s'il est chiffré.
Définir sur NULL ou chaîne vide afin de ne pas utiliser le mot de passe (valeur par défaut).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour ouvrir un document PDF, s'il est chiffré.
Définir sur NULL ou chaîne vide afin de ne pas utiliser le mot de passe (valeur par défaut).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

