---
title: "SpreadsheetDocumentInfo"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente les métadonnées d'un document Spreadsheet"
type: docs
weight: 15
url: /fr/nodejs-java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document Spreadsheet

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Renvoie le format de ce document de feuille de calcul |
|
|  | [getPageCount()](#getPageCount--) | Renvoie le nombre d'onglets |
|
|  | [getSize()](#getSize--) | Renvoie la taille en octets de ce document de feuille de calcul |
|
|  | [isEncrypted()](#isEncrypted--) | Indique si ce document de feuille de calcul spécifique est chiffré et |
nécessite un mot de passe pour l'ouverture
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Génère et renvoie un aperçu de la feuille de calcul sélectionnée sous forme d'image SVG |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Détermine si cette instance est égale à l'autre spécifiée |
Instance de SpreadsheetDocumentInfo
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Renvoie le format de ce document de feuille de calcul


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Renvoie le nombre d'onglets


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Renvoie la taille en octets de ce document de feuille de calcul


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indique si ce document de feuille de calcul spécifique est chiffré et
nécessite un mot de passe pour l'ouverture


**Returns:**
booléen
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Génère et renvoie un aperçu de la feuille de calcul sélectionnée sous forme d'image SVG


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | worksheetIndex | int | Indice basé sur 0 de la feuille de calcul souhaitée. Ne peut pas être inférieur à 0, ne peut pas dépasser le nombre de feuilles de calcul dans ce classeur. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Détermine si cette instance est égale à l'autre spécifiée
Instance de SpreadsheetDocumentInfo


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Autre instance de SpreadsheetDocumentInfo, qui doit être vérifiée pour l’égalité avec celle-ci |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

