---
title: "EmailDocumentInfo"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente les métadonnées d'un document email de tout format email pris en charge"
type: docs
weight: 11
url: /fr/nodejs-java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document email de tout format email pris en charge

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Renvoie le format de ce document email |
|
|  | [getPageCount()](#getPageCount--) | Toujours renvoie 1, car les documents email n’ont pas de vue paginée |
|
|  | [getSize()](#getSize--) | Renvoie la taille en octets de ce document email |
|
|  | [isEncrypted()](#isEncrypted--) | Comme les documents email ne peuvent pas être chiffrés avec un mot de passe, cette propriété renvoie toujours 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Détermine si cette instance est égale à l’autre instance spécifiée de EmailDocumentInfo |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Renvoie le format de ce document email


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Toujours renvoie 1, car les documents email n’ont pas de vue paginée


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Renvoie la taille en octets de ce document email


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Comme les documents email ne peuvent pas être chiffrés avec un mot de passe, cette propriété renvoie toujours 'false'


**Returns:**
booléen
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Détermine si cette instance est égale à l’autre instance spécifiée de EmailDocumentInfo


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Autre instance de EmailDocumentInfo, qui doit être vérifiée pour l’égalité avec celle-ci |
|

**Returns:**
booléen - Vrai si égaux, faux si différents

