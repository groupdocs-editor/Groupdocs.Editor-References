---
title: "WordProcessingDocumentInfo"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente les métadonnées d'un document de traitement de texte"
type: docs
weight: 17
url: /fr/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document de traitement de texte

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Renvoie un format de ce document WordProcessing |
|
|  | [getPageCount()](#getPageCount--) | Renvoie le nombre de pages |
|
|  | [getSize()](#getSize--) | Renvoie la taille en octets de ce document WordProcessing |
|
|  | [isEncrypted()](#isEncrypted--) | Détermine si ce document WordProcessing spécifique est chiffré et |
requiert un mot de passe pour l'ouverture
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Génère et renvoie un aperçu de la page sélectionnée sous forme d'image SVG |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Détermine si cette instance est égale à l'autre spécifiée |
instance WordProcessingDocumentInfo
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Renvoie un format de ce document WordProcessing


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Renvoie le nombre de pages


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Renvoie la taille en octets de ce document WordProcessing


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Détermine si ce document WordProcessing spécifique est chiffré et
requiert un mot de passe pour l'ouverture


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Génère et renvoie un aperçu de la page sélectionnée sous forme d'image SVG


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | pageIndex | int | Indice basé sur 0 de la page souhaitée. Ne peut pas être inférieur à 0, ne peut pas dépasser le nombre de pages de ce document WordProcessing. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Détermine si cette instance est égale à l'autre spécifiée
instance WordProcessingDocumentInfo


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Autre instance WordProcessingDocumentInfo, qui doit être vérifiée pour l'égalité avec celle-ci |
|

**Returns:**
booléen - True si égaux, false si différents

