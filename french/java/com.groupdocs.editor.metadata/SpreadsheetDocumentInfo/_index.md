---
title: "SpreadsheetDocumentInfo"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente les métadonnées d'un document de feuille de calcul"
type: docs
weight: 15
url: /fr/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document de feuille de calcul

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Renvoie le format de ce document Spreadsheet |
|
|  | [getPageCount()](#getPageCount--) | Renvoie le nombre d'onglets |
|
|  | [getSize()](#getSize--) | Renvoie la taille en octets de ce document Spreadsheet |
|
|  | [isEncrypted()](#isEncrypted--) | Indique si ce document Spreadsheet spécifique est chiffré et |
requiert un mot de passe pour l'ouverture
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Génère et renvoie un aperçu de la feuille de calcul sélectionnée sous forme d'image SVG |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Détermine si cette instance est égale à l'autre spécifiée |
instance SpreadsheetDocumentInfo
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Renvoie le format de ce document Spreadsheet


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


Renvoie la taille en octets de ce document Spreadsheet


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indique si ce document Spreadsheet spécifique est chiffré et
requiert un mot de passe pour l'ouverture


**Returns:**
boolean
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
instance SpreadsheetDocumentInfo


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Autre instance SpreadsheetDocumentInfo, qui doit être vérifiée pour l'égalité avec celle-ci |
|

**Returns:**
booléen - True si égaux, false si différents

