---
title: "MarkdownImageLoadArgs"
second_title: "GroupDocs.Editor für Java API-Referenz"
description: "Stellt Daten für das Ereignis MGroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImageMarkdownImageLoadArgs bereit."
type: docs
weight: 22
url: /de/java/com.groupdocs.editor.options/markdownimageloadargs/
---
**Inheritance:**
java.lang.Object
```
public class MarkdownImageLoadArgs
```

Stellt Daten für das

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)

Ereignis.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MarkdownImageLoadArgs()](#MarkdownImageLoadArgs--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getImageFileName()](#getImageFileName--) | Liest oder setzt den Dateinamen (wie im Markdown-Dokument) der verwendet wird |
verarbeiten.
|
|  | [setImageFileName(String value)](#setImageFileName-java.lang.String-) | Liest oder setzt den Dateinamen (wie im Markdown-Dokument) der verwendet wird |
verarbeiten.
|
|  | [isAbsoluteUri()](#isAbsoluteUri--) | Gibt einen Wert zurück, der angibt, ob dieses Bild einen absoluten URI-Link hat. |
|
|  | [setAbsoluteUri(boolean value)](#setAbsoluteUri-boolean-) | Gibt einen Wert zurück, der angibt, ob dieses Bild einen absoluten URI-Link hat. |
|
|  | [setData(byte[] data)](#setData-byte---) | Setzt vom Benutzer bereitgestellte Daten der Ressource, die verwendet werden, wenn |

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


Liest oder setzt den Dateinamen (wie im Markdown-Dokument) der verwendet wird
verarbeiten.


**Returns:**
java.lang.String
### setImageFileName(String value) {#setImageFileName-java.lang.String-}
```
public final void setImageFileName(String value)
```


Liest oder setzt den Dateinamen (wie im Markdown-Dokument) der verwendet wird
verarbeiten.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### isAbsoluteUri() {#isAbsoluteUri--}
```
public final boolean isAbsoluteUri()
```


Gibt einen Wert zurück, der angibt, ob dieses Bild einen absoluten URI-Link hat.
Wert:  true  wenn dieses Bild einen absoluten URI-Link hat; andernfalls  false .


**Returns:**
boolean
### setAbsoluteUri(boolean value) {#setAbsoluteUri-boolean-}
```
public final void setAbsoluteUri(boolean value)
```


Gibt einen Wert zurück, der angibt, ob dieses Bild einen absoluten URI-Link hat.
Wert:  true  wenn dieses Bild einen absoluten URI-Link hat; andernfalls  false .


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### setData(byte[] data) {#setData-byte---}
```
public final void setData(byte[] data)
```


Setzt vom Benutzer bereitgestellte Daten der Ressource, die verwendet werden, wenn

M:GroupDocs.Editor.Options.IMarkdownImageLoadCallback.ProcessImage(MarkdownImageLoadArgs)



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Daten | byte[] |  |

