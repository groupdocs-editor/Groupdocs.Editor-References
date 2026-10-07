---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Levert gegevens voor het MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs‑event."
type: docs
weight: 22
url: /nl/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Levert gegevens voor de

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

event.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Haalt op of stelt de bestandsnaam (zoals in het Markdown-document) in die zal worden |
verwerken.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Haalt op of stelt de bestandsnaam (zoals in het Markdown-document) in die zal worden |
verwerken.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Geeft een waarde die aangeeft of deze afbeelding een absolute URI‑link heeft. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Geeft een waarde die aangeeft of deze afbeelding een absolute URI‑link heeft. |
|
|  | [setData(byte[] data)](#setData-byte---) | Stelt door de gebruiker geleverde gegevens van de bron in die worden gebruikt als |

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


Haalt op of stelt de bestandsnaam (zoals in het Markdown-document) in die zal worden
verwerken.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Haalt op of stelt de bestandsnaam (zoals in het Markdown-document) in die zal worden
verwerken.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Geeft een waarde die aangeeft of deze afbeelding een absolute URI‑link heeft.
Waarde:  true  als deze afbeelding een absolute URI‑link heeft; anders,  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Geeft een waarde die aangeeft of deze afbeelding een absolute URI‑link heeft.
Waarde:  true  als deze afbeelding een absolute URI‑link heeft; anders,  false .


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Stelt door de gebruiker geleverde gegevens van de bron in die worden gebruikt als

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] |  |

