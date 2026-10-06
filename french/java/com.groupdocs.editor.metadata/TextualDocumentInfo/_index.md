---
title: "TextualDocumentInfo"
second_title: "Référence API de GroupDocs.Editor pour Java"
description: "Représente les métadonnées d'un document textuel tel que XML, HTML ou texte brut TXT"
type: docs
weight: 16
url: /fr/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document textuel tel que XML, HTML ou texte brut
(TXT)

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Renvoie le format de ce document textuel. |
|
|  | [getPageCount()](#getPageCount--) | Renvoie toujours 1 |
|
|  | [getSize()](#getSize--) | Renvoie la taille en octets (pas le nombre de caractères) de ce texte |
document
|
|  | [isEncrypted()](#isEncrypted--) | Renvoie toujours 'false', car les documents textuels ne peuvent pas être chiffrés. |
|
|  | [getEncoding()](#getEncoding--) | Renvoie l'encodage détecté présumé du document texte |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Renvoie le format de ce document textuel. Peut ne pas être 100 % correct dans
certains cas.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Renvoie toujours 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Renvoie la taille en octets (pas le nombre de caractères) de ce texte
document


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Renvoie toujours 'false', car les documents textuels ne peuvent pas être chiffrés.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Renvoie l'encodage détecté présumé du document texte


**Returns:**
java.nio.charset.Charset
