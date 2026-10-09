---
title: "SpreadsheetLoadOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Contient des options pour charger des documents binaires Spreadsheet Cells compatibles Excel tels que XLSX, ODS, etc."
type: docs
weight: 36
url: /fr/nodejs-java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Contient des options pour charger des fichiers binaires Spreadsheet (Cells, compatibles Excel)
documents tels que XLS(X), ODS, etc. dans la classe Editor

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Constructeur par défaut sans paramètres - tous les paramètres ont des valeurs par défaut |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour |
ouverture du document Spreadsheet, s'il est encodé.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour |
ouverture du document Spreadsheet, s'il est encodé.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Active les mécanismes d'optimisation de la mémoire pendant le traitement du document d'entrée, |
ce qui peut dégrader les performances dans certains cas particuliers, mais d'autre part
diminue l'utilisation de la mémoire.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Active les mécanismes d'optimisation de la mémoire pendant le traitement du document d'entrée, |
ce qui peut dégrader les performances dans certains cas particuliers, mais d'autre part
diminue l'utilisation de la mémoire.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Constructeur par défaut sans paramètres - tous les paramètres ont des valeurs par défaut


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour
ouverture du document Spreadsheet, s'il est encodé. Défini sur NULL ou vide
chaîne afin de ne pas utiliser le mot de passe (valeur par défaut).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permet de spécifier, modifier et obtenir le mot de passe, qui sera utilisé pour
ouverture du document Spreadsheet, s'il est encodé. Défini sur NULL ou vide
chaîne afin de ne pas utiliser le mot de passe (valeur par défaut).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Active les mécanismes d'optimisation de la mémoire pendant le traitement du document d'entrée,
ce qui peut dégrader les performances dans certains cas particuliers, mais d'autre part
diminue l'utilisation de la mémoire. Utile lors du traitement de très gros documents et
en cas d'OutOfMemoryException. La valeur par défaut est false (l'optimisation de la mémoire est
désactivée afin d'obtenir de meilleures performances).


**Returns:**
booléen
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Active les mécanismes d'optimisation de la mémoire pendant le traitement du document d'entrée,
ce qui peut dégrader les performances dans certains cas particuliers, mais d'autre part
diminue l'utilisation de la mémoire. Utile lors du traitement de très gros documents et
en cas d'OutOfMemoryException. La valeur par défaut est false (l'optimisation de la mémoire est
désactivée afin d'obtenir de meilleures performances).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

