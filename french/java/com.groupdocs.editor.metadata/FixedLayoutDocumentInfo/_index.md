---
title: "FixedLayoutDocumentInfo"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente les métadonnées d'un document au format mise en page fixe comme PDF ou XPS"
type: docs
weight: 12
url: /fr/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Représente les métadonnées d'un document au format mise en page fixe comme PDF ou XPS

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Renvoie un format de ce document à mise en page fixe |
|
|  | [getPageCount()](#getPageCount--) | Renvoie le nombre de pages |
|
|  | [getSize()](#getSize--) | Renvoie la taille en octets de ce document à mise en page fixe |
|
|  | [isEncrypted()](#isEncrypted--) | Détermine si ce document à mise en page fixe spécifique est chiffré et requiert un mot de passe pour l'ouverture |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Détermine si cette instance est égale à l'autre instance FixedLayoutDocumentInfo spécifiée |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Renvoie un format de ce document à mise en page fixe


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


Renvoie la taille en octets de ce document à mise en page fixe


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Détermine si ce document à mise en page fixe spécifique est chiffré et requiert un mot de passe pour l'ouverture


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Détermine si cette instance est égale à l'autre instance FixedLayoutDocumentInfo spécifiée


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Autre instance FixedLayoutDocumentInfo, qui doit être vérifiée pour l'égalité avec celle-ci |
|

**Returns:**
booléen - True si égaux, false si différents

