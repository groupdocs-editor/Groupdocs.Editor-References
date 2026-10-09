---
title: "TextualDocumentInfo"
second_title: "Référence d'API GroupDocs.Editor pour Node.js via Java"
description: "Représente les métadonnées d'un document textuel comme XML, HTML ou texte brut TXT"
type: docs
weight: 16
url: /fr/nodejs-java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Représente les métadonnées d'un document textuel comme XML, HTML ou texte brut
(TXT)

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | Retourne le format de ce document textuel. |
|
|  | [getPageCount()](#getPageCount--) | Retourne toujours 1 |
|
|  | [getSize()](#getSize--) | Retourne la taille en octets (pas le nombre de caractères) de ce texte |
document
|
|  | [isEncrypted()](#isEncrypted--) | Retourne toujours 'false', car les documents textuels ne peuvent pas être chiffrés. |
|
|  | [getEncoding()](#getEncoding--) | Retourne l'encodage présumé détecté du document texte |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Retourne le format de ce document textuel. Peut ne pas être correct à 100% dans
certains cas.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Retourne toujours 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Retourne la taille en octets (pas le nombre de caractères) de ce texte
document


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Retourne toujours 'false', car les documents textuels ne peuvent pas être chiffrés.


**Returns:**
booléen
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Retourne l'encodage présumé détecté du document texte


**Returns:**
java.nio.charset.Charset
