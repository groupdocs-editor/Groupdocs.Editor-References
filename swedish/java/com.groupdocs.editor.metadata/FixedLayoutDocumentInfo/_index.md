---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar metadata för ett dokument med fast layoutformat som PDF eller XPS."
type: docs
weight: 12
url: /sv/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Representerar metadata för ett dokument med fast layoutformat som PDF eller XPS.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta fixed-layout-formatdokument |
|
|  | [getPageCount()](#getPageCount--) | Returnerar antalet sidor |
|
|  | [getSize()](#getSize--) | Returnerar storleken i byte för detta fixed-layout-formatdokument |
|
|  | [isEncrypted()](#isEncrypted--) | Avgör om detta specifika fixed-layout-formatdokument är krypterat och kräver lösenord för öppning |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Avgör om denna instans är lika med den andra specificerade FixedLayoutDocumentInfo-instansen |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Returnerar ett format för detta fixed-layout-formatdokument


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar antalet sidor


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storleken i byte för detta fixed-layout-formatdokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Avgör om detta specifika fixed-layout-formatdokument är krypterat och kräver lösenord för öppning


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Avgör om denna instans är lika med den andra specificerade FixedLayoutDocumentInfo-instansen


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Annan FixedLayoutDocumentInfo-instans som bör jämföras för likhet med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

