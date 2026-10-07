---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Tillhandahåller data för händelsen MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs."
type: docs
weight: 22
url: /sv/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Tillhandahåller data för

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

händelse.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Hämtar eller anger filnamnet (så som det är i Markdown‑dokumentet) som kommer att |
behandlas.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Hämtar eller anger filnamnet (så som det är i Markdown‑dokumentet) som kommer att |
behandlas.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Hämta ett värde som indikerar om den här bilden har en absolut URI‑länk. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Hämta ett värde som indikerar om den här bilden har en absolut URI‑länk. |
|
|  | [setData(byte[] data)](#setData-byte---) | Ställer in användarlevererade data för resursen som används om |

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

|
### MarkdownImageLoadArgs() {#MarkdownImageLoadArgs--}
```
public MarkdownImageLoadArgs()
```


### getImageFileName() {#getImageFileName--}
```
public final String getImageFileName()
```


Hämtar eller anger filnamnet (så som det är i Markdown‑dokumentet) som kommer att
behandlas.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Hämtar eller anger filnamnet (så som det är i Markdown‑dokumentet) som kommer att
behandlas.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Hämta ett värde som indikerar om den här bilden har en absolut URI‑länk.
Värde:  true  om denna bild har en absolut URI-länk; annars,  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Hämta ett värde som indikerar om den här bilden har en absolut URI‑länk.
Värde:  true  om denna bild har en absolut URI-länk; annars,  false .


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Ställer in användarlevererade data för resursen som används om

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] |  |

