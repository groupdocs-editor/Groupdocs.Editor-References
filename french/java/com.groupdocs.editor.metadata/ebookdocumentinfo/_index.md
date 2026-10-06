---
title: "EbookDocumentInfo"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente les métadonnées d'un document EBook"
type: docs
weight: 10
url: /fr/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document EBook

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Renvoie le format de ce document |
|
|  | [getPageCount()](#getPageCount--) | Renvoie le nombre de pages dans le cas du MOBI ou AZW3 ou le nombre de chapitres dans le cas de l'ePub. |
|
|  | [getSize()](#getSize--) | Renvoie la taille en octets de ce document eBook. |
|
|  | [isEncrypted()](#isEncrypted--) | Comme les documents eBook ne peuvent pas être chiffrés avec un mot de passe, cette propriété renvoie toujours 'false'. |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Détermine si cette instance est égale à l'autre instance EbookDocumentInfo spécifiée. |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Renvoie le format de ce document


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Renvoie le nombre de pages dans le cas du MOBI ou AZW3 ou le nombre de chapitres dans le cas de l'ePub.

<br />

*** ** * ** ***

Les documents eBook n'ont généralement pas de pages fixes et donc pas de nombre de pages. Dans le cas de l'ePub, il est possible de calculer un nombre de chapitres. Cependant, les formats MOBI et AZW3 n'ont pas non plus de chapitres, ainsi ce nombre est calculé à partir d'une taille de page standard définie à A4 en orientation portrait.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Renvoie la taille en octets de ce document eBook.


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Comme les documents eBook ne peuvent pas être chiffrés avec un mot de passe, cette propriété renvoie toujours 'false'.


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Détermine si cette instance est égale à l'autre instance EbookDocumentInfo spécifiée.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Autre instance EbookDocumentInfo, qui doit être vérifiée pour l'égalité avec celle-ci. |
|

**Returns:**
booléen - True si égaux, false si différents

