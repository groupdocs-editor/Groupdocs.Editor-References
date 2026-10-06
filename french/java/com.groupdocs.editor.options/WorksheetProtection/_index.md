---
title: "WorksheetProtection"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Encapsule les options de protection de feuille de calcul qui permettent de protéger une feuille de calcul dans le document Spreadsheet de sortie contre toute modification d'un type spécifié avec un mot de passe spécifié."
type: docs
weight: 49
url: /fr/java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Encapsule les options de protection de feuille de calcul, qui permettent de protéger une feuille de calcul
dans le document Spreadsheet de sortie contre toute modification d'un type spécifié avec un
mot de passe spécifié.


*** ** * ** ***

La plupart des formats Spreadsheet comme XLSX permettent de protéger une feuille de calcul contre la modification avec un mot de passe. Cette classe permet d'activer cette protection et de spécifier ses options.

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Crée une nouvelle instance avec les paramètres par défaut. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Crée une nouvelle instance avec le type de protection de feuille de calcul spécifié et |
mot de passe
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Permet de spécifier un type de protection de feuille de calcul. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Permet de spécifier un type de protection de feuille de calcul. |
|
|  | [getPassword()](#getPassword--) | Mot de passe, qui est utilisé pour protéger une feuille de calcul. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Mot de passe, qui est utilisé pour protéger une feuille de calcul. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Crée une nouvelle instance avec les paramètres par défaut. Si elle n'est pas modifiée et transmise
à SpreadsheetSaveOptions, aucune protection de feuille de calcul ne sera appliquée


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Crée une nouvelle instance avec le type de protection de feuille de calcul spécifié et
mot de passe


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | protectionType | int | Type de protection de feuille de calcul |
|
|  | mot de passe | java.lang.String | Mot de passe, qui verrouille la protection |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Permet de spécifier un type de protection de feuille de calcul. Par défaut, c'est 'None' -
la protection n'est pas appliquée.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Permet de spécifier un type de protection de feuille de calcul. Par défaut, c'est 'None' -
la protection n'est pas appliquée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Mot de passe, qui est utilisé pour protéger une feuille de calcul. Si NULL ou vide
chaîne, la protection ne sera pas appliquée.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Mot de passe, qui est utilisé pour protéger une feuille de calcul. Si NULL ou vide
chaîne, la protection ne sera pas appliquée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

