---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt Metadaten eines Präsentationsdokuments dar"
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Stellt Metadaten eines Präsentationsdokuments dar

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Gibt ein Format dieses Präsentationsdokuments zurück |
|
|  | [getPageCount()](#getPageCount--) | Gibt die Anzahl der Folien in diesem Präsentationsdokument zurück |
|
|  | [getSize()](#getSize--) | Gibt die Größe in Bytes dieses Präsentationsdokuments zurück |
|
|  | [isEncrypted()](#isEncrypted--) | Gibt an, ob dieses bestimmte Präsentationsdokument verschlüsselt ist und ein Passwort zum Öffnen benötigt |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Erzeugt und gibt eine Vorschau der ausgewählten Folie in Form eines SVG‑Bildes zurück |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Gibt ein Format dieses Präsentationsdokuments zurück


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Gibt die Anzahl der Folien in diesem Präsentationsdokument zurück


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Gibt die Größe in Bytes dieses Präsentationsdokuments zurück


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Gibt an, ob dieses bestimmte Präsentationsdokument verschlüsselt ist und ein Passwort zum Öffnen benötigt


**Returns:**
boolesch
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Erzeugt und gibt eine Vorschau der ausgewählten Folie in Form eines SVG‑Bildes zurück


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | slideIndex | int | 0‑basierter Index der gewünschten Folie. Darf nicht kleiner als 0 sein und die Anzahl der Folien in dieser Präsentation nicht überschreiten. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

