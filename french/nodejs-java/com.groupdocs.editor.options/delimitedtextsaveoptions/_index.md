---
title: "DelimitedTextSaveOptions"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Contient des options pour générer et enregistrer des documents de type feuille de calcul texte (CSV, à base de tabulations, etc.) qui utilisent un séparateur"
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Contient des options pour générer et enregistrer des documents de type feuille de calcul texte
(CSV, à base de tabulations, etc.), qui utilisent un séparateur (délimiteur)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated-values

<br />


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Ce constructeur sans paramètre crée une nouvelle instance de DelimitedTextSaveOptions avec un séparateur par défaut point-virgule (;) (peut être modifié ensuite via |
Séparateur
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) property)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Crée une instance de la classe d'options pour le texte délimité avec obligatoire |
séparateur (délimiteur)
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents basés sur du texte |
documents de feuille de calcul
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents basés sur du texte |
documents de feuille de calcul
|
|  | [getEncoding()](#getEncoding--) | Permet de définir un encodage pour le document de feuille de calcul basé sur du texte. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Permet de définir un encodage pour le document de feuille de calcul basé sur du texte. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Indique si les lignes et colonnes vides en tête doivent être tronquées comme |
ce que fait MS Excel
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Indique si les lignes et colonnes vides en tête doivent être tronquées comme |
ce que fait MS Excel
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Indique si les séparateurs doivent être générés pour une ligne vide. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Indique si les séparateurs doivent être générés pour une ligne vide. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Ce constructeur sans paramètre crée une nouvelle instance de DelimitedTextSaveOptions avec un séparateur par défaut point-virgule (;) (peut être modifié ensuite via
Séparateur
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) property)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Crée une instance de la classe d'options pour le texte délimité avec obligatoire
séparateur (délimiteur)


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | séparateur | java.lang.String | Séparateur de chaîne (délimiteur) pour les documents de feuille de calcul basés sur du texte |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents basés sur du texte
documents de feuille de calcul


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Permet de spécifier un séparateur de chaîne (délimiteur) pour les documents basés sur du texte
documents de feuille de calcul


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Permet de définir un encodage pour le document de feuille de calcul basé sur du texte. Par
défaut (et si non spécifié) est UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Permet de définir un encodage pour le document de feuille de calcul basé sur du texte. Par
défaut (et si non spécifié) est UTF8.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Indique si les lignes et colonnes vides en tête doivent être tronquées comme
ce que fait MS Excel


**Returns:**
booléen -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Indique si les lignes et colonnes vides en tête doivent être tronquées comme
ce que fait MS Excel


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Indique si les séparateurs doivent être générés pour une ligne vide. Par défaut
la valeur est false ce qui signifie que le contenu pour la ligne vide sera vide.


**Returns:**
booléen -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Indique si les séparateurs doivent être générés pour une ligne vide. Par défaut
la valeur est false ce qui signifie que le contenu pour la ligne vide sera vide.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

