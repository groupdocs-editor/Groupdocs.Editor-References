---
title: "DelimitedTextEditOptions"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Options de chargement des documents Spreadsheet basés sur du texte (CSV, à base d'onglets, etc.) qui utilisent un séparateur"
type: docs
weight: 10
url: /fr/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Options de chargement des documents Spreadsheet basés sur du texte (CSV, à base d'onglets, etc.),
qui utilisent un séparateur (délimiteur)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Crée une instance de la classe d'options pour le texte délimité avec le |
séparateur (délimiteur)
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents basés sur du texte |
documents Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents basés sur du texte |
documents Spreadsheet
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Obtient ou définit une valeur indiquant si la chaîne dans les documents basés sur du texte |
est convertie en données de date.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Obtient ou définit une valeur indiquant si la chaîne dans les documents basés sur du texte |
est convertie en données de date.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Obtient ou définit une valeur indiquant si la chaîne dans les documents basés sur du texte |
est convertie en données numériques.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Obtient ou définit une valeur indiquant si la chaîne dans les documents basés sur du texte |
est convertie en données numériques.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Définit si les délimiteurs consécutifs doivent être traités comme un seul. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Définit si les délimiteurs consécutifs doivent être traités comme un seul. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Active les mécanismes d'optimisation de la mémoire pendant le traitement du document d'entrée, |
ce qui peut dégrader les performances dans certains cas particuliers, mais d'autre part
réduire manuellement l'utilisation de la mémoire.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Active les mécanismes d'optimisation de la mémoire pendant le traitement du document d'entrée, |
ce qui peut dégrader les performances dans certains cas particuliers, mais d'autre part
réduire manuellement l'utilisation de la mémoire.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Crée une instance de la classe d'options pour le texte délimité avec le
séparateur (délimiteur)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | séparateur | java.lang.String | Séparateur obligatoire (délimiteur), qui ne peut pas être NULL ou vide |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents basés sur du texte
documents Spreadsheet


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents basés sur du texte
documents Spreadsheet


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Obtient ou définit une valeur indiquant si la chaîne dans les documents basés sur du texte
Le document est converti en données de date. La valeur par défaut est false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Obtient ou définit une valeur indiquant si la chaîne dans les documents basés sur du texte
Le document est converti en données de date. La valeur par défaut est false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Obtient ou définit une valeur indiquant si la chaîne dans les documents basés sur du texte
Le document est converti en données numériques. La valeur par défaut est false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Obtient ou définit une valeur indiquant si la chaîne dans les documents basés sur du texte
Le document est converti en données numériques. La valeur par défaut est false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Définit si les délimiteurs consécutifs doivent être traités comme un seul. Par
La valeur par défaut est false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Définit si les délimiteurs consécutifs doivent être traités comme un seul. Par
La valeur par défaut est false.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Active les mécanismes d'optimisation de la mémoire pendant le traitement du document d'entrée,
ce qui peut dégrader les performances dans certains cas particuliers, mais d'autre part
réduire manuellement l'utilisation de la mémoire. Utile lors du traitement de documents volumineux et
en cas d'OutOfMemoryException. La valeur par défaut est false (l'optimisation de la mémoire est
désactivée afin d'améliorer les performances).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Active les mécanismes d'optimisation de la mémoire pendant le traitement du document d'entrée,
ce qui peut dégrader les performances dans certains cas particuliers, mais d'autre part
réduire manuellement l'utilisation de la mémoire. Utile lors du traitement de documents volumineux et
en cas d'OutOfMemoryException. La valeur par défaut est false (l'optimisation de la mémoire est
désactivée afin d'améliorer les performances).


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

