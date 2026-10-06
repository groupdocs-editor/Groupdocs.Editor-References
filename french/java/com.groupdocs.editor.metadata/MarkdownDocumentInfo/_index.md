---
title: "MarkdownDocumentInfo"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente les métadonnées d'un document Markdown"
type: docs
weight: 13
url: /fr/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document Markdown

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Renvoie un format de ce document Markdown \u2014 toujours le même |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Renvoie le nombre de pages. |
|
|  | [getSize()](#getSize--) | Renvoie la taille en octets de ce document Markdown |
|
|  | [isEncrypted()](#isEncrypted--) | Parce que les documents Markdown ne peuvent pas être chiffrés avec un mot de passe, cette |
propriété renvoie toujours 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Détermine si cette instance est égale à l'autre spécifiée |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Renvoie un format de ce document Markdown \u2014 toujours le même
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Renvoie le nombre de pages. Les documents Markdown n'ont généralement pas de pages fixes
et donc le nombre de pages, ainsi ce nombre est calculé à partir de la taille de page standard
défini sur A4 en orientation portrait.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Renvoie la taille en octets de ce document Markdown


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Parce que les documents Markdown ne peuvent pas être chiffrés avec un mot de passe, cette
propriété renvoie toujours 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Détermine si cette instance est égale à l'autre spécifiée
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Autre instance [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo), qui doit être vérifiée pour l'égalité avec celle-ci |
|

**Returns:**
booléen - True si égaux, false si différents

