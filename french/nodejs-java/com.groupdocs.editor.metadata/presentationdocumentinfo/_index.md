---
title: "PresentationDocumentInfo"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente les métadonnées d'un document Presentation"
type: docs
weight: 14
url: /fr/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document Presentation

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Retourne le format de ce document Presentation |
|
|  | [getPageCount()](#getPageCount--) | Retourne le nombre de diapositives dans ce document Presentation |
|
|  | [getSize()](#getSize--) | Retourne la taille en octets de ce document Presentation |
|
|  | [isEncrypted()](#isEncrypted--) | Indique si ce document de présentation spécifique est chiffré et nécessite un mot de passe pour l'ouverture |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Génère et renvoie un aperçu de la diapositive sélectionnée sous forme d'image SVG |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Retourne le format de ce document Presentation


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Retourne le nombre de diapositives dans ce document Presentation


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Retourne la taille en octets de ce document Presentation


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indique si ce document de présentation spécifique est chiffré et nécessite un mot de passe pour l'ouverture


**Returns:**
booléen
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Génère et renvoie un aperçu de la diapositive sélectionnée sous forme d'image SVG


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | slideIndex | int | Indice basé sur 0 de la diapositive souhaitée. Ne peut pas être inférieur à 0, ne peut pas dépasser le nombre de diapositives dans cette présentation. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

